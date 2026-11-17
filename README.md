# Proyecto Intermodular – ASIR

**Antonio Gonzalez Amores**  
**IES Triana**

---

# ÍNDICE

- Introducción
- 1. Título
- 2. Descripción
- 3. Justificación
- 4. Objetivos
- 5. Lenguajes de programación y tecnologías
- 6. Prototipo de interfaz de usuario
- 7. Gestor de bases de datos
- 8. Entornos de aplicación del proyecto
- 9. Fases de desarrollo
- 10. Módulos del ciclo formativo relacionados
- 11. Anexos y bibliografía

---

# Introducción

En este proyecto se desarrollará una infraestructura informática para una pequeña empresa, teniendo en cuenta las necesidades tecnológicas que puede tener para realizar su actividad diaria. Se trabajará con diferentes sistemas, redes, servidores y servicios informáticos, buscando una solución organizada y eficiente.

A lo largo del proyecto se abordarán aspectos como la configuración de la red, la administración de usuarios y permisos, la seguridad de los sistemas y las copias de seguridad. Todo ello permitirá aplicar los conocimientos adquiridos en el ciclo de ASIR y crear una infraestructura funcional, segura y adaptada a las necesidades de una pequeña empresa.

---

# 1. Título

Diseño e implementación de una infraestructura informática para una pequeña empresa.

# 2. Descripción

En este proyecto quiero diseñar e implementar una infraestructura informática para una pequeña empresa, teniendo en cuenta las necesidades que puede tener en su día a día. La idea es crear un entorno informático organizado, seguro y funcional que permita gestionar los equipos, los usuarios, la red y los diferentes servicios necesarios para trabajar correctamente.

Para llevarlo a cabo, trabajaré con sistemas operativos, servidores, redes y servicios de red, además de configurar usuarios y permisos, medidas de seguridad y copias de seguridad para proteger la información. También estudiaré la posibilidad de utilizar máquinas virtuales para facilitar la instalación y administración de los sistemas. El objetivo es conseguir una solución práctica y adaptada a una pequeña empresa, que sea fácil de mantener y que permita aprovechar los recursos informáticos de forma eficiente.

# 3. Justificación

He elegido este proyecto porque actualmente cualquier pequeña empresa necesita una infraestructura informática que funcione correctamente para poder realizar sus tareas diarias. Los ordenadores, los servidores, la red y los servicios informáticos son importantes para trabajar de forma organizada, compartir información y mantener los datos protegidos. Si estos elementos no están bien configurados, pueden aparecer problemas de conexión, pérdida de información o accesos no autorizados.

Existen diferentes soluciones para gestionar la infraestructura informática de una empresa, como utilizar servidores, redes locales, sistemas de virtualización y herramientas para realizar copias de seguridad. Con este proyecto quiero aplicar los conocimientos que he adquirido durante el ciclo de ASIR para crear una infraestructura adaptada a las necesidades de una pequeña empresa. Mi propuesta se centrará en organizar los equipos y usuarios, configurar los servicios necesarios y aplicar medidas de seguridad y copias de seguridad. De esta manera, podré desarrollar una solución práctica, segura y fácil de administrar, utilizando herramientas y tecnologías que se pueden encontrar en un entorno de trabajo real.

# 4. Objetivos

Los objetivos de este proyecto serán los siguientes:

1. Diseñar la infraestructura informática de una pequeña empresa, teniendo en cuenta sus necesidades y los recursos disponibles.
2. Configurar una red local que permita la comunicación entre los equipos y el acceso a los servicios de la empresa.
3. Instalar y configurar los sistemas operativos y servidores necesarios para el funcionamiento de la infraestructura.
4. Crear y administrar usuarios y grupos, estableciendo permisos para controlar el acceso a los recursos compartidos.
5. Configurar servicios de red que faciliten la conexión y la administración de los equipos.
6. Aplicar medidas de seguridad para proteger los sistemas y evitar accesos no autorizados.
7. Implementar un sistema de copias de seguridad que permita recuperar los datos en caso de pérdida o fallo.
8. Utilizar la virtualización, si resulta adecuada, para instalar y probar diferentes sistemas y servicios sin necesidad de disponer de muchos equipos físicos.
9. Realizar pruebas de funcionamiento para comprobar que la red, los servicios, los permisos y las copias de seguridad funcionan correctamente.
10. Documentar el proceso de instalación y configuración, explicando las decisiones tomadas y las comprobaciones realizadas.

