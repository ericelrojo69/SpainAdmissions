# SpainAdmissions
Projecto Final Eric Spain Admissions

# Tecnologias utilizadas
Php ( Lenguaje del servidor )<br />
Symfony ( Framework que permite utilizar el modelo vista controlador en PHP )<br />
Twig( motor de plantillas )<br />
Boostrap ( Framework CSS)<br />
Postgresql ( Base de datos )<br />

# Requisitos proyecto:
Tener instalado la version php 8.1<br />
Tener postgresql, asi como php-pgsql para las conexiones con la base del proyecto( configurar el fichero .env del proyecto para poner) <br />
Tener el cli de symfony<br />

# Como inciar el proyecto:
Modificamos el fichero .env para ajustar los parametros de la base de datos<br />
Usamos el comando:<br />
  php bin/console make:migration<br />
Para hacer la migracion de la base de datos( eso nos creara las tablas y insertara los datos de forma automatica )<br />
Para iniciar el projecto usamos el comando symfony server:start<br />
Para para el proyecto usaremos symfony server:stop<br />
