Para Instalar em um CentOS 9 é necessário instalar o Repositório da IRONTEC
Utilizando p editor de texto de sua preferencia no console Linux crie o arquivo irontec.repo no diretório  /etc/yum.repos.d/ 
vim /etc/yum.repos.d/irontec.repo
 

Adicione conteúdo abaixo no arquivo /etc/yum.repos.d/irontec,repo :
[irontec]
name=Irontec RPMs repository
baseurl=http://packages.irontec.com/centos/$releasever/$basearch/
 
Salve o arquivo e baixe a chave publica do repositório IRONTEC 
rpm --import http://packages.irontec.com/public.key
Em seguida de um update nos repositórios e instale com os comandos a seguir
yum update

yum install sngrep
Agora é só usar...
 

 