# 5. Lenguajes de programación y tecnologías

Para realizar este proyecto utilizaré diferentes herramientas y tecnologías que me permitirán diseñar, configurar y administrar la infraestructura informática de una pequeña empresa.

- **VirtualBox:** lo utilizaré para crear máquinas virtuales y simular los equipos y servidores de la empresa.
- **Ubuntu Server:** lo utilizaré para instalar y configurar los servidores y los diferentes servicios de red.
- **Ubuntu Desktop:** lo utilizaré como sistema operativo de los equipos cliente para comprobar el acceso a la red y a los recursos compartidos.
- **DHCP:** permitirá asignar automáticamente direcciones IP a los equipos de la red.
- **DNS (BIND9):** permitirá resolver los nombres de los equipos y servidores de la empresa.
- **Samba:** lo utilizaré para compartir carpetas y archivos entre los equipos, estableciendo los permisos de acceso.
- **MySQL:** lo utilizaré para crear y administrar una base de datos donde se registrarán las incidencias técnicas de la empresa, indicando su descripción y estado.
- **Bash y scripts:** los utilizaré para ejecutar comandos y automatizar algunas tareas de administración.
- **SSH:** permitirá administrar los servidores de forma remota desde otros equipos de la red.
- **rsync:** lo utilizaré para realizar copias de seguridad de los archivos importantes.
- **Herramientas de red:** utilizaré comandos como `ping`, `ip a` y `nslookup` para comprobar la conectividad, revisar la configuración de red y verificar la resolución de nombres.

Estas herramientas me permitirán poner en práctica los conocimientos adquiridos durante el ciclo de ASIR y desarrollar una infraestructura informática funcional, segura y fácil de mantener.

# 6. Prototipo de interfaz de usuario

La infraestructura informática contará con diferentes formas de administración y acceso según las necesidades de la empresa. Los usuarios podrán trabajar desde sus equipos y acceder a los recursos compartidos, mientras que el administrador se encargará de configurar y mantener los sistemas.

Para gestionar la infraestructura utilizaré VirtualBox para controlar las máquinas virtuales y Ubuntu Server para administrar los servidores mediante la terminal. Además, los equipos cliente permitirán comprobar el acceso a los servicios y a las carpetas compartidas.

Aunque no se desarrollará una aplicación gráfica propia, se mostrarán capturas de pantalla de las configuraciones y pruebas realizadas para representar el funcionamiento de la infraestructura.

# 7. Gestor de bases de datos

Para este proyecto utilizaré MySQL como gestor de bases de datos, ya que permite almacenar y organizar información relacionada con el funcionamiento de la infraestructura informática de la empresa.

La base de datos estará orientada a la gestión de incidencias técnicas, permitiendo registrar los problemas que aparezcan en los equipos y llevar un seguimiento de su resolución.

## Modelo entidad-relación

# 8. Entornos de aplicación del proyecto

El proyecto estará pensado para una pequeña empresa que necesita una infraestructura informática para gestionar sus equipos, usuarios, servicios de red e incidencias técnicas.

Para desarrollar el proyecto utilizaré un entorno virtualizado con VirtualBox, donde instalaré máquinas virtuales con Ubuntu Server y Ubuntu Desktop. De esta forma, podré configurar los servidores y los equipos cliente y comprobar que funcionan correctamente.

La infraestructura contará con los siguientes elementos:

- **Hardware:** un ordenador físico que servirá como equipo principal para ejecutar las máquinas virtuales.
- **Sistemas operativos:** Ubuntu Server para los servidores y Ubuntu Desktop para los equipos cliente.
- **Red:** una red local que permitirá la comunicación entre los equipos y el acceso a los servicios configurados.
- **Servicios de red:** DHCP para asignar direcciones IP, DNS para resolver nombres y Samba para compartir archivos.
- **Base de datos:** MySQL para almacenar y gestionar las incidencias técnicas de la empresa.
- **Administración y seguridad:** gestión de usuarios, permisos, acceso remoto mediante SSH y copias de seguridad.

