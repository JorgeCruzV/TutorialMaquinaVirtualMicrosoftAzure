#TUTORIAL DE MICRISOFT AZURE, PARA GENERACIÓN DE MÁQUINAS VIRTUALES
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
 
A.	TIPOS DE MÁQUINAS QUE OFRECE MICROSOFT AZURE:
SERIE A	Máquinas virtuales básicas a precios económicos para desarrollo y pruebas.
	Las VM de la serie A tienen las configuraciones de memoria y rendimiento de CPU adecuadas para cargas de trabajo de nivel de entrada como desarrollo y pruebas. Son económicas y proporcionan una opción de bajo costo para empezar con Azure. Av2 estándar es la última generación de máquinas virtuales de la serie A, con un rendimiento de CPU similar, pero más RAM por vCPU, y un disco más rápido.
SERIE Bs	Máquinas virtuales ampliables y económicas.
	Las instancias de la serie Bs son máquinas virtuales económicas que ofrecen una opción de bajo costo para cargas de trabajo que, normalmente, se ejecutan con un uso base de CPU de bajo a moderado, pero que, a veces, necesitan repentinamente un uso de CPU mucho más alto cuando la demanda aumenta.
SERIE D	Proceso de uso general
	Las máquinas virtuales de la serie D cuentan con CPU rápidas y una configuración óptima de CPU en relación con la memoria, por lo que son adecuadas para la mayoría de las cargas de trabajo de producción.
	Las instancias de máquina virtual Dv3 proporcionan máquinas virtuales de uso general con Hyper-Threading y se basan en el procesador Intel XEON ® E5-2673 v4 (Broadwell) de 2,3 GHz. Pueden alcanzar 3.5 GHz con Intel Turbo Boost Technology 2.0.
SERIE DC	Protección de los datos en uso
	La serie DC es una nueva familia de máquinas virtuales que utiliza enclaves seguros para proteger la confidencialidad y la integridad de los datos y del código mientras se están procesando en Azure. Esto se suma a las funcionalidades de cifrado incorporadas que ya existen para proteger los datos en Azure mientras están en reposo y en tránsito.
SERIE E	Optimizadas para aplicaciones en memoria con tecnología Hyper-Threading
	Las máquinas virtuales de Azure de la serie E están optimizadas para aplicaciones que hacen un uso intensivo de la memoria, como SAP HANA. Estas máquinas virtuales están configuradas con una proporción de memoria por núcleo muy alta, por lo que son idóneas para servidores de bases de datos relacionales, con memorias caché de tamaño medio a grande y análisis en memoria. Las máquinas virtuales de la serie Ev3 tienen de 2 a 64 vCPU y de 16 a 432 GiB de memoria RAM, respectivamente.
SERIE F	Máquinas virtuales optimizadas para proceso.
	Las máquinas virtuales de la serie F cuentan con una proporción de CPU por memoria más alta. Están equipadas con una memoria RAM de 2 GB y 16 GB de unidad de estado sólido (SSD) local por núcleo de CPU y están optimizados para cargas de trabajo de proceso intensivo. La serie Fsv2 presenta 2 GiB de RAM y 8 GB de almacenamiento local temporal (SSD) por cada vCPU. La serie Fsv2 cuenta con hyperthreading y se basa en el procesador Intel Xeon® Platinum 8168 (SkyLake) de 2,7 GHz, que puede lograr velocidades de reloj de hasta 3,7 GHz con Intel Turbo Boost Technology 2.0.
	 Algunos casos de uso son, por ejemplo, el procesamiento por lotes, los servidores web, el análisis y los juegos.
SERIE G	Máquinas virtuales optimizadas para memoria y almacenamiento. 
	Las máquinas virtuales de la serie G cuentan con la familia de procesadores Intel® Xeon® E5 v3, dos veces más de memoria y cuatro veces más de almacenamiento en unidades de estado sólido (SSD) que la serie D de uso general. 
	La serie G presenta hasta ½ TB de memoria RAM y 32 núcleos de CPU, y proporciona un rendimiento de proceso sin parangón, memoria y almacenamiento SSD local para las aplicaciones más exigentes.
SERIE H	Máquinas virtuales de informática de alto rendimiento.
	Las máquinas virtuales de la serie HB están optimizadas para aplicaciones HPC basadas en el ancho de banda de memoria, como la dinámica de fluidos, el análisis explícito de elementos finitos y la elaboración de modelos climáticos. Las máquinas virtuales de la serie HB cuentan con 60 núcleos de procesador AMD EPYC 7551, 4 GB de memoria RAM por núcleo de CPU, sin Hyper-Threading y un máximo de 4 discos administrados. La plataforma AMD EPYC proporciona un ancho de banda de memoria de más de 260 GB/s.
SERIE Ls	Máquinas virtuales optimizadas para almacenamiento
	Las máquinas virtuales de la serie Ls están optimizadas para almacenamiento. Estas máquinas son ideales para aplicaciones que requieren baja latencia, alto rendimiento y almacenamiento de disco local de gran tamaño. Se basan en la tecnología del procesador Intel Haswell, en concreto, los procesadores E5 Xeon v3 con tamaños de máquina virtual de 4, 8, 16 y 32 núcleos. Las máquinas virtuales de la serie Ls admiten un disco SSD local de hasta 6 TB y ofrecen un rendimiento inigualable de las operaciones de E/S de almacenamiento.
SERIE M	Máquinas virtuales optimizadas para memoria
	La familia de máquinas virtuales de Azure de la serie M está optimizada para memoria y son ideales para grandes cargas de trabajo en memoria, como SAP HANA. La serie M ofrece hasta 4 TB de RAM en una sola máquina virtual. Además, estas máquinas virtuales ofrecen numerosas CPU virtuales con hasta 128 vCPU en una sola máquina virtual, lo que permite un procesamiento paralelo de alto rendimiento.
SERIE Mv2	Máquinas virtuales optimizadas para memoria más grandes
	Las máquinas virtuales de la serie Mv2 de Azure cuentan con la función hyperthreading y con procesadores Intel® Xeon® Platinum 8180M a 2,5 GHz (Skylake), que ofrecen hasta 416 vCPU en una sola máquina virtual y configuraciones de 3 TB, 6 TB y 12 TB de memoria. Esta es, con mucho, la máquina virtual de memoria más grande que se ofrece en Azure y proporciona un rendimiento de proceso sin parangón para admitir bases de datos en memoria de gran tamaño.
SERIE N	Máquinas virtuales con GPU
	La serie N es una familia de Azure Virtual Machines con funcionalidad de GPU. Las GPU son perfectas para cargas de trabajo que utilizan una gran cantidad de proceso y gráficos, y ayudan a los clientes a impulsar la innovación con características como visualización remota de alto nivel, aprendizaje exhaustivo y análisis predictivo.

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



