# IP_2018_Bandtec
integration project of research and innovation


					COMANDOS GIT 

--para checar o branch git branch
ira aparecer
*master
*teste

git checkout -b teste para criar um branch

--para MUDAR o branch
git checkout teste 
git checkout master

git init --> para iniciar o git

git pull origin master 

--> para dar push

git status

git add .

git status

git commit -m "comentario"

git push -u origin master <--- o -u

Se voc� n�o clonou um reposit�rio existente e quer conectar seu reposit�rio a um servidor remoto, voc� deve adicion�-lo com
git remote add origin <servidor>
Agora voc� � capaz de enviar suas altera��es para o servidor remoto selecionado.

ramificando
Branches ("ramos") s�o utilizados para desenvolver funcionalidades isoladas umas das outras. 
O branch master � o branch "padr�o" quando voc� cria um reposit�rio. 
Use outros branches para desenvolver e mescle-os (merge) ao branch master ap�s a conclus�o.
sempre ira aparecer em qual vc esta entre parenteses (master)/(teste) por padrao � o master
--->>>>>>(ATEN��O)antes de qualquer push ou commit fazer o pull para baixar o prejeto novo

verificar no site se foi


------------ outros comandos -------------------


git push -f origin master -> forcar a commit (N�O RECOMENDADO USAR NO NOSSO PROJETO).

ssh-keygen -> apos digitar confirmar onde vai e depois digite uma senha  ele cria uma senha ao seu repositorio deixando mais seguro o repositorio (usar so quando vc criar um novo repositorio) 
# >>>> depois de usar esse comando verificar se seu computador esta exibindo itens ocultos 
passo 1 se for windows va em C:/Usuarios/nome_do_desktop/.ssh
passo 2 dentro dela vai ter 2 arquivos abrir id_rsa como txt copiar a chave que esta nela
passo 3 abrir a foto do seu perfil no github em settings e depois SSH and GPG keys
passo 4 clicar em new SSH key adiciona um titulo e depois cole sua key e salve.

git config --global push.default current -> restaura as config do push

git clone git@github.com:R-robot/IP_2018_Bandtec.git clonar o repositorio ssh 

git clone  https://github.com/R-robot/IP_2018_Bandtec.git

git remote add origin git@github.com:R-robot/IP_2018_Bandtec.git --> adicionar um acesso ao repositorio

git config --global user.name "seu nome aqui" --> deixar como padr�o seu usuario

git config --global user.email "seu email aqui" --> como padr�o seu email





	REGRAS ANTES DO COMMIT/PUSH

#1 Ler sempre a documenta��o.
#2 Ao atualizar algo sobre o projeto comunicar a todos sobre quaisquer informa�oes.
#3 Alertar a todos no que esta mexendo no projeto ou ira mexer.
#4 Sempre dar git pull antes de mexer no projeto.
#5 N�o for�ar o push  para n�o criar branchs(s�o linhas em que o projeto sai e � alterado perdendo a vers�o anterior)
(ATEN��O !!! o git push -f USAR somente em casos extremos). 
#6 Sempre comentar no git commit -m o que foi feito ou alterado.
#7 Ao dar git push e der erro de commit , avisar ao grupo o que esta acontecendo (pois possa haver algum commit travado).
#8 criar um issue especifico e direcionado a cada usuario
