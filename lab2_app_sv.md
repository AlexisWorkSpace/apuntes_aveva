# Laboratorio 2
## Crear plantillas derivadas globales

### Procedimiento:

1. Hacer _click derecho_ en **TrainigGalaxy** y seleccionar **New Template Toolset**
2. Renombrar el _New Toolset_, en este caso **Training**
3. Realizar el mismo procedimiento en **Training** y llamar al _New toolset_ global
4. Repetir en **Training** y generar un toolset llamado **Project**
5. Expandir la pestaña **Device integration** 
6. Click derecho en **$DDESuiteLinkClient**, desplegar _New_ y seleccionar **Derived Template**
7. Renombrar el nuevo archivo como **$gDDESuiteLinkClient**
8. Crear 3 plantillas mas derivadas desde: 

    | Plantilla base     | PLantilla derivada  |
    | ------------------ | ------------------- |
    | $InTouchProxy      | $gInTouchProxy      |
    | $OPCClient         | $gOPCClient         |
    | $RedundantDIObject | $gRedundantDIObject |

9. Seleccionar y arrastrar las nuevas plantillas derivadas hacia la carpeta **Global** previamente creada
10. Expandir la plantilla **System**
11. Crear plantillas derivadas de los siguientes items: 

    | Plantilla base    | Plantilla derivada   |
    | ----------------- | -------------------- |
    | $AppEngine        | $gAppEngine          |
    | $Area             | $gArea               |
    | $ViewEngine       | $gViewEngine         |
    | $WinPlatform      | $gWinPlatform        |

12. Seleccionar las nuevas plantillas derivadas y tambien las plantillas **$InTouchViewApp** y **$ViewApp** y moverlas hacia global
13. Click derecho en **Device integration** y seleccionar **Hide**
14. Aplicar el paso anterior en **System**
15. Click en el menu **Galaxy**
16. En el menu izquierdo, seleccionar **Configure**
17. Expandir **integrated development environment** y seleccionar **Toolset**
18. En el listado _Toolset_ seleccionar los toolsets que se desea ver, luego, apretar la flecha hacia atras.


