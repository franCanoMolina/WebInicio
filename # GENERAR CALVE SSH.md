# GENERAR CALVE SSH
Para emepzar abrimos la consola bash y pegamos el siguiente texto con tu propio correo.
``` 
ssh-keygen -t ed25519 -C "francanmol@gmail.com"
```
Se abra generado un clave ssh con tu correo como etiqueta.
# Agregar clave ssh a github
Ejecutamos nueva ventana de PowerShell con privilegios elevados de administrador y escribiremos los siguientes codigos:

![](./Captura%20de%20pantalla%202025-01-20%20165754.png)


Entraremos en la carpeta ssh para hacerle un cat al documento id_ed25519.pub 
. y nos dara un codigo similar a el siguente: 

`ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIDvHI1v4icMjFvIjwq3M+YkioiBE1V1LpQKe9AEf24Z9 francanmol@gmail.com`

Para el siguiente paso nos meteremos en github y en la seccion settings y en los apartados en forma de columna que tenemos a la derecha nos meteremos en `SSH and GPT keys`, donde agregaremos nueva vlace ssh y meteremos el codigo anterior



