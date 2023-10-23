## Instalação do PHP

Instalar a dependência software-properties-common que permite adicionar repositório de terceiros de forma fácil no ubuntu:
~~~
sudo apt install software-properties-common
~~~

Instalando a última versão do php (versão 8), irá pedir confirmação e aperte o enter
~~~
sudo add-apt-repository ppa:ondrej/php
~~~

Pegar a lista de pacotes atualizadas:
~~~
sudo apt update
~~~

Instalar o php (no caso está a versão 8.0 escolha a versão que deseja instalar e confirme a instalação):
~~~
sudo apt install php8.0
~~~

Verifique se instalou:
~~~
php -v
~~~

Baixar as principais bibliotecas do php <b> (troque a versão do php8.0 para a versão que esteja usando) </b> , para rodar frameworks como o laravel e composer:
~~~
sudo apt install php8.0-mbstring php8.0-xmlrpc php8.0-soap php8.0-gd php8.0-xml php8.0-cli php8.0-zip php8.0-bcmath php8.0-tokenizer php8.0-curl
~~~

Baixar as extensões do banco de dados <b> (troque a versão do php8.0 para a versão que esteja usando) </b> :
~~~
sudo apt install php8.0-sqlite3
~~~


## Remover PHP

Somente das versões 7
~~~
sudo apt-get remove --purge php7*
sudo apt-get autoremove
~~~

Somente da versão em especifico (no caso que é o php 8.1)
~~~
sudo apt-get remove --purge php8.1*
sudo apt-get autoremove
~~~

Remover todas as versões
~~~
sudo apt-get remove --purge php*
sudo apt-get autoremove
~~~


---

Sites de Referencia:

[Removendo php, mysql e apache do linux](https://www.fredericomarinho.com/removendo-php-mysql-e-apache-do-linux/)

