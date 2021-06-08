# UnityIAProyecto
 Proyecto de IA con unity usando NAV MESH
 Para ejecutar el proyecto se debe realizar las siguientes acciones:
 
1.	Es necesario tener instalado Unity en su versión 2020.3.1f1 o superior

2.	Descargar el proyecto como archivo zip en la carpeta que se desea o clonarlo.

3.	Abrir Unity Hub y dar clic en agregar, para añadir el directorio donde se descargó el proyecto.

4.	Seleccionar el proyecto y hacer dos veces clic para poder abrirlo.

5.	Una vez finalizado el cargado del proyecto, dar clic en ‘play’ para ejecutar el juego.


NO ES NECESARIO DESCARGAR O INSTALAR RECURSOS EXTRAS PARA EJECUTAR EL PROYECTO.

El proyecto utiliza los agentes de inteligencia artificial que proporciona Unity, en este caso el sistema de navegación, la cual permite mover a un personaje de manera inteligente dentro del juego. 

El sistema de navegación necesita su propia data para representar las áreas en las que puede navegar. Y en las áreas seleccionadas el agente puede caminar y pararse, debido que están conectados a un componente llamado navigation mesh (NavMesh). 

El NavMesh almacena las superficies de los polígonos(objetos) para poder razonar acerca el área entera donde se puede caminar.

El componente NavMesh permite:
  -	Encontrar caminos entre dos puntos
  -	Seguir un camino 
  -	Evitar obstáculos
  -	Mover al agente
  -	Navegar sobre superficies con cierto grado de inclinación
