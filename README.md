# Instalação do Linux Ubuntu

1- Abra o **“Prompt de Comando (cmd)”**

2- Comando que define que vamos trabalhar por padrão com o WSL versão 2.  
**`wsl --set-default-version 2`**

3- Vamos instalar o **Linux Ubuntu versão 20.04**.  
**`wsl --install -d Ubuntu-20.04`**

Após executar o comando acima, irá exibir uma janela do terminal do Linux Ubuntu, conforme imagem abaixo:

![image](https://user-images.githubusercontent.com/126198206/221364434-c6c8bfcf-def2-4658-b1d5-01fc3b1dcce8.png)

Caso exiba a mensagem abaixo, favor acessar o site da Microsoft (https://aka.ms/wsl2kernel) para baixar e instalar o Kernel do Linux.

![image](https://user-images.githubusercontent.com/126198206/221364452-25bfb760-a827-4922-b109-0b80a24bacd7.png)

A partir daqui os comandos serão no terminal do Linux.

4- Após a instalação, buscar a lista de atualizações para o SO.  
**`sudo apt update`**

5- Fazer a atualização do SO.  
**`sudo apt upgrade`**

Para forçar o restart do __kernel Linux__, na janela de **terminal do Windows (cmd)** executar o comando:  
**`wsl --shutdown`**
