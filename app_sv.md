# Anotaciones para el curso de application server

## Componentes del Application server

- **Bootstrap**: Bootstrap es un servicio de Windows que proporciona el software necesario para que una computadora pueda recibir una plataforma (un componente de su aplicación que hace que la computadora sea parte de su aplicación)
- **IDE**: El IDE (Entorno de Desarrollo Integrado) es el servidor de desarrollo de aplicaciones, herramienta para crear, configurar e implementar su aplicación
- **Repositorio de galaxias**: El Galaxy Repository es un servicio de Windows que gestiona el desarrollo e implementación de la aplicación; la computadora que ejecuta el software Galaxy Repository aloja la base de datos del proyecto de configuración

## Galaxia y repositorio de galaxias: 

Una galaxia es la aplicación completa. Es la base de datos del proyecto y la información de configuración, así como como el espacio de nombre lógico único de su aplicación implementada (entorno de ejecución). Es compuesto por:

- Una coleccion de objetos que representa todas las entidades fisicas y logicas de la aplicacion; desde **computadoras** y **runtimes** a todo el equipamiento en el campo
- La base de datos del proyecto donde se aloja toda la configuracion del proyecto
- Una o mas computadoras en red ejecutando la aplicacion
- Un conjunto común de políticas a nivel de sistema que cumplen todos los componentes y objetos, como configuraciones de seguridad, alarmas y comunicaciones

## Como crear y conectar una galaxia

El **IDE** de system platform es utilizado para crear, configurar y administrar las galaxias. El **IDE** no puede iniciar en una _Galaxia de estado neutral_, entonces al iniciar el **IDE**, se solicitara que se conecte a una galaxia existente o cree una nueva.


