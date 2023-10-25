## Comando sudo:

- Podemos definir no terminal de superusuário para todos os comandos que usarmos
~~~
sudo -s
~~~

- ou podemos utilizar o sudo antes do comando que precise de acesso superusuário:
~~~
sudo 
~~~
---


Para ter acesso de escrita , leitura e execucação em um diretório você precisa configurar diferentes tipos de acesso:

As permissões adequadas geralmente seriam 644 no Linux, o que significa que o proprietário pode ler e escrever, enquanto outros podem apenas ler.
~~~
sudo chmod 644 Directory 
~~~

Acesso Total ao propriétario e aos outros:
~~~
sudo chmod 777 Directory
~~~

Acesso Total para subpastas:
~~~
sudo chmod -R 777 Directory
~~~