Este entorno permitirá simular una infraestructura informática real y realizar pruebas de funcionamiento sin necesidad de disponer de varios equipos físicos.

# 9. Fases de desarrollo

El proyecto se organizará en seis fases para facilitar el trabajo y comprobar que la infraestructura informática funciona correctamente.

## 1. Planificación

-Todas las tareas las he definido en la plataforma de **JIRA** para su organización, justo debajo teneis un enlace para acceder a ella.
-Para acceder a la planificación en Jira pulsa [aqui](https://www.ejemplo.com)

## 2. Análisis y diseño

Diseñaré la red informática, distribuiré los equipos y servidores y seleccionaré los servicios necesarios.

## 3. Implementación

Instalaré las máquinas virtuales y los sistemas operativos. Después, configuraré los servicios de red, los usuarios y permisos, las carpetas compartidas y la base de datos MySQL para gestionar las incidencias.

## 4. Pruebas

Comprobaré la conectividad entre los equipos, el funcionamiento de los servicios, los permisos de acceso, el registro de incidencias y las copias de seguridad.

## 5. Puesta en funcionamiento

Verificaré que todos los elementos estén correctamente configurados y que la infraestructura esté preparada para utilizarse.

## 6. Mantenimiento

Realizaré actualizaciones, revisaré los servicios y comprobaré las copias de seguridad para mantener la infraestructura en buen estado.

# 10. Módulos del ciclo formativo relacionados

Este proyecto está relacionado con varios módulos del ciclo de ASIR, ya que permite aplicar los conocimientos adquiridos durante el curso en un entorno informático similar al de una pequeña empresa.

1. **Implantación de Sistemas Operativos:** instalación y configuración de Ubuntu Server y Ubuntu Desktop, así como la administración de usuarios y permisos.
2. **Planificación y Administración de Redes:** configuración de la red local, las direcciones IP y la comunicación entre los equipos.
3. **Fundamentos de Hardware:** conocimiento de los recursos de los equipos y asignación de recursos a las máquinas virtuales.
4. **Gestión de Bases de Datos:** instalación y utilización de MySQL para almacenar y gestionar las incidencias técnicas de la empresa.
5. **Administración de Sistemas Operativos:** administración de servidores, gestión de usuarios, permisos y tareas de mantenimiento.
6. **Servicios de Red e Internet:** configuración de servicios como DHCP, DNS, Samba y SSH.
7. **Implantación de Aplicaciones Web:** relación con la posible utilización de una interfaz web para consultar o gestionar las incidencias, si finalmente se incorpora al proyecto.
8. **Seguridad y Alta Disponibilidad:** aplicación de medidas de seguridad, control de accesos y realización de copias de seguridad para proteger la información.

Estos módulos están relacionados con el proyecto porque aportan los conocimientos necesarios para diseñar, configurar y mantener una infraestructura informática segura y funcional para una pequeña empresa.

# 11. Anexos y bibliografía

En este apartado incluiré documentación complementaria y las fuentes de información que utilizaré para desarrollar el proyecto.

## Anexos

Se incluirán los siguientes elementos para mostrar el trabajo realizado:

- Capturas de pantalla de la instalación y configuración de las máquinas virtuales.
- Capturas de la configuración de la red y de los servicios instalados.
- Pruebas de conectividad entre los equipos.
- Capturas de la configuración de MySQL y del registro de incidencias.
- Evidencias de la configuración de usuarios, permisos y copias de seguridad.

## Bibliografía

Para realizar el proyecto consultaré la documentación oficial de las herramientas utilizadas y otros recursos técnicos que me ayuden a resolver posibles problemas.

- Ubuntu: [https://ubuntu.com/server/docs?utm_source=chatgpt.com]
- VirtualBox: [https://www.virtualbox.org/manual/?utm_source=chatgpt.com]
- MySQL: [https://dev.mysql.com/doc/?utm_source=chatgpt.com]
- Samba: [https://www.samba.org/?utm_source=chatgpt.com]
- BIND9: [https://bind9.readthedocs.io/?utm_source=chatgpt.com]

Estas fuentes me servirán para consultar información sobre la instalación, configuración y administración de los sistemas y servicios utilizados durante el desarrollo del proyecto.
