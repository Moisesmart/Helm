## DESPLEGAR WORDPRESS CON DOS PARÁMETROS

## Parámetro wordpressscheme=http://moiseswordpress.com` para indicar nuestra url para el acceso a WordPress

## `helm install moiseswordpress bitnami/wordpress --set service.type=NodePort --set wordpressscheme=http://moiseswordpress.com`



## El parámetro wordpressBlogName nos permite mostrar en nuestra página de inicio de WordPress el mensaje de bienvenida

 ## `helm install moiseswordpressblog bitnami/wordpress --set service.type=NodePort --set wordpressBlogName="BIENVENIDO AL BLOG DE MOISÉS"`
