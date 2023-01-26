# Curso_de_Introduccion_a_AWS_Fundamentos_de_Cloud_Computing

**Curso de Introduccion a AWS Fundamentos de Cloud Computing**

<h2>Content List</h2>

- [Cómo Aprender AWS](#cómo-aprender-aws)
- [Visión General de las TI Tradicionales](#visión-general-de-las-ti-tradicionales)


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
