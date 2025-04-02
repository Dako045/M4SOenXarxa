# Compartició d'impressores per parelles

Aquesta activitat es pot fer per parelles o de forma individual.

L'activitat consta de dues activitats i el treball final és fer un tutorial i una presentació per cada part.

- Tutorial: Pàgina web amb explicació pas a pas de com s'ha resolt la situació proposada. Pots utilitzar qualsevol plataforma que sigui on line i gratuïta con Github, Gitlab, Google Sites...
- Presentació: Amb  l´ordinador fareu una demostració a classe de com ho heu resolt.

# Activitat 1 - Compartir una impressora de Linux a Windows

La vostra oficina disposa d'una impressora centralitzada que està connectada a un equip amb Linux. 
La resta d'ordinadors de l'oficina fan servir Windows 10.
Has de fer que tots els usuaris puguin utilitzar la impressora.
La xarxa de l'oficina fa servir aquestes adreces IP. On X és el número assignat al teu grup.

![image](https://github.com/XaSaFa/MP04/assets/110727546/744d6524-d1c8-4edd-9a9a-fba6acf0a776)

Primer hem instal·lat cups per poder instal·lar una impressora PDF virtual

![image](https://github.com/user-attachments/assets/084d4ed3-39a4-4046-b184-4ccc4fe4d8c5)

Despres l'hem configurat obrint el navegador i anant a l'adreça http://localhost:631 i hem afegit una impressora PDF (Molt important marcar les opció de la dreta)

![image](https://github.com/user-attachments/assets/a5042647-5e69-42f2-a995-4c6608cb1363)

Un cop alli hem ficat la configuració seguent:

![image](https://github.com/user-attachments/assets/ff2118f6-9021-4fe7-96cf-0050ae45b261)


Despres hem anat al fitxer de configuració (/etc/cups/cupsd.conf) i hem fet les següents modificacions:

![image](https://github.com/user-attachments/assets/64cd6c0e-0a77-4c4c-bf1b-fe38dc246c62)
![image](https://github.com/user-attachments/assets/ea5c3ea9-786a-469f-a2ed-03dc5dcc62f6)
![image](https://github.com/user-attachments/assets/e7973712-e7cb-4068-b3a9-ed70e8e61a44)
![image](https://github.com/user-attachments/assets/379f4b06-d779-4fbf-967d-b3a0dfd18367)

Despres d'aquestes modificacions hem anat a windows Panel de control > Dispositius i impressores > Afegir una impressora i ja ens sortira la impressora que hem compartit desde Ubuntu.

![Captura de pantalla 2025-04-02 114444](https://github.com/user-attachments/assets/bbc8b2ac-54d3-41e6-a328-9728e0b8209f)

Un cop afegida comprovem que funciona enviant una pàgina de prova:

![image](https://github.com/user-attachments/assets/ead1df4d-8c57-4ea0-9d6e-166d89e7d575)

I aqui podem comprovar que ha arribat:

![image](https://github.com/user-attachments/assets/eab35896-244d-4888-87c7-e71bebb4130c)



















# Activitat 2 - Compartir una impressora de Windows a Linux

La vostra oficina disposa d'una impressora centralitzada que està connectada a un equip amb Windows 10.
La resta d'ordinadors de l'oficina fan servir Linux.
Has de fer que tots els usuaris puguin utilitzar la impressora.
La xarxa de l'oficina fa servir aquestes adreces IP. On X és el número assignat al teu grup.

![image](https://github.com/XaSaFa/MP04/assets/110727546/1dd6f371-1038-4f82-82cc-35fe39793671)

# Grups de treball:

1.- Aleix i Zulema

2.- Jordi i Marc

3.- Sergi i David

4.- Unai i Jan

5.- Javi i Edgar

6.- Raul i Francesc

7.- Iker 

8.- Leo
