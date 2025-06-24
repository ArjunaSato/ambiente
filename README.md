# Preparação de ambiente
Criar uma máquina virtual para instalar as ferramentas e dependências para o estudo de algoritmo e lógica de programação

## Criar o diretório base
Vamos criar um diretório para guardar a nossa máquina virtual. Será criado no Drive D: (Nomeada com o nome do usuário)

<img src="criar-diretorio-d.png">

## Preparação da máquina virtual
### vamos usar a ferramenta de virtualização chamada Virtual Box
<img src="tela -virtualbox.png">

<a href="https://www.virtualbox.org/wiki/Downloads"> Faça o download aqui </a>


## Criando a máquina virtual

<img src="nova-maquina-virtual.png">


## Criando usuario e senha (será solicitado após a instalação do Ubuntu)

<img src="usuario-e-senha.png">

## Inserindo as configurações de Hardware para a instalação do Ubuntu

<img src="hardware1.png">

<img src="hardware2.png">

 Concluindo a configuração de hardware, clique em finalizar. 

# Instalando e configurando o Linux Ubuntu Server

 Após a instalação do Ubuntu, insira o usuario e a senha que criou na configuração da maquina virtualbox

<img src="tela-ubuntu-1.png">
Observação: aperte enter para aparecer o usuario e senha.

## configuração e atualização dos comandos e app do ubuntu

Na tela informa as configurações de hardware utilizados pelo sistema operacional e a quantidade de updates a serem aplicados

<img src="tela-ubuntu-2.png">

Para atualizar o sistema iremos usar os seguintes comandos:

```shell
sudo apt update -y
```
<img src="comando1.png">

```shell
sudo apt upgrade -y 
```
<img src="comando2.png">

_reboot (irá reiniciar o ubuntu)

_instalar o cockpit - ferramenta para gerenciar o servidor, por meio de um ambiente gráfico online
<img src="ferramenta-cockpit.png">



```shell
sudo apt install cockpit
```

<img src="comando3.png">


