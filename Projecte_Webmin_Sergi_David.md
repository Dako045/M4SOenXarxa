# Utilitzant webmin per administrar el servidor

- Entregueu link a un repositori **públic** (un link per alumne) de Github on feu les següents tasques.
- Expliqueu el que feu amb text i captures.
- **Fer tot des de webmin**
- Rúbrica:
  - 2 punts - Estructura del document (portada, índex, captures correctes, text ben formatat...).
  - 1 punt - Exercici 1.
  - 1 punt - Exercici 2.
  - 1 punt - Exercici 3.
  - 1 punt - Exercici 4.
  - 1.5 punt - Exercici 5.
  - 1.5 punt - Exercici 6.
  - 1 punt - Exercici 7.

## 1.- Crear i modificar usuaris

**Fer tot des de webmin**

- Has de crear dos usuaris bakalao_X i techno_X on (X és el vostre cognom).

  ![image](https://github.com/user-attachments/assets/b5115ef7-7eb4-4986-96dc-b625e6ea27e7)
  ![image](https://github.com/user-attachments/assets/33622996-358d-447b-bbd1-3be8079bd64d)
  ![image](https://github.com/user-attachments/assets/d0c40d31-fa5b-4d0e-9f2e-3680654bcd41)

- Els usuaris et passaran el hash de la seva contrasenya, no la contrasenya real. (podeu fer servir openssl).

  ![image](https://github.com/user-attachments/assets/bd527a86-9e23-4ffe-bb0e-5c3b1abbdba8)
  ![image](https://github.com/user-attachments/assets/e534b03d-5b49-49d8-a9e5-05a010b5cea1)
  ![image](https://github.com/user-attachments/assets/a4756803-0af6-486f-9391-225bf357c7c0)


- Cada usuari tindrà un directori a home igual al seu nom d'usuari.

 ![image](https://github.com/user-attachments/assets/f78c9802-5455-44a9-a8b3-7689520b248e)
 ![image](https://github.com/user-attachments/assets/0e30ed1a-f32c-41ff-86e3-d4b348569485)



- Utilitzaran bash com a shell.

 ![image](https://github.com/user-attachments/assets/937efcf9-dfa2-44fd-9650-5a0b23963ebd)
 ![image](https://github.com/user-attachments/assets/dae5a2bf-b6be-419e-98b3-4e31ee891bed)

- Els usuaris estaran dins del grup que tingui el seu mateix nom i dins del grup usuaris_empresa.
  
 ![image](https://github.com/user-attachments/assets/229d7464-08cf-486f-8466-07b80a3f46b3)
 ![image](https://github.com/user-attachments/assets/ac4f021c-31b0-432e-a116-57b85875a8da)
 ![image](https://github.com/user-attachments/assets/577fbf8d-4245-4913-891b-5849dcecf39e)

- L'usuari techno no podrà fer login després del dia 30-04-2025.(he canviat el dia per a que tingui sentit)

![image](https://github.com/user-attachments/assets/db0cfdf2-8867-45ac-b1ba-5d221d548987)

- Comproveu que els usuaris poden iniciar sessió.

 ![image](https://github.com/user-attachments/assets/bd9c2423-a9a1-4f0d-979c-8fc1189baa8b)

- Canvia la data del sistema (utilitzant webmin) i comprova que techno no pot iniciar sessió si estem a dia 01-05-2025.(he canviat la data per a que tingui sentit)

 ![image](https://github.com/user-attachments/assets/360e739a-1cee-443b-a2f0-0a4bd02b7290)
 ![image](https://github.com/user-attachments/assets/ccbf5f48-5780-459f-9fba-1423d676a257)
 ![image](https://github.com/user-attachments/assets/2c0169f8-daa0-45c6-9337-ddcc88b97302)

## 2.- Programar tasques

- Programa una tasca que neteja els paquets de Linux que ja no s'utilitzen una vegada al mes.

 ![image](https://github.com/user-attachments/assets/2a227481-4bbe-41e6-a2ef-2f5d9660c891)
 ![image](https://github.com/user-attachments/assets/a5774700-98b0-4e0b-b69f-eca192b54290)
 ![image](https://github.com/user-attachments/assets/7a9dcaa2-61b6-4d6e-ab35-3f7ee5c891e0)
 ![image](https://github.com/user-attachments/assets/4224f952-5fef-46bd-9b30-6671029dfac1)

- Programa una tasca diaria que apaga l'ordinador a les 14:00.

 ![image](https://github.com/user-attachments/assets/3917e1c6-4595-4d18-91c6-616e74990a6e)
 ![image](https://github.com/user-attachments/assets/d0f58fca-f465-4767-8127-1dbc90b798ea)

- Comprova que funcionen (canvia dia i hora del sistema mitjançant webmin).

![image](https://github.com/user-attachments/assets/bc910d6b-969d-4617-85e6-6e2042dd7ff4)
![image](https://github.com/user-attachments/assets/ac394b6c-3c2e-4f12-b972-3ea9db6a5ea8)
![image](https://github.com/user-attachments/assets/f5113e47-dd77-46da-918b-ffc44243fab7)
![image](https://github.com/user-attachments/assets/b6387aa7-1025-4c6a-b624-f25bac2e64d4)

  
## 3.- Instal·lació de software

- Utilitza webmin per mostrar quins paquets de software es podrien actualitzar.

![image](https://github.com/user-attachments/assets/04ec7f48-1647-4645-a5d8-52563e834c41)
![image](https://github.com/user-attachments/assets/e902f8f6-1436-4e52-873c-0bf908982348)
![image](https://github.com/user-attachments/assets/3cc8836c-543c-4d90-b919-2a905d4cf1a4)

- Des de webmin actualitza un paquet.

![image](https://github.com/user-attachments/assets/e902f8f6-1436-4e52-873c-0bf908982348)
![image](https://github.com/user-attachments/assets/3cc8836c-543c-4d90-b919-2a905d4cf1a4)

- Utilitza webmin per instal·lar un joc de apt.

![image](https://github.com/user-attachments/assets/e3c014a2-a7c5-4dbe-89c6-ea8a7431769b)
![image](https://github.com/user-attachments/assets/63f61688-5a88-47b3-8284-28d1c4b45145)
![image](https://github.com/user-attachments/assets/69c903c9-30ee-41d9-9db8-3b84629a3e2c)

- Utilitza webmin per instal·lar gimp de apt.

![image](https://github.com/user-attachments/assets/4a4cea90-577a-4861-9edb-6c4f2ba24d89)
![image](https://github.com/user-attachments/assets/9141bac3-e71c-43f7-b299-4679613aa873)

- Utilitza webmin per desinatl·lar el joc que heu instal·lat abans.

![image](https://github.com/user-attachments/assets/cc2af321-49e9-48b4-8d9b-92b29884c861)
![image](https://github.com/user-attachments/assets/57a7e449-1e5c-4be2-bae2-534e150dfdfe)
![image](https://github.com/user-attachments/assets/41d224fd-2270-4543-ba34-a1ef91ea4cd8)


## 4.- Serveis

- Utilitza webmin per mostrar els serveis que s'inicien amb el sistema.

![image](https://github.com/user-attachments/assets/c3830dfc-3790-41f8-b00c-cacc22fc81c5)

- Utilitza webmin per mostrar els serveis que estan actius.

![image](https://github.com/user-attachments/assets/7d604db0-5646-4637-845c-e6d88c847fe8)

- Utilitza webmin per mostrar l'estat del servidor Apache.

![image](https://github.com/user-attachments/assets/5f11f1e2-1d48-4d0f-8523-e3fcb4b50d83)

- Utilitza webmin per aturar Apache.

![image](https://github.com/user-attachments/assets/e82a5e49-6534-402b-bc6f-5f71e15aaf89)

- Utilitza webmin per mostrar l'estat del servidor Apache apagat.

![image](https://github.com/user-attachments/assets/3692d029-03f4-4c8d-a8fd-ca9c28997336)

- Utilitza webmin per reiniciar Apache.

![image](https://github.com/user-attachments/assets/a46bd361-f76c-4bc3-bbca-e99027a8af2d)

- Utilitza webmin per mostrar l'estat del servidor Apache reiniciat.

![image](https://github.com/user-attachments/assets/353e0e30-6569-4a83-aca5-195ff28234a6)

## 5.- Quotes de disc

Activa les quotes de disc pels usuaris amb la comanda: 

```
sudo apt install quota quotatool
```

![image](https://github.com/user-attachments/assets/cdb3089f-b6c4-4550-8c87-f9a7b135bb12)

- Utilitza webmin perquè l'usuari bakalao_X no pugui tenir més de 2 MB d'informació al disc.

![image](https://github.com/user-attachments/assets/413fa582-6b0c-4fec-8d86-74fb597ee2f4)
![image](https://github.com/user-attachments/assets/1ffd88db-2d81-4df8-8548-35a3e16de5e2)

- Comprova que el límit de la quota funciona.

![image](https://github.com/user-attachments/assets/d272c808-05ab-4cc0-99d8-5ed1aef8b828)

- Utilitza webmin perquè l'usuari techno no pugui tenir més de 10 fitxers al disc.

![image](https://github.com/user-attachments/assets/5e3403b1-a0ae-4ed5-ac64-f33e0eaec1b3)


- Comprova que el límit de la quota funciona.

![image](https://github.com/user-attachments/assets/02aa048e-9d11-40f5-b54e-7685b3027353)

## 6.- Còpies de seguretat

- Utilitzant el mòdul de Webmin Filesystem Backup fes una còpia de seguretat del directori /home al directori /backups (l'haureu de crear si no existeix).

![image](https://github.com/user-attachments/assets/b073ea65-057e-4d7e-96be-1b3f6b624e3e)
![image](https://github.com/user-attachments/assets/ae702bec-ebe8-4874-8b73-71fea5bfc071)
![image](https://github.com/user-attachments/assets/02886b77-773b-4fdf-9960-57fe244899dd)
![image](https://github.com/user-attachments/assets/33c1f9b9-c8b7-465c-af80-fa4ea74d0302)
![image](https://github.com/user-attachments/assets/a6f32bff-5d02-4d18-b8d9-32594991b655)

- Modifica alguns fitxers de /home.

![image](https://github.com/user-attachments/assets/b1714658-925e-4ffb-9f4e-727011377f80)

- Recupera la còpia de seguretat.

![image](https://github.com/user-attachments/assets/f659f3d5-b28a-4275-b015-fd494eb879dc)
![image](https://github.com/user-attachments/assets/c7cdc5c2-7209-435a-839b-a26daa8401a7)
![image](https://github.com/user-attachments/assets/5aca6956-39c4-471a-91f0-d9ff085d0afc)

- Comprova que els fitxers de /home són els correctes.

![image](https://github.com/user-attachments/assets/06b65513-1e4d-4f78-a2d2-7c623475b9cc)

- Programa una còpia de seguretat de /home/bakalao_X per els divendres a les 21:00.

![image](https://github.com/user-attachments/assets/0ae246e9-7ef4-4d3d-b44c-bb4247f6a9f3)

- Esborra la còpia de seguretat programada anteriorment.

![image](https://github.com/user-attachments/assets/aa1bf419-6af8-4272-9553-80e48454be3a)

## 7.- Compartició

- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "area_public_X" per a usuaris sense autenticar en forma de lectura i escriptura.

![image](https://github.com/user-attachments/assets/617b128e-b499-4dce-bd68-e5fddca8ceef)
![image](https://github.com/user-attachments/assets/ada0bafc-9105-46e4-9239-56d5a528214f)

- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "pontaeri_privat_X" per a usuaris _X i techno només de lectura.

![image](https://github.com/user-attachments/assets/b2afebe6-9244-4492-89ef-3013408eb498)
![image](https://github.com/user-attachments/assets/d2036482-c701-4ff4-8254-83aaa155c0ef)
![image](https://github.com/user-attachments/assets/4c0c60e2-32c1-4fbd-9c0a-6fc4aca0688d)
![image](https://github.com/user-attachments/assets/5a717bf4-f863-42ac-9117-2abce5a9541b)

- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "pontaeri_privat_X" per a usuaris _X i techno només de lectura.

![image](https://github.com/user-attachments/assets/a66792db-69fd-4430-9d58-68eeaa85b954)
![image](https://github.com/user-attachments/assets/58a5ec1c-46f3-4423-a4fc-1ec1ec6014b4)

## Grups
1.- Raul i Francesc

2.- Aleix i Zulema

3.- Jordi i Marc

4.- Sergi i David

5.- Javi i Edgar

6.- Leo

7.- Jan i Unai

8.- Iker
