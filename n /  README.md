# Indice
1.Segundo ejercicio.


2.Tercero ejercicio.

3. Se ha creado este propio documento.

4. Bibiliografia.

#Ejercicio 2



## Abro la terminal y uso el comando shh mas el nombre de usuario al que quiero entrar y su ip.


ssh usuario@192.168.0.185*


![imagen](https://github.com/user-attachments/assets/a9132af3-d0c2-4e4b-83d7-fbb553b065bb)



1. Si encuentra un usuario que coincide me pide la contraseña de este , que nos la ha facilitado el profesor.


contraseña DAMWDAWM


2. Uso el comando ls para ver los archivos creados y asi yo compruebo donde estoy se que se puede con pwd tambien.


ls 


3. Con el comando cd me muevo de directorio a escritorio.


cd Escritorio


 4.Con el comando touch creo el archivo txt.


touch Fede.txt


![imagen](https://github.com/user-attachments/assets/f2c1c266-5975-4919-9c8f-df134f918884)



5.on el comando whoami el sistema me dice que el nombre de mi usuario.


whoami


6. Uso el comando nano para poder escribir en el documento que habia creado.


![imagen](https://github.com/user-attachments/assets/a9b265e2-caf4-43db-9ac6-937b793c7c9d)



nano Fede.txt


7.Escribo usuario que es el resultado que me ha dado al utilizar el comando whoami.


Con los siguientes comandos guardo los cambios y salgo del documento.


ctr 0 , enter , ctrl x


nano Fede.txt


Escribo who que es el comando para saber quien esta conectado.


![imagen](https://github.com/user-attachments/assets/4fe4796a-ed66-4d4a-a4bd-187b245898d1)



usuario  tty7         2024-11-11 14:56 (:0)
usuario  pts/1        2024-11-11 15:14 (192.168.0.151)
usuario  pts/2        2024-11-11 15:14 (192.168.0.150)
usuario  pts/3        2024-11-11 15:24 (192.168.0.149)
usuario  pts/4        2024-11-11 15:22 (192.168.0.114)
usuario  pts/5        2024-11-11 15:22 (192.168.0.145)
usuario  pts/6        2024-11-11 15:24 (192.168.0.103)
usuario  pts/7        2024-11-11 15:25 (192.168.0.162)
usuario  pts/9        2024-11-11 15:26 (192.168.0.106)
usuario  pts/8        2024-11-11 15:27 (192.168.0.194)
usuario  pts/10       2024-11-11 15:29 (192.168.0.103)
usuario  pts/11       2024-11-11 15:30 (192.168.0.129)
usuario  pts/12       2024-11-11 15:31 (192.168.0.148)


## Ejercicio 3

1.Instalamos apache

2.Se hace un sudo apt update 

 En /var/www/ creamos una carpeta llamada mi web

 creamos un archivo html

 ![image](https://github.com/user-attachments/assets/918d450e-ada5-4db8-b900-c099bb055aa3)

 
3. Es necesario crear un archivo de host virtual con las directivas correctas.
Similar al predeterminado, pero actualizado para nuestro nuevo directorio y nombre de dominio:

![image](https://github.com/user-attachments/assets/474da06f-0d8c-4b2f-89f3-40e9d6fe0561)

![image](https://github.com/user-attachments/assets/0c29859a-d662-4caf-b865-71d71dd303b7)


![image](https://github.com/user-attachments/assets/df87321b-37b8-46ec-b9bf-0b392778c526)

 4.Modificamos el archivo /etc/hosts

![image](https://github.com/user-attachments/assets/655bb298-cc99-460b-8c29-5714e487a121)

5.Parate el .conf se tiene que ver asi 

![image](https://github.com/user-attachments/assets/f79ffe27-059d-4153-9276-bc191c2ef78b)


6.Por ultimo se vera esto si todo ha ido bien.

![image](https://github.com/user-attachments/assets/386f2e92-dbb0-4dec-b81b-9c6ed9f3b9b5)

### Bibliografia.
1. Documentacion de classroom.

 
3. Documentacion oficial Mardown

   
5. Documentacion oficial apache

