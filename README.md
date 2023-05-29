## INFORMACIÓN DEL PROYECTO

El proyecto consiste en desarrollar una plataforma colaborativa para que la comunidad, principalmente la que que habitan en zona rurales, ingresen datos meteorológicos y/o pueden consultarse en el caso que lo requieran. 
El  principal objetivo es contar con una base de datos hidrometeorológica para que los expertos puedna generar y calibrar de modelos de transformación precipitación-caudal que son un insumo fundamental para el diseño de obras hidráulicas y la generación de sistemas de gestión de amanazas a fin de prevenir a la población en caso de crecidas potencialmente peligrosas.

## CREACIÓN DEL ENTORNO VIRTUAL E INSTALACIÓN DE DJANGO

Abrir el proyecto en Visual Studio Code y hacer clic en Crear ambiente, luego elegir Venv, luego el intérprete Python (última versión), y finalmente pregunta por las dependencias: elegimos requirements.txt. 

## CREACIÓN DEL PROYECTO EN EL DIRECTORIO ACTUAL

Crea las migraciones, que son archivos Python encargados de la base de datos:

`python manage.py makemigrations`

Ejecuta las migraciones, para que se realicen los cambios en la base de datos:

`python manage.py migrate`

Ubicarse en el directorio donde se encuentra el archivo manage.py e escribir en la terminal el siguiente comando:

`python manage.py runserver`

## ABRIR EL PROYECTO EN HTML  

Para acceder ingresar a:
127.0.0.1:8000

## ESTRUCTURA DE LA PAGINA 

Dentro de la barra de navegación los usuarios pueden ver:

*INICIO: se destaca la importancia del proyecto, y pueden direccionar desde el navbar hacia: quienes somos, registrarse, registrar su estacion meteorológica, Base de datos (cargar o acceder) y la forma de contactarse con los que llevan adelante el proyecto.

*QUIENES SOMOS: para informar acerca de los participantes del proyecto y porque estan interesados en la realización de la plataforma

*ESTACIONES METEOROLÓGICAS: los usuarios podrán incorporar estaciones meteorológicas en el lugar que ellos residan o tengan instalados los pluviómetros. Para ello se requiere saber acerca de ellos, donde viven y la ubicación geográfica del punto de medición. Una vez creada la estación podrán ingresar o ver datos desde la pestaña "Base de datos".

*BASE DE DATOS: los usuarios que ya estén logueados y tengan una estación podran cargar datos meteorológicos en la plataforma y sino no tienen una estación igual podran verlos pero sin tener la posiblidad de manipular informacíon.

*ADQUIRIR UN PLUVIOMETRO: los usuarios que quieran participar podrán acceder a un pluviometro gratis que se le enviará a domicilio y para ello deberán solicitarlo en la página

*CONTACTANOS: datos de contacto de los participantes del proyecto 

# Importante:
Si se desea modificar la base de datos el proyecto cuenta con un administador ingresando a 127.0.0.1:8000/admin con el usuario: admin y una contraseña:1234

Para esta entrega solo trabajé con la app usuario (REGISTRATE en el navbar)

# REGISTRARSE

Se le solicitan los datos personales:

*Nombre
*Apellido
*Fecha de nacimiento
*Email

Ingresarán su pais de origen:

*Pais

Indicarán su ciudad e indicarán las coordenadas GPS (latitud y longitud)

Finalmente se le pedirá que realicen un descripción de porque desean participar del proyecto dandole la posibilidad de ingresar una imagen.

Todas las html tienen la posiblidad de volver al menú principal





