# restaurantespro-web

## Prerequisitos
- Github Desktop instalado
- Control de Versiones Git Instalado
- Acceso al repositorio de Github

## Guia de inicio rápido

**Ya habiendo cumplido con los prerequisitos debemos:**

1) Ejecutar el comando `docker compose up -d --build` para crear y levantar las imagenes de docker configuradas en nuestro ambiente local
2) Ingresar al Docker desktop y en el contenedor de la base de datos Mysql ingresar a la consola y logearse para crear la base de datos
    usuario: root
    password: secret
    con el comando `mysql -uroot -p`
    solcitara el password indicado arriba.
3) En esa consola del paso 2, creamos la base de datos con el comando `create database quickqr`
4) Ingresamos en el navegador a `http://localhost`
5) Seguimos las instrucciones de configuracion del sistema con este archivo `documentation\index.html` solo los siguientes apartados:
    - **STEP1 Choose Language**
    - **STEP2 Database Configuration**
    - **STEP3 Create Admin**
