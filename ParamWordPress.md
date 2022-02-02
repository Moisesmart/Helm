## DESPLEGAR WORDPRESS CON DOS PARÁMETROS


![wordpress2](https://user-images.githubusercontent.com/72433702/152125343-eedfae2b-a7b7-4658-8058-c64a66ce7cbf.PNG)


## TENDREMOS QUE CREAR UN ARCHIVO PARA QUE AL INSTALAR WORDPRESS LO LEA CON LAS CARACTERÍSTICAS QUE QUERAMOS, EN ESTE CASO CREAREMOS UN ARCHIVO .YAML LLAMADO VALORES


## EJECUTAMOS EL SIGUIENTE COMANDO COMO EJEMPLO:
###  `helm install miblog bitnami/wordpress --set service.type=NodePort -f valores.yaml stable/wordpress`



![valores](https://user-images.githubusercontent.com/72433702/152127742-e7aa7ce8-1bd9-4135-9917-178303d28e2e.PNG)
