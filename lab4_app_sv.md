# Laboratorio 
## sando el visor de objetos

### Procedimientos

1. En el cuadro **Deployment**, click derecho en **ProdPlatform** y seleccionar **View in Object Viewer**
   - Aqui veremos como emerge una nueva ventana llamada **Object Viewer**
2. Ver en la columna **Atributte Name** para filtrar los elementos deseados
3. Verificar que en el arbol de objetos este seleccionado el arbol **ProdPlatform**, luego buscar **PlatformInfo** y hacerle click derecho, luego seleccionar **Add to Watch**
    - El anterior atributo se agrega al **Watch window**, ventana que se ve abajo
4. En el arbol de procesos, click en **GRPlatform** y en el panel de detalles, arrastrar **PlatformInfo** hacia el **Watch window**
5. En el **Watch window**, expandir la pestaña **Value** para ver la descripcion completa de los atributos
6. Agregar el atributo **GR.TimeOfLastDeploy** al **Watch window**

### Renombrar el Watch Window

7. Click derecho en un espacio vacio del **Watch window** y seleccionar **Rename Tab**
8. Renombrarlo como **Platforms**
   - **NOTA**: veremos como en la solapa inferior cambia el nombre al especificado

### Guardar el watch list

9. En el menu **File**, seleccionar **Save Watch List As**
10. Navegar hacia **C:\Training** y guardar el archivo como **My Watch Window.xml**
11. Guardar el archivo
12. Cerrar el visor de objetos

### Usar el OCMC Platform Manager para abrir el visor de objetos 

14. Abrir el Operations control management consol _(OCMC)_
15. En el panel izquierdo del OCMC, clickear en **Platform Manager**
    - Aqui se mostrara la galaxia antes creada en el _IDE_
16. Expandir la pestaña **PLatform Manager** y seleccionar la galaxia
17. En el panel derecho, click derecho en **ProdPlatform** y seleccionar **Launch Object Viewer**

### Cargar Watch list previamente guardada

18. Desde el desplegable  **File** darle a **Load Watch list**, antes, clickear en la pestaña de abajo
19. Cargar el archivo guardado en el paso **10**

### Agregar una nueva pestaña de visualizacion

20. en el **Object viewer**, en la ventana de visualizacion de abajo, click dereccho en un espacio vacio y darle a **Add Watch Window**
21. En el panel de la izquierda, click en **AppEngine1**, luego, en el panel de detalles, arrastrar los siguientes atributos al nuevo panel de visualizacion:
    - ScanState
    - ScanStateCmd
    - Scheduler.ScanPeriod
22. Renombrar la nueva pestaña como **AppEngine**
23. Guardar esta lista