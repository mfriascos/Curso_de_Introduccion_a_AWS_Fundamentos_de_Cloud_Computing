# Curso_de_Introduccion_a_AWS_Fundamentos_de_Cloud_Computing

**Curso de Introduccion a AWS Fundamentos de Cloud Computing**

<h2>Content List</h2>

- [Cómo Aprender AWS](#cómo-aprender-aws)
- [Visión General de las TI Tradicionales](#visión-general-de-las-ti-tradicionales)
- [Los Diferentes Tipos de Cómputo: IaaS vs PaaS vs SaaS](#los-diferentes-tipos-de-cómputo-iaas-vs-paas-vs-saas)


## Cómo Aprender AWS

Amazon web services (AWS) es el proveedor de servicios en la nube más grande del mundo. Muchas aplicaciones como Netflix, Meta y Platzi operan su arquitectura web gracias a su plataforma. 

**¿Qué aprender?**

* Historia de AWS
* Regiones y zonas de disponibilidad en AWS 
* Cómo crear tu cuenta de AWS
* Roles, seguridad e identidad en AWS

## Visión General de las TI Tradicionales

Entendamos primero como funciona la web en términos simples. Tenemos un **cliente** con una dirección Ip que se conecta a una **red** para hacer una **petición** a un **servidor** con otra dirección IP. Este servidor devuelve una respuesta al cliente. 

Si la web fuera un servicio postal, el **cliente** seríamos nosotros con la **petición** o paquete que queremos enviar, la **red** sería el sevicio postal en sí y el **servidor** representaría al destinatario al que queremos enviar el paquete. 

<h3>Cómo está Compuesto un Servidor?</h3>

Un servidor posee los siguientes componenetes: 

* **Cómputo/CPU**: Realiza las operaciones que necesitamos
* **Memoria RAM** Contiene la información a procesar mediante la CPU. Es como un cerebro
* **Almacenamiento**: Archiva datos, a modo de archivos de texto plano. 
* **Bases de Datos**: Información almacenada de manera estructurada
* **Redes**: Cables, routers y servidoress conectados unos a otros. Servidores DNS

<h3>Terminología de IT (redes)</h3>

En términos generales, un cliente envía un paquete a un **router**, el cual reenvía este paquete al **swith**, y este se encarga de distribuirlo. 

* **Router**: Dispositivo que reenvía paquetes de datos entre redes informáticas 
* **Switch**: Dispositivo que toma paquetes y los envía al servidor/cliente correcto en la red. 

<h3>Diseño Tradicional de Infraestructura</h3>

Las grandes empresas de IT empezaron comprando servidores y montándolos en sus garajes. Se encontraron con problemas al tratar de expandir su infraestructura, como los costos de mover estos servidores, comprar nuevos, y más...

<h4>Problemas del enfoque de IT Tradicional</h4>

Algunas dificultades del enfoque de tecnología de la información habitual: 

* **Renta**: Los costos de rentar espacios para mantener servidores son altos
* **Mantenimiento**: El funcionamiento de los servidores es díficil de asegurar
* **Reemplazar y Agreagar Hardware**: Pueden existir largos tiempos de espera para conseguir el hardware necesario
* **Escalamiento Limitado**: Podemos vernos limitados por el espacio donde almacenamos los servidores
* **Monitoreo 24/7**: Debemos contratar gente para monitorear los servidores
* **Desastres Naturales**: ¿Cómo evitamos que se caigan nuestros servicios si ocurre un imprevisto? 

## Qué es la Computación en la Nube

La computación en la nube es la entrega bajo demanda de recursos de IT como computación, almacenamiento y otros servicios a través de internet. En pocas palabras, es como si alquiláramos la computadora de otra persona.

Esta tecnología permite acceso instantáneo a los recursos que necesites, así como la adquisición del tipo y tamaño exacto de estos recursos. Algunos servicios que seguramente has usado son Gmail (proveedor de email), Dropbox (proveedor de almacenamiento) y Netflix (proveedor de video bajo demanda).

<h3>Modelos de computación en la nube</h3>

A continuación, conocerás las distintas plataformas en la nube que utilizamos cuando trabajamos en proyectos personales o en nuestra empresa.

<h4>Nube pública</h4>

La nube pública se refiere a los recursos de proveedores que utilizamos a través de internet y algunos ejemplos son Google Cloud Platform (GCP), Azure y AWS.

Además, posee estas ventajas:

* Elimina los gastos de capital comercial (CapEx) y reduce el gasto operativo (OpEx).
* Reduce los precios en economías de escala
* Despliega aplicaciones a nivel global en cuestión de minutos

<h4>Nube privada</h4>

La nube privada es un servicio empleado por una organización que no está abierto al público. Permite un control total de la infraestructura y es útil para aplicaciones con requerimientos específicos de seguridad o comerciales.

<h4>Nube híbrida</h4>

La nube híbrida consiste en mantener nuestra infraestructura y extender sus capacidades mediante la nube pública. Posibilita el control sobre activos sensibles en tu infraestructura privada, aprovechando la flexibilidad y rentabilidad de la nube pública.

<h3>Características de la computación en la nube</h3>

Ahora que conoces los distintos modelos de tecnología en la nube, es importante que hablar sobre sus propiedades de computación.
* Autoservicio en demanda
* Amplio acceso a la red
* Multiples inquilino 
* Este modelo genera un autoservicio en demanda (con registros en la plataforma ya se pueden proveer recursos)
* Tiene un amplio acceso a la red
* Proporciona un espacio donde los clientes pueden compartir infraestructura y recursos de manera segura

<h3>Problemas resueltos por la nube</h3>

Por último, es crucial que conozcas las cualidades que trae implementar un sistema de computación en la nube.

* La nube aporta flexibilidad (puedes cambiar los tipos de recursos cuando sea necesario)
* Brinda rentabilidad y un servicio medido pues pagas solo por lo que usas
* Trae escalabilidad al agregar capacidad para hardware o equipos que necesitan acomodar cargas grandes
* Ofrece elasticidad al dar capacidad de escalar automáticamente cuando sea necesario
* Tiene alta disponibilidad y tolerancia a fallos
* Proporciona agilidad (puedes desarrollar, probar y ejecutar rápidamente aplicaciones en la nube)

## Los Diferentes Tipos de Cómputo: IaaS vs PaaS vs SaaS

* **IaaS:** Infraestructura como Servicio. Proporciona componentes básico para las tecnologías de información en la nube.
* **PaaS:** Plataforma como Servicio. Eliminar la necesidad de que nuestra rganización administre la infraestructura
* **SaaS:** Software como Servicio. Producto terminado que es administrado y ejecutado por el proveedor de servicio 

<h3>Ejemplos de los Tipos de Computación de la Nube</h3>

IaaS: Azure, Linode, Digital Ocean. 
PaaS: Google AppEngine. 
SaaS: Dropbox, Zoom, Gmail

