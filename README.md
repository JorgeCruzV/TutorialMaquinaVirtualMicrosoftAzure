#TUTORIAL DE MICRISOFT AZURE, PARA GENERACIÓN DE MÁQUINAS VIRTUALES

![alt text](https://github.com/JorgeCruzV/TutorialMaquinaVirtualMicrosoftAzure/blob/master/Imagenes/1.png)


1.	OBJETIVOS:

a.	Objetivo principal:

	i.	Comprender el proceso de creación de una máquina virtual, mediante el uso de Microsoft Azure.
	
b.	Objetivos secundarios:

	i.	Analizar las herramientas y características que nos brinda Microsoft Azure para generar máquinas virtuales.
	
	ii.	Observar las aplicaciones que podrían llegar a tener nuestra máquina virtual, analizando sus ventajas.

2.	MARCO TEÓRICO:

En informática, una máquina virtual es un software que simula un sistema de computación y puede ejecutar programas como si fuese una computadora real. Este software en un principio fue definido como "un duplicado eficiente y aislado de una máquina física". La acepción del término actualmente incluye a máquinas virtuales que no tienen ninguna equivalencia directa con ningún hardware real.

Una característica esencial de las máquinas virtuales es que los procesos que ejecutan están limitados por los recursos y abstracciones proporcionados por ellas. Estos procesos no pueden escaparse de esta "computadora virtual".
Uno de los usos domésticos más extendidos de las máquinas virtuales es ejecutar sistemas operativos para "probarlos". De esta forma podemos ejecutar un sistema operativo que queramos probar (GNU/Linux, por ejemplo) desde nuestro sistema operativo habitual (Mac OS X por ejemplo) sin necesidad de instalarlo directamente en nuestra computadora y sin miedo a que se des configuré el sistema operativo primario.


Migre sus cargas de trabajo empresariales y críticas a Azure. Ejecute el software SQL Server, SAP y Oracle® y las aplicaciones de informática de alto rendimiento en Azure Virtual Machines. Elija su distribución de Linux favorita o Windows Server.
Implemente máquinas virtuales que tengan hasta 416 vCPU y 12 TB de memoria. Consiga hasta 3,7 millones de operaciones IOPS por máquina virtual en almacenamiento local. Aproveche Ethernet de hasta 30 Gbps y la primera implementación de la nube de InfiniBand a 200 Gbps.
 


A. TIPOS DE MÁQUINAS QUE OFRECE MICROSOFT AZURE 




3.- DETALLES DE LICENCIA OBTENIDA:

 
a)	Se adquirió la licencia gratuita, la cual nos ofrece los siguientes beneficios: 

	i.	12 meses de servicio gratuito. 
	ii.	Crédito de 170 Euros o 200 Dólares para probar durante 30 días.  
	iii.	Más de 25 servicios gratuitos para siempre. 
	
4.- TUTORIAL DE REGISTRO EN MICROSOFT AZURE:


1)	Se procederá a ingresar a la página oficial de Microsoft Azure, donde también se puede obtener mayor información respecto a los servicios que este ofrece Microsoft Azure. Una vez dentro de la página, buscaremos una pestaña “Cuenta Gratuita”. Luego se deberá dar en empezar gratis para iniciar el registro.

a.	Link: https://azure.microsoft.com/es-es/free/ 
 
 
 
 
2)	Como siguiente paso será necesario ingresar a nuestra cuenta de Microsoft, la cual se realiza a partir de una cuenta en Hotmail.
 
 
 
 
3)	Aquí se debe llenar con información personal, solicitada por la página.
 
 
 
 
4)	Luego se realiza el proceso de verificación de identidad, esto se realiza mediante dos métodos. Uno usando un mensaje o llamada para confirmar un código de confirmación y el otro método obligatorio es la verificación a partir de una tarjeta de crédito 
 
 
 
 
 
5)	Finalmente se acepta un Acuerdo, en el cual está incluido el contrato con el cliente y el contrato de privacidad. 
 
 
 
 
5.- TUTORIAL DE CREACIÓN DE LA MÁQUINA VIRTUAL:

