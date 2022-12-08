<p align="center">
<img src= "web/peliIMG/cliente.png" height = "128">
</p>


# Taller de Productividad Basada en Herramientas Tecnológicas
![](https://i.imgur.com/waxVImv.png)
## Descripción
  Es una herramienta web que gestiona la base de datos para el manejo de ventas del producto de la microempresa PELISCORP, esta aplicación esta desarrollada en JAVA con Java Server Pages con el objetivo de resolver la problemática que se nos presentó.
## Problema Identificado
- El problema que se identifico es que la empresa no sabe cómo llegar a las personas para la venta de sus películas y con el alto mercado de streaming que hay ellos han tenido perdidas es por eso que en su stock hay películas que no suelen verse en internet
- La empresa no quería login ya que no le importaba eso, solo querían mostrar y vender sus productos, eso será un problema a largo plazo ya que no sabrán quien le consume más.


## Tabla de Contenidos
  **PELISCORP**
  
  - **[nbproject]([nbprojects](https://github.com/Esmeralda-Almaguer/Pelicorp/tree/Master/nbproject))**
    - ant-deploy.xml
    - build-impl.xml
    - genfiles.properties
    - project.properties
    - project.xml
    
  - **[Src]([src](https://github.com/Esmeralda-Almaguer/Pelicorp/tree/Master/src))**
    - conf
      - MANIFEST.MF
    - java
      - Config
        - Conexion.java
        - Fecha.java
      - Controller
        - Controlador.java
        - ControladorIMG.java
      - Model
        - Carrito.java
        - Cliente.java
        - Compra.java
        - Pago.java
        - Producto.java
      - ModelDAO
        - CompraDAO.java
        - PersonaDAO.java
        - ProductoDAO.java
      
  - **[Web]([web](https://github.com/Esmeralda-Almaguer/Pelicorp/tree/Master/web))**
    - META-INF
      - context.xml
    - WEB-INF
      - lib
        - jstl-1.2.jar
        - standard.jar
      web.xml
    - css
      - style.css
    - js
      - funciones.js
      - login.js
    - peliIMG
      - Caratulas Peliculas
    - vistas
      - carrito.jsp
      - error.jsp
      - mensaje.jsp
    index.jsp
  - mysql-connector-java-8.0.27.jar
  - PELISCORP.sql

![](https://i.imgur.com/waxVImv.png)
## Requerimientos
- **Requerimientos Generales**
  - **Servidores de Aplicación
    - apache-tomcat-9.0.58
  - **Web**
     - Bootstrap 4.6.2
     - Bootstrap.min.css
     - Bootstrap-icons 1.10
     - JQuery 3.5.1.min.js
     - popper.min.js
     - sweeralert.min.css
  - **Base de datos** 
    - Server version	8.0.28
- **Paquetes Adicionales** 
  - **[jstl-1.2.jar](web/WEB-INF/lib/jstl-1.2.jar)**
  - **[standard.jar](web/WEB-INF/lib/standard.jar)**
  - **[mysql-connector-java-8.0.27.jar ](mysql-connector-java-8.0.27.jar)**
- **Versión de Java**
  - Obtener la versión más actual de java
## Instalación
 - Descargar el proyecto del repositorio o clonarlo si tiene git
 - Descomprimir el archivo para obtener la carpeta del proyecto
 - Abrimos la carpeta del proyecto
 - Tenemos que añadir el [controlador](mysql-connector-java-8.0.27.jar) de sql en librerías
 - Creamos nuestra base de datos ejecutando el archivo [PelisCorp](PELISCORP.sql)
 - Verificamos que tenemos Tomcat y ejecutamos el JSP alojado en tomCat
 
 **Para implementar esta solución de problema pudiéramos ocupar como lo es Heroku ya que es un ambiente web en el que se puede montar nuestro Java Server Page**
## Configuración
- Instalamos la versión más actual de java ya que sin ella no podremos correr el software
- Configuración del ambiente JAVA
- Si desea cambiar el color y fuente de la página cambiar el [style](web/css/style.css)
- En caso de tener una versión inferior actualizar a la versión mínima requerida

![](https://i.imgur.com/waxVImv.png)
## Uso
La herramienta web es para uso de PELISCORP
## Contribución
- Abrimos el [repositorio ](https://github.com/Esmeralda-Almaguer/Pelicorp)
- En el branch "master" podemos encontrar la version mas actual del software y la mas completa y estable
- En caso de querer ocupar alguna otra versión la rama beta nos puede ayudar
- Del lado derecho tenemos la opción de clone or download
- Tenemos dos opciones a elegir (abrir en el equipo o descargar como zip)
- Cualquiera de las 2 opciones nos puede servir
### **Contribuidores**❤
 <p align="center">
  <a href = "https://github.com/Esmeralda-Almaguer/Pelicorp/graphs/contributors">
    <img src = "https://contrib.rocks/image?repo=Esmeralda-Almaguer/Pelicorp"/>
    </a>
</p>

## RoadMap
Conforme vaya ganando popularidad dentro de su comunidad local, ellos nos podrían solicitar algún tipo de servicio gestionable en línea como lo serían envíos, renta de películas, estamos hablando que necesitaríamos administrar a los clientes, llevar un historial de sus ventas como a su vez nosotros necesitamos contabilizar el número de clientes, filtrar el consumo de producto de nuestros clientes y expedir un recibo que confirme la venta del producto. Se planea hablar con el propietario del negocio y proponerle una actualización de esta herramienta web basada en java, Estará siendo probada por el cliente durante 6 meses en caso de requerir una actualización se mostrará en la rama master
## Créditos
Desarrollado por: 
- **2954958**  Irma Esmeralda Almaguer Rincón
