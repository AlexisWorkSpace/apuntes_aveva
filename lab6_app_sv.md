# Laboratorio 6
## Metricas de modelado

### Procedimiento:

1. En el IDE, en el desplegable **Application**, click derecho en **$UserDefined** y hacer **New/Derived Template**
2. Nombrarla **$Meter**
3. Moverla hacia **Training/Project**
4. Doble click en **$Meter**
5. Clickear la varita magica de configuraciones
6. Apretar el **+** para agregar un nuevo atributo
7. Configurar de la siguiente forma:
   1. **Name**: PV
   2. **Data type**: Float
   3. **Writeability**: object writeable
8. Clickear el boton **I/O**
9. En el area de **I/O** seleccionar **Read**
10. Guardar y salir del editor de configuracion
11. Hacer **Check in** en **$Meter**

### Crear Templates e instancias adicionales

12. Crear dos templates derivadas de **$Meter** llamadas **$Level** y **$Temperature** respectivamente
13. En base a **$Level** generar una nueva instancia llamada **L1**
14. Ubicar **L1** dentro de **Production**
15. en base a **$Temperature** generar una nueva instancia llamada **T1**
16. Ubicar **T1** dentro de **Production**
17. Moverse hacia el menu **View** y hacer click en **I/O devices**
18. En el mimo menu **View** hacer click en **Mapping**
19. En  **I/O devices** expandir **TrainingGalaxy/Simulator/Fast**
20. En **Production** realizar un **Deploy** en **T1** y **L1**

### Ver la metrica de datos en ejecucion

21. Abrir el **View in object viewer** en **L1**
22. Clickear en **L1** y en la pestaña **Simulator** enviar los siguientes atributos:
    - PV
    - PV.InputSource
23. Repetir pasos de **L1** para **T1** con los mismos atributos
24. Guardar **Watch window** y minimizar