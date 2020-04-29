Usme y Ospino

En teoría, la complejidad de hacer DFS es  menor que hacer BFS.

Tiempo de ejecución de bfs 0.28125  segundos

Tiempo de ejecución de dfs 0.21875  segundos

Para la misma busqueda: ABQ-12-24 JFK-12-24

BFS: ABQ-12-24 ---> JFK-12-24
DFS:  ABQ-12-24--->ATL-12-24--->ABE-12-24--->ORD-12-24--->ALB-12-24--->BWI-12-24--->AUS-12-24--->BNA-12-24--->BOS-12-24--->BUF-12-24--->CLT-12-24--->BDL-12-24--->DCA-12-24--->CHS-12-24--->DAL-12-24--->AMA-12-24--->DFW-12-24--->AEX-12-24--->IAH-12-24--->ASE-12-24--->DEN-12-24--->ANC-12-24--->CDV-12-24--->YAK-12-24--->JNU-12-24--->KTN-12-24--->SEA-12-24--->BIL-12-24--->MSP-12-24--->ATW-12-24--->DTW-12-24--->BGR-12-24--->LGA-12-24--->CLE-12-24--->EWR-12-24--->BQN-12-24--->JFK-12-24


# Lab8_202010

Este repositorio contiene una plantilla del laboratorio 8 con un ejemplo de un ADT grafo que está implementado con listas de adyacencias. La aplicación está construida bajo el patrón Modelo-Vista-Controlador que carga datos y realiza consultas usando las estructuras de datos implementadas. Para iniciar la aplicación debe ejecutar: 
```
python App/view.py
```
*	ADT: archivos Python con la definición de los Tipos Abstractos de Datos.
*	App: aplicación Python cliente que usa las ADTs y ordenamientos para dar solución a laboratorios y retos.
    * view.py: Es el punto de entrada de la aplicación, y se encarga de la entrada y salida de datos, e interacción con el usuario
    * controller.py: Comunica la vista con el modelo a través de las operaciones invocadas por el usuario desde la vista
    * model.py: Representa el modelo del mundo.
*	Data: archivos con los datos (csv, json, txt, etc) usados en el laboratorio o reto. El contenido de esta carpeta NO se debe versionar.
*	DataStructures: archivos Python con las estructuras de datos básicas (adjlist, edge, y graphstructure).
*	Sorting: archivos Python que implementan los algoritmos de ordenamiento.
*	Test: pruebas unitarias en Python para validar el código desarrollado.

![Modelo-Vista-Controlador](http://sistemasproyectos.uniandes.edu.co/iniciativas/architlab/wp-content/uploads/sites/7/2020/02/MVC.png)
