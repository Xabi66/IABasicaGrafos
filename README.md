# Descrición
 
Nueva zona para el tanque.

# Título principal
## Subtítulo

Lista de cammbios:

- Añadida conexión directa entre los waypoints 8 y 2 para poder pasar directamente de Rock a Ruin.
- Añadida nueva escena House con un edificio, un waypoint 9, 3 conexiones con los waypoints 1, 2 y 7 y un boton para ir a la escena.

[Ligazón](https://exemplo.com)


```csharp
// Ir á house (waypoint 8)
public void GotoHouse() {
    graph.AStar(currentNode, waypoints[8]);
    currentWP = 0;
}

```