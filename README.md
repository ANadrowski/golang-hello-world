# golang-hello-world
Hello world in Go lang.

Organização:

pasta-do-usuario/
	go/
    	bin
    	pkg
    	src/
        	hello/
           		hello.go


Instalação no Linux (Ubuntu):

1 - Fazer download do arquivo .tar e extraí-lo para a pasta /usr/local com o seguinte comando:
	
	sudo tar -C /usr/local -xzf go1.8.3.linux-amd64.tar.gz

2 - digitar o comando:
	 
	 sudo gedit /etc/profile 

3 - inserir a seguinte linha no final do arquivo:
	
	export PATH=$PATH:/usr/local/go/bin

3 - digitar o comando:
	
	source /etc/profile

4 - Go lang passa a funcionar, para verificar se está tudo ok, basta digitar o seguinte comando:
	
	go version


