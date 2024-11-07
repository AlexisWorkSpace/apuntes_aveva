# Laboratorio 3
## Creando la planta y los modelos de despliegue

### Procedimiento: 

1. Verificar que el cuadro inferior izquierdo llamado _model_ en el IDE este seleccionado
2. En caso de no estar seleccionado, seleccionar el cuadro _model_ y seleccionar la solapa _Model - Tagname_
3. En el cuadro _Templates/Training/Global_, hacer click derecho en **$gArea** y seleccionar **New/Instance**
    - Notese que se genera un nuevo archivo llamado **gArea_001** en el cuadro _Model_
4. Renombrar esta instancia como **Receiving**
5. Arrastrar el _Template_ **$gArea** hacia el cuadro _Model_ y renombrarlo como **Plant**
6. arrastrar el _Template_ **$gArea** hacia el cuadro _Model_ 6 veces mas renombrando cada instancia de las siguientes formas: 
    - ControlSystem
    - Production
    - Line1
    - Line2
    - Packaging
    - Shipping 
7. En el cuadro _Model_, arrastrar **Line1** dentro de Production, de esta forma se asignara **Line1** al objeto **Production**
8. Click derecho en **Line2** y seleccionar **Assing to**, aparecera un cuadro de dialogo
9. En el listado desplegable seleccionar **Production**
10. Click en **Assign**
11. Realizar los pasos anteriores para asignar al objeto **Plant** los objetos:
    - ControlSystem
    - Packaging
    - Production
    - Receiving
    - Shipping

Ahora pasaremos a la solapa de **Deploument**

12. Clickear la pestaña **Deployment** y expandir las carpetas **TrainingGalaxy** y **Unassigned Host**
13. En el cuadro **Templates/Training/Global**, click derecho en **$gWinPlatform** y seleccionar **New/Instance**
14. Renombrar la nueva instancia como **GRPlatform**
15. Crear una nueva instancia y renombrarla como **ProdPlatform**
    - **Nota**: luego de esto, la nueva instancia aparecera con un icono rojo, indicando que hay un error de configuracion
16. Doble click en la nueva instancia para abrir el editor de configuraciones
17. En la solapa **General**, configurar el campo **Network Adress** con el nombre de la computadora
18. Apretar el boton **guardar y salir**
19. En el cuadro de dialogo **Check-In** poner como comentario **Changed Network Address**
    - **Nota**: para este punto, el icono de error deberia haber desaparecido, en caso de que no, revisar los pasos
20. Click derecho en **$gAppEngine** y seleccionar **New/Instance**
21. Renombrar la instancia como **AppEngine1**
22. Arrastrar **AppEngine1** a **ProdPlatform**
23. Arrastrar todas las instancias desde **Unassigned Host** hacia **AppEngine1**
24. Volver a la solapa _Model - Tagname_ y expandir la carpeta **Unassigned Area**
    - Notese que en este lugar apareceran las 3 instancias previamente creadas
25. Enviar estas 3 instancias (**AppEngine1**, **GRPlatform** y **ProdPlatform**) hacia la carpeta **ControlSystem**

### Despliegue de la aplicacion.

26. Volver a la pestaña **Deployment** 
27. Click derecho en **GRPlatform** y seleccionar **Deploy**
28. Dejar las opciones por defecto y darle al boton **Deploy**
29. Cerrar la pestaña que aparece
30. Click derecho en **ProdPlatform** y seleccionar **Deploy**
31. Dejar las opciones por defecto y darle a **Deploy**
32. La pestaña **Deployment** ahora mostrara todos los elementos que hayan sido desplegados, cerrar la ventana emergente


# Ha aparecido un error de bootstrap - revisar como solucionarlo
