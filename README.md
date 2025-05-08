Configurar Zentyal com Controlador de domini
En aquesta pràctica tenim una MV amb Zentyal ja instal·lat i configurarem el servei de directori.

L'eina d'administració de Zentyal és via web a l'adreça localhost:8443

1.- Afegir components
Afegirem els components de Controlador de Domini i DNS.

![image](https://github.com/user-attachments/assets/020a06c6-aa57-4d84-964a-fa94fa5ecbab)
![image](https://github.com/user-attachments/assets/df86011f-90bb-4c2a-99d6-29aa4011dbe0)






2.- Habilitar el mòdul de xarxa
Activem el mòdul de xarxa i configurem l'adreça de la tercera interfície de xarxa que és una xarxa privada de centre.

![image](https://github.com/user-attachments/assets/a9b3136b-58d9-4c5f-bbe6-daa5aa2fd94f)
![image](https://github.com/user-attachments/assets/e700a156-42bf-4ed6-8fd8-faf5590a4c00)




3.- Canviar el nom de domini
Canviarem el nom de domini, el vostre domini serà X.local on X és el vostre cognom, el nom del server serà el vostre nom.
![image](https://github.com/user-attachments/assets/ebba08ad-60bf-4d98-8e5c-abcde10e6484)







4.- Habilitar el mòdul de controlador de domini
Habilitem el mòdul i a nom netbios ficarem el nostre cognom.
![image](https://github.com/user-attachments/assets/c435590f-a66a-40f0-b5f4-428bc9d6d9c3)
![image](https://github.com/user-attachments/assets/6863a643-7ea3-41cc-b5e1-58b7c815d4c8)







5.- Canviar el password de l'usuari Administrator
L'usuari Administrator és l'administrador del domini, li ficarem una contrasenya vàlida a més d'un nom i cognom.

![image](https://github.com/user-attachments/assets/f5ef12b9-f324-40eb-b3aa-9db519f41bff)
![image](https://github.com/user-attachments/assets/78540613-5eb5-4b1b-8a6e-7b9dcd4f0bad)








6.- Afegir un usuari del domini
Afegim un usuari al domini per a provar-lo.
![image](https://github.com/user-attachments/assets/cfddda50-b126-40a7-b91d-fb767d78fd16)
![image](https://github.com/user-attachments/assets/1acec21f-c595-4e81-913c-f752192c251d)





6.- Canviar la configuració del client Windows
A l'adaptador de xarxa de Windows fiquem una IP vàlida a la mateixa xarxa que el server i com a DNS la IP del server Zentyal.

A més unirem Windows al domini.
![image](https://github.com/user-attachments/assets/f6ba7efc-8a05-4b72-b12c-9f2b760c2088)
![image](https://github.com/user-attachments/assets/0e9ce035-2985-4f2e-86fa-f69539ec7f5e)

