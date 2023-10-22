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

Baixar as principais extensões do php, para rodar frameworks como o laravel que é um framework PHP:
~~~
sudo apt install
php8.0-mbstring
php8.0-xmlrpc
php8.0-soap
php8.0-gd php8.0-xml
php8.0-cli
php8.0-zip
php8.0-bcmath
php8.0-tokenizer
~~~

Baixar as extensões do banco de dados:
~~~
sudo apt install php8.0-sqlite3
~~~


