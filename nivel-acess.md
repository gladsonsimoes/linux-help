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

Acesso Total (777): Ler, Escrever e Executar
~~~
sudo chmod 777 Directory
~~~

para subpastas:
~~~
sudo chmod 777 ./Directory/*
~~~


