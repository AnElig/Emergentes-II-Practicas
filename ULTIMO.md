# Practica-N1
#SISTEMAS EMPRESARIALES
------
>**Carrera:	Ingeniería de Sistemas**

>**Materia:	Emergentes II**

>**Apellidos y nombres: Gutierrez Oruño Ana Eliza**

>**Lugar y fecha: 16/08/2019**

>**INICIAL PATERNO: G** 




> ###  1 ¿ Explique que son los sistemas empresariales?
>
Un sistema empresarial es un elemento central de una organización y garantiza que la información se pueda compartir a través de todas sus funciones de negocios y todos sus niveles de gestión para soportar su operación y administración, cuya falla traería graves consecuencias.
>
> ###  2 Describa cuales son las caracterizticas mas importantes de una aplicacion empresarial
- Acceso a bases de datos, usualmente a bases de datos relacionales.
- Operaciones transaccionales, cumple con las propiedades ACID.
- Escalables, permiten escalabilidad vertical y horizontal.
- Disponibles, idealmente prestan servicios de forma continua.
- Seguras, no todos los usuarios acceden con la misma funcionalidad.
- Permiten integración con otras tecnologías.
- Arquitectura multicapa.

> ###  3 Investigue y proponga cinco instituciones que requiriran aplicaciones de mision critica.
> ###    Justifique su respuesta.
* #### 1) correo electrónico: un elemento vital en la comunicación corporativa, cuya caída parece convertir todo en un caos. En  el caso de las aplicaciones de nivel operativo puede ser aún peor, pues puede quedar detenida la actividad principal de la organización, con todas las consecuencias que esto implica para el negocio.
* #### 2) ministerio de salud: el cual necesitaria una aplicacion que tenga escalabilidad porque siempre va ir en forma de crecimiento los usuarios la natalidad por ejemplo, debera ser flexible para los cambios de actualizacion que habria, debera tener seguridad no cualquier persona solo personal autorizado puede tener los datos e informacion de las personas que utilizen tal aplicacion. 
* #### 3) universidad publica de el alto necesitaria una aplicacion de mision critica ya que el manejo de recursos economicos y humanos debe ser transparente debe tener total flexibilidad y sobre todo seguridad no debe existir ninguna vulneracion de sus datos ademas que debe ser presiso y eficiente.
* #### 4) manaco la zapateria manaco deberia tener una aplicacion de misison critica ya que deberia tener accesibilidad de ver los modelos y precios que ofrecen a sus usuarios y poder venderlos ofrecerlos via online por lo tanto deberia tener flexibilidad a crecer y tener seguridad para q no puedan vulnerar sus datos ademas de eso ser escalable.
* #### 5) helados panda deberia acceder a una aplicacion de mision critica para poder promocionar sus helados y tener mas acercamiento con las personas y poder vender sus productos de manera online publicando sus precios y sabores.
>    
> ###  4 Explique cuales son las diferencias entre escalabilidad horizontal y escalabilidad vertical
 La escala horizontal se refiere a aumentar el número de componentes, mientras que
la escala vertical se refiere a actualizaciones o modernización de los componentes existentes (crecer el hardware).	



> ###  5 Que es un servidor web y un servidor de aplicaciones
Un servidor web Es un servidor que almacena los documentos que componen una página web (HTML, CSS, PHP…) y se la proporciona al usuario para que la visualice completa en su navegador de Internet (toma la petición de un cliente y devuelve algo).
Un servidor de aplicaciones es un dispositivo de software que proporcionan servicios de aplicación a las computadoras cliente.


> ###  6 Con un grafico explique como funciona el protocolo HTTP

