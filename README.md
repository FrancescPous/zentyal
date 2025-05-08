Configurar Zentyal com Controlador de domini
En aquesta pràctica tenim una MV amb Zentyal ja instal·lat i configurarem el servei de directori.

L'eina d'administració de Zentyal és via web a l'adreça localhost:8443

1.- Afegir components
Afegirem els components de Controlador de Domini i DNS.

![image](https://github.com/user-attachments/assets/020a06c6-aa57-4d84-964a-fa94fa5ecbab)
![image](https://github.com/user-attachments/assets/df86011f-90bb-4c2a-99d6-29aa4011dbe0)






2.- Habilitar el mòdul de xarxa
Activem el mòdul de xarxa i configurem l'adreça de la tercera interfície de xarxa que és una xarxa privada de centre.





3.- Canviar el nom de domini
Canviarem el nom de domini, el vostre domini serà X.local on X és el vostre cognom, el nom del server serà el vostre nom.





4.- Habilitar el mòdul de controlador de domini
Habilitem el mòdul i a nom netbios ficarem el nostre cognom.







5.- Canviar el password de l'usuari Administrator
L'usuari Administrator és l'administrador del domini, li ficarem una contrasenya vàlida a més d'un nom i cognom.









6.- Afegir un usuari del domini
Afegim un usuari al domini per a provar-lo.





6.- Canviar la configuració del client Windows
A l'adaptador de xarxa de Windows fiquem una IP vàlida a la mateixa xarxa que el server i com a DNS la IP del server Zentyal.

A més unirem Windows al domini.
