# Descrición
 
Escena de un área desértica con un tanque que e mueve hacia diversos objetivos segun el botón pulsado.

# Título principal

**Nueva zona para el tanque.**

## Subtítulo

Lista de cammbios:

- Añadida conexión directa entre los waypoints 8 y 2 para poder pasar directamente de Rock a Ruin.
- Añadida nueva escena House con un edificio, un waypoint 9, 3 conexiones con los waypoints 1, 2 y 7 y un boton para ir a la escena.
- Añadido metodo GotoHouse en TanksWaypointsFollow.cs.

[Ligazón](https://github.com/Xabi66/IABasicaGrafos/blob/master/Assets/Scripts/TanksWaypoints/TanksWaypointsFollow.cs)


```csharp
// Ir á house (waypoint 8)
public void GotoHouse() {
    graph.AStar(currentNode, waypoints[8]);
    currentWP = 0;
}

```