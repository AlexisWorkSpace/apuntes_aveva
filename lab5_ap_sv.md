# Laboratorio 5
## Configuracion de la informacion de simulacion 

### Procedimiento

1. en el **OCMC** ir a **Operations integration server manager/TrainingGalaxy/ProdPlatform/OI.SIM.1/Configuration/Port/PLC**
2. Ir a la solapa **Device Groups** 
3. Ir a **Templates** en el IDE y crear una nueva instancia del **$gOPCClient**
4. Nombrar dicha instancia como **Simulator**
5. Doble click en **Simulator** para abrir su configurador
6. En **General** configurar:
   1. Server name: OI.SIM.1
   2. Server node: {nombre del prod}
7. En **Scan Group** en **Available scan groups** apretar el **+**
8. Nombrar al nuevo grupo **Fast**
9. Cambiar el **Update interveal** a 300
10. Con lo previamente mencionado crear lo siguiente:
    
    | Name   | Update interveal |
    | ------ | ---------------- |
    | Normal | 1000             |
    | Slow   | 10000            |

11. Guardar y salir
12. En **Model**, asignar **Simulator** a **ControlSystem**
13. En **Deployment** asignar **Simulator** a **ProdPlatform/AppEngine1**
14. Hacer **Deploy** en **Simulator**
15. En el _OCMC_ verificar que **OI.SIM.1** tenga un chech verde

### Ver atributos en ejecucion

16. En el IDE, vista **Deployment**, click derecho a **Simulator** e ir al **View in object viewer**
17. En el **Watch window** de abajo, agregar una solapa y llamarla **Simulator**
18. Agregar las siguientes columnas:
    - ConnectionStatus
    - ScanState
    - ScanStateCmd
19. Agregar el **ScanGroupList** al **Watch window**
20. En el cuadro de dialogo poner -1
21. en el campo **Attribute reference**, arriba a la izquierda poner **Simulator.Fast.$Sys$Status** (entre sys van dos signos $)
22. Guardar y minimizar