![Alt text](https://user-images.githubusercontent.com/53720544/62845954-5810eb00-bc9a-11e9-8c5b-6b06e6f86f88.gif)

El funcionamiento del http se basa en un esquema de petición-respuesta entre el servidor web y el “agente usuario” o cliente que realiza la solicitud de transmisión de datos. 
Un  cliente puede ser un explorador determinado, cuando intentamos abrir una página web, o los  rastreadores web (webcrawlers o arañas web) que las inspeccionan.Por ejemplo: Al abrir una página web específica, el intercambio informativo entre nuestro explorador web y el servidor donde reside la información establecerá de qué manera debe transmitirse la información, en qué lugar están las imágenes y en qué orden se me mostrarán, etc. Este intercambio de comandos de solicitud y códigos de respuesta da como  resultado la representación en mi computador de la misma información contenida  originalmente en el servidor, que puede estar a miles de kilómetros de distancia.
>
> ###  7 Explique los elementos importantes de REQUEST EN HTTP
- Método HTTP (HTTP method, la acción a realizar).
- La página para acceder (URL).
- Form parameters (como argumentos a un método).

> ### 8 Explique los elementos importantes de RESPONSE EN HTTP
- Código de estado (Status code): Indica si la operación fue realizada correctamente o no.
- Tipo de contenido (Content Type): Si el contenido es HTML, una imagen, un archivo PDF, etc.
- Contenido: El HTML, la imagen, etc. 

> 
> ### 9 Describe con un grafico la arquitectura JAVA EE

![Alt text](https://user-images.githubusercontent.com/53720544/62846550-09b21b00-bc9f-11e9-92c0-9d8b40996f55.gif)

La especificación de JavaEE define su arquitectura basándose en los conceptos de capas, containers, componentes, servicios y las características de cada uno de éstos Las aplicaciones JavaEE son divididas en cuatro capas: la capa cliente, la capa web,  la capa negocio y la capa datos 

>- Capa Cliente
Esta capa corresponde a lo que se encuentra en el computador del cliente.
Es la interfaz gráfica del sistema y se encarga de interactuar con el usuario.
JAVAEE tiene soporte para diferentes tipos de clientes incluyendo clientes HTML, applets Java y aplicaciones Java.
>-  Capa Web
Se encuentra en el servidor web y contiene la lógica de presentación que se utiliza para generar una respuesta al cliente

>- Capa Negocio
Se encuentra en el servidor de aplicaciones y contiene el núcleo de la lógica del negocio de la aplicación. Provee las interfaces necesarias para utilizar el servicio de componentes del negocio. Las componentes del negocio interactúan con la capa de datos y son típicamente implementadas como componentes EJB. 

>-  Capa Datos
Esta capa es responsable del sistema de información de la empresa o Enterprise Information System (EIS) que incluye bases de datos, sistema de procesamiento datos, sistemas legados3.2 y sistemas de planificación de recursos. Esta capa es el punto donde las aplicaciones J2EE se integran con otros sistemas no JavaEE o con sistemas legados. 

> ### 10 Explique que son los contenedores, componentes, y servicios de JAVA EE
 Un contenedor es un entorno de ejecucion que provee al componente una serie de servicios. Java EE define tipos de contenedores los cuales son:

>-  Contenedor web
>-  Contenedor de negocio (o de EJBs)
zUn componente es una unidad de software que forma parte de una aplicación Java EE define los siguientes tipos de componentes:

>-  Componente cliente: Cliente AWT, Swing, Applet y navegador Web
>-  Componente web: Servlet, JSP y JSF
>-  Componente de negocio: EJB

>Cada tipo cubre necesidades concretas y se basan en APIs especificas. Son los servicios que deben ofrecer los contenedores Java EE. Java EE define los siguientes servicios:

>-  De directorio: para la indexación y búsqueda de componentes y recursos
>-  De despliegue: para poder personalizar los componentes y recursos

>   - De transaccionalidad: para poder ejecutar distintas acciones en una misma unidad transaccional
>   - De seguridad: para poder autenticar y autorizar a los usuarios de la aplicación
>   - De acceso a datos: para facilitar el acceso a Bases de Datos
>   - De conectividad: para poder acceder fácilmente a distintos EIS
>   - De mensajería: para poder comunicarse con otros componentes, aplicaciones o EIS


> ### 11 Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo. 

#### public abstract class HttpServlet extends GenericServlet: 
##### Es la clase de la cual se debe extender para crear un servlet HTTP.
##### De la clase que extiende obtiene los métodos ya definidos además de los cuales define:
* doGet(HttpServletRequest req, HttpServletResponse resp): Es el método llamado para procesar información que haya sido enviado con el método GET. Este método es llamado concurrentemente para cada cliente por lo que hay que estar atento por posibles variables compartidas que causen problemas.
* doPost(HttpServletRequest req, HttpServletResponse resp): Ídem al anterior pero para el método POST, en general se implementa sólo un método y el otro lo referencia.



