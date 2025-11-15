# Proyecto-infraestructura
## Configuración de RAID y LVM
### Crear los raid
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.12.53%20PM.jpeg?raw=true)
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.12.59%20PM.jpeg?raw=true)
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.13.07%20PM.jpeg?raw=true)
### Hacer que los raid sean persistentes
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.13.21%20PM.jpeg?raw=true)
### Crear los volúmenes físicos
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.13.28%20PM.jpeg?raw=true)
### Crear los grupos de volúmenes
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.13.40%20PM.jpeg?raw=true)
### Crear los volúmenes lógicos
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.13.47%20PM.jpeg?raw=true)
### Formatear los volúmenes
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.13.54%20PM.jpeg?raw=true)
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.14.25%20PM.jpeg?raw=true)
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.14.38%20PM.jpeg?raw=true)
### Crear los directorios 
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.14.55%20PM.jpeg?raw=true)
### Montar los volúmenes 
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.15.02%20PM.jpeg?raw=true)
### Hacer los raids permanentes
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.15.17%20PM.jpeg?raw=true)
## Creación de imágenes con Dockerfile
## Apache
### Creación DockerfileApache
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.15.26%20PM.jpeg?raw=true)
### Creación index.html
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.15.32%20PM.jpeg?raw=true)
### Creación login.html
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.15.39%20PM.jpeg?raw=true)
### Creación registro.html
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.15.49%20PM.jpeg?raw=true)
### Creación script.js
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.15.58%20PM.jpeg?raw=true)
### Creación style.css
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.16.04%20PM.jpeg?raw=true)
### Copiar todos los archivos HTML, JS y CSS de la carpeta del proyecto hacia /mnt/apache
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.16.11%20PM.jpeg?raw=true)
### Construir img_apache
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.16.20%20PM.jpeg?raw=true)
### Crear contenedor_apache
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.16.27%20PM.jpeg?raw=true)
### Actualizar los paquetes e instalar nano
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.16.36%20PM.jpeg?raw=true)
## Nginx
### Crear DockerfileNginx
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.16.47%20PM.jpeg?raw=true)
### Crear index.html
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.16.51%20PM.jpeg?raw=true)
### Crear login.html
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.17.01%20PM.jpeg?raw=true)
### Crear registro.html
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.17.15%20PM.jpeg?raw=true)
### Crear script.js
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.17.20%20PM.jpeg?raw=true)
### Crear style.css
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.17.25%20PM.jpeg?raw=true)
### Copiar todos los archivos HTML, JS y CSS de la carpeta del proyecto hacia /mnt/nginx
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.17.35%20PM.jpeg?raw=true)
### Construir img_nginx
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.18.21%20PM.jpeg?raw=true)
### Crear contenedor_nginx
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.18.26%20PM.jpeg?raw=true)
### Actualizar los paquetes e instalar nano
![image alt](https://github.com/Nikollocampo/Proyecto-infraestructura/blob/main/WhatsApp%20Image%202025-11-14%20at%208.18.31%20PM.jpeg?raw=true)
## Mysql
