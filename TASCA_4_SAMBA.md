Activitat 1

Crea una carpeta a la MV Linux a /srv/samba/compartida1 amb els permisos necessaris perquè pugui accedir tothom.

![image](https://github.com/user-attachments/assets/d6aec244-5999-4b13-95c7-ff90d8073160)

Crea la configuració de SAMBA per compartir la carpeta per a convidats (sense autenticació) amb lectura i escriptura.

![image](https://github.com/user-attachments/assets/06b2b875-c4d6-4b26-b5c0-1ecf68d62905)

Reinicia el servei SAMBA.

![image](https://github.com/user-attachments/assets/bfb31545-e1ab-4b7f-8523-07779ec2bf5e)

Comprova que tens accés des de Windows.

![image](https://github.com/user-attachments/assets/52dd2163-8ad5-4f34-8007-cee8ee9e0d8f)

Crea algun fitxer a la carpeta.

![image](https://github.com/user-attachments/assets/79e2b7b8-8e61-499a-9297-54a656fa201b)


Comprova que s'ha creat a Linux.

![image](https://github.com/user-attachments/assets/880c5547-d376-46f5-ba5d-f46c989deaf2)


Activitat 2

Crea una carpeta a la MV Linux a /srv/samba/compartida2 amb els permisos necessaris.

![image](https://github.com/user-attachments/assets/855820f5-f49a-4c84-926a-664b726e329e)

Crea un usuari local anomenat user1_X (on X és el teu cognom).

![image](https://github.com/user-attachments/assets/12276381-156c-4a73-84af-e2c53102f83c)

Afegeux l'usuari anterior a SAMBA.

![image](https://github.com/user-attachments/assets/39f9bd59-7598-4cb4-a15c-739a4b0b2442)

Crea la configuració de SAMBA per compartir la carpeta per a l'usuari anterior amb lectura i escriptura amb màscara de fitxers 755.

![image](https://github.com/user-attachments/assets/75dd56fb-8f08-4f68-88d4-1a12bd0da5fe)

Reinicia el servei SAMBA.

![image](https://github.com/user-attachments/assets/66eea896-c490-4720-b24b-9f87e2fe5860)

Comprova que tens accés des de Windows amb les credencials de l'usuari.

![image](https://github.com/user-attachments/assets/1bc8dcdd-d7f4-4660-92f8-c0525a6ddd10)

*Ho he fet amb un altre usuari perque no em funcionava

Crea algun fitxer a la carpeta.

![image](https://github.com/user-attachments/assets/1a4b8164-42d5-4c4e-b0b7-b1c54fd21d45)

Comprova que s'ha creat a Linux i té els permisos 755.

![image](https://github.com/user-attachments/assets/6c676383-0b1f-4f06-9119-533558269292)