1)	Estando en la pantalla principal de Microsoft Azure, procedemos a “Crear un recurso nuevo”.
a.	Link: https://portal.azure.com/#home 
 
 
 
2)	Aquí podemos observar todos los servicios de Microsoft Azure, como también se observan los más populares. 
 
3)	En este caso se creará una máquina virtual Usando Windows Server 2016 Datacenter como sistema operativo, existen otras opciones como Ubuntu.

4)	Una vez elegido el sistema operativo a usar, se mostrará la siguiente ventana. Con la cual iniciaremos a determinar las características de nuestro computador virtual.  
 
Aquí encontraremos detalles principales como el nombre de la máquina virtual, región donde se desea poseer el servidor, como también se nos solicitara un nombre de usuario y una contraseña. Pero lo más importante en esta pestaña es al momento de elegir el “tamaño” ya que ahí se elige las características de hardware que tendrá nuestro equipo, se debe tener en cuenta, ya que de esto depende el costo mensual.
 
En nuestra máquina virtual se utilizarán las características del B2s, el cual cuenta con 4G de ram, 2 vCpu y 4 discos datos. 
Aquí también podremos escoger los puertos de ingreso que deseamos, entre estos puertos están: Http, Https SSH, RDP. 
 
5)	A continuación, vamos a encontrar una pestaña en la cual se puede modificar las características del disco, ya que estas máquinas virtuales cuentan con dos discos, uno de sistema operativo y otro de un disco temporal para el almacenamiento a corto plazo. 
 
6)	La siguiente pestaña consiste en la configuración de las redes de nuestra máquina virtual. Se puede controlar los puertos y la conectividad entrante y saliente con reglas de grupos de seguridad o bien aplicar una solución de equilibrio de carga ya existente. 
 
7)	A continuación, observamos la pestaña de administración, donde se proporciona las características unificadas de administración de la seguridad y protección contra amenazas en todas las cargas de trabajo de nube híbrida. 
 
8)	También encontraremos opciones avanzadas y etiquetas entre las pestañas de nuestra configuración, en la primera se podrá agregar configuración, agentes, scripts o aplicaciones adicionales y en la segunda pestaña. Mientras que las etiquetas se definen como “Las etiquetas son pares nombre-valor que permiten categorizar los recursos y ver una facturación consolidada mediante la aplicación de la misma etiqueta en varios recursos y grupos de recurso”
 
 
9)	Finalmente se visualiza la pestaña de Revisar y crear, donde vamos a encontrar los detalles elegidos previamente como también se encuentra el precio por hora que se facturará. 
 
  
10)	Finalmente, observamos un botón “Crear”, con el cual nos va a generar nuestra máquina virtual. Esto podría demorar un tiempo. 
 
6.- PROCESO PARA INICIAR E INGRESAR A NUESTRA MÁQUINA VIRTUAL MEDIANTE CONTROL REMOTO:
a)	Una vez creado la máquina virtual, accedemos en la pantalla principal a “Máquinas Virtuales”, donde encontraremos todas las maquinas creadas con anterioridad. 
 
b)	Accedemos a nuestra máquina, una vez ahí vamos a observar todas las características y datos recolectados de la máquina. 
 
 
c)	Para iniciar la conexión mediante control remoto, se debe acceder a la pestaña “Conectar”, en la cual elegiremos el protocolo “RDP”
 
d)	Procedemos a descargar el archivo RDP e iniciamos la sesión. 
 
e)	Finalmente ingresamos a nuestra máquina virtual. 
 
7.- CONCLUSIONES:
A.	Tras una prueba rápida se pudo evidenciar que este tipo de herramientas en línea pueden llegar a ser altamente útiles, por la variedad de equipos como también es increíble su velocidad de conexión con internet. A continuación, se mostrarán unos pocos programas funcionado en nuestra computadora virtual.
 
 
 
 
8.- BLIBLIOGRAFÍA
Microsoft Azure. (2020).Azure. Recuperado de: https://azure.microsoft.com/es-es/overview/  
TicPortal&European Knowledge Center for Information Technology. (2020).Cloud Computing. Recuperado de: https://www.ticportal.es/temas/cloud-computing 



