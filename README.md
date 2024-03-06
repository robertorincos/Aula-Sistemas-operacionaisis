# Aula-Sistemas-operacionaisis
Envio de exercícios de lab da máteria sistemas operacionais

#Lab01a - Hello World
Preparando ambiente:
Primeiro foi instalado o git no ambiente:
![image](https://github.com/robertorincos/Aula-Sistemas-operacionaisis/assets/112891254/3699f501-20fb-496e-b917-88a15783be22)

Hello_World.c:

Apôs isso foi criado o arquivo em C com o código Hello World:
ubuntu@ip-172-31-38-196:~$ nano hello_world.c
Então para compilar o código foi utilizado o comando:
ubuntu@ip-172-31-38-196:~$ gcc hello_world.c -o hello_world
E por fim foi executado:
![image](https://github.com/robertorincos/Aula-Sistemas-operacionaisis/assets/112891254/6186f3e5-8f60-41b1-a5ca-40238f2de5f6)

GIT:
Começamos iniciando um novo repositorio GIT:
ubuntu@ip-172-31-38-196:~$ git init
então adcionamos o Hello_world.c ao repositorio e depois um commit do arquivo no repositório:
ubuntu@ip-172-31-38-196:~$ git add hello_world.c
ubuntu@ip-172-31-38-196:~$ git commit -m "Adiciona Hello World em C"
![image](https://github.com/robertorincos/Aula-Sistemas-operacionaisis/assets/112891254/85bee70b-d768-4dd8-80b7-21180865a53b)
Por fim adcionamos o endereço do repositorio no GITHUB e enviamos o codigo:
ubuntu@ip-172-31-38-196:~$ git remote add origin https://github.com/robertorincos/Aula-Sistemas-operacionaisis
ubuntu@ip-172-31-38-196:~$ git push -u origin master
O ambiente pede o usário e senha:
![image](https://github.com/robertorincos/Aula-Sistemas-operacionaisis/assets/112891254/6c999574-1fca-49cf-9766-eb2ec0cb83de)

