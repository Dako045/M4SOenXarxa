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

Primer hem modificat el fitxer de configuració (/etc/samba/smb.conf) i hem fet les configuracions seguents:

![image](https://github.com/user-attachments/assets/901d6b4e-6fc7-4862-98c4-f557ef9a3a3b)
![image](https://github.com/user-attachments/assets/3bc28864-a883-493d-a732-f0e6547621df)





Despres hem instal·lat cups per poder instal·lar una impressora PDF virtual

![image](https://github.com/user-attachments/assets/084d4ed3-39a4-4046-b184-4ccc4fe4d8c5)

L'hem configurat obrint el navegador i anant a l'adreça http://localhost:631 i hem afegit una impressora PDF (Molt important marcar les opció de la dreta)

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

# Activitat 2 - Compartir una impressora de Windows a Linux

La vostra oficina disposa d'una impressora centralitzada que està connectada a un equip amb Windows 10.
La resta d'ordinadors de l'oficina fan servir Linux.
Has de fer que tots els usuaris puguin utilitzar la impressora.
La xarxa de l'oficina fa servir aquestes adreces IP. On X és el número assignat al teu grup.

![image](https://github.com/XaSaFa/MP04/assets/110727546/1dd6f371-1038-4f82-82cc-35fe39793671)

Primer de tot instal·lem PDF Creator per poder tindre una impressora virtual per poder compartir

![image](https://github.com/user-attachments/assets/9674d41a-94aa-4860-836b-929561edac03)

Despres hem anat al Panel de control > Dispositius i impressores

![image](https://github.com/user-attachments/assets/af1cb4c5-3505-4bb9-92ff-510c65a4bba7)

Ara a l'impressora del PDF Creator l'hi donem click dret > Propiedades de la impresora > Us compartit i marquem l'opció de "Comparteix aquesta impressora".

![image](https://github.com/user-attachments/assets/4a94d0fa-2f8e-47e3-b741-90d843a9728d)

Ara per poder imprimir desde Ubuntu anem al terminal i instal·lem el smbclient

![Captura de pantalla 2025-04-02 124010](https://github.com/user-attachments/assets/8ee9bbcd-12fc-4414-8959-fa0eddbc6f8b)

Fem aquesta comanda per veure una llista de tots els recursos compartits de la IP de Windows:

![Captura de pantalla 2025-04-02 124145](https://github.com/user-attachments/assets/cff0c1bc-07ad-42dd-a958-af3e5fdf91fa)

Entrem al navegador i anem a l'adreça http://localhost:631 per poder afegir l'impressora a l'opció "Add printer" i fiquem tote les configuracions seguents:

![Captura de pantalla 2025-04-02 124219](https://github.com/user-attachments/assets/db857fe4-1dc8-4704-b0d8-27577897cf62)
![Captura de pantalla 2025-04-02 124401](https://github.com/user-attachments/assets/96ddbe12-35bf-4d87-aee2-36c717799d05)
![Captura de pantalla 2025-04-02 124427](https://github.com/user-attachments/assets/26273d31-7889-4f05-8ee4-456195856747)
![Captura de pantalla 2025-04-02 124509](https://github.com/user-attachments/assets/25fc92a6-d154-4026-9ec1-62f5f62f10bd)
![Captura de pantalla 2025-04-02 124526](https://github.com/user-attachments/assets/9260dc70-7d60-44b4-bd0c-7b69d5386d3a)

Un cop tot configurat ja podem veure la impressora desde Ubuntu a Parametres > Impressores

![image](https://github.com/user-attachments/assets/5cc6a1b4-f65f-4d41-a266-4507d790dd77)

Aqui enviem una pagina de prova per veure que funciona correctament

![image](https://github.com/user-attachments/assets/ede22b93-6694-4efd-b933-d0d345235e15)










