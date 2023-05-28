## INFORMACIÓN DEL PROYECTO

El proyecto consiste en desarrollar una plataforma colaborativa para que la comunidad, sobretodo la que que habitan en zona rurales, ingresen datos meteorológicos y/o pueden consultarse en el caso que lo requieran ver las de otros. En una primera instancia, la plataformar se centrará en datos de precipitaciones y niveles de altura de agua y, a futuro, darles la posibilidad de ingresar mayor información. 
El contar con una base de datos hidrometeorológica posibilita a los expertos generar y calibrar de modelos de transformación precipitación-caudal, insumo fundamental para el diseño de obras hidráulicas y la generación de sistemas de gestión de amanazas a fin de prevenir a la población en caso de crecidas potencialmente peligrosas.

## CREACIÓN DEL ENTORNO VIRTUAL E INSTALACIÓN DE DJANGO

Abrir el proyecto en Visual Studio Code y hacer clic en Crear ambiente, luego elegir Venv, luego el intérprete Python (última versión), y finalmente pregunta por las dependencias: elegimos requirements.txt. 

## CREACIÓN DEL PROYECTO EN EL DIRECTORIO ACTUAL

Crea las migraciones, que son archivos Python encargados de la base de datos

`python manage.py makemigrations`

Ejecuta las migraciones, para que se realicen los cambios en la base de datos

`python manage.py migrate`

Ubicarse en el directorio donde se encuentra el archivo manage.py e escribir en la terminal el siguiente comando:

`python manage.py runserver`

## ABRIR EL PROYECTO EN HTML  

Para acceder ingresar a:
127.0.0.1:8000

## ESTRUCTURA DE LA PAGINA 

Dentro de la barra de navegación los usuarios pueden ver:

*INICIO: se destaca la importancia del proyecto, y pueden direccionar hacia quienes somos, base de datos, estaciones meteorológicas y la forma de contactarse con los que llevan adelante el proyecto.

*QUIENES SOMOS: para informar acerca de los participantes del proyecto y porque estan interesados en la realización de la plataforma

*ESTACIONES METEOROLÓGICAS: los usuarios podrán incorporar estaciones meteorológicas en el lugar que ellos residan o tengan instalados los pluviómetros. Para ello se requiere saber acerca de ellos, donde viven y la ubicación geográfica del punto de medición. Una vez creada la estación podrán ingresar o ver datos desde la pestaña "Base de datos".

*CONTACTANOS: datos de contacto de los participantes del proyecto 

# Importante:

Todavia no vimos como logear usuarios pero en el caso que se desee modificar la base de datos el proyecto cuenta con un administador ingresando a 127.0.0.1:8000/admin con el usuario: admin y una contraseña:1234





