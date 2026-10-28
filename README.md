# Piapc-TP_final_integrador_IA_NPCs

# Guardia y ladrón
Videojuego 2D desarrollado en Unity, en el que el jugador controla a un ladrón que debe escapar de un patio sin ser atrapado por un guardia controlado por inteligencia artificial.

# Características principales
Percepción del NPC: el guardia detecta al jugador mediante un campo de visión limitado por distancia y obstáculos.
Máquina de estados finitos (FSM): el guardia alterna entre patrullar, perseguir e investigar la última posición conocida del ladrón.
Algoritmos de búsqueda: implementación y selección de BFS y A* para calcular caminos.
Estrategias de navegación: selección entre una ruta corta y una ruta segura que evita zonas expuestas.
Generación de escenarios: mapas con distintas distribuciones de obstáculos y zonas expuestas, verificando que exista un camino válido hacia la salida.

# Objetivo
El jugador debe llegar a la salida antes de que el guardia lo atrape. El proyecto busca demostrar el funcionamiento de algoritmos de búsqueda, navegación, percepción y toma de decisiones en NPC.

# Tecnologías
Unity 2D
C#
OpenCode para asistir en el desarrollo guiado por especificaciones (spec-driven)

# Integrantes:
- Emanuel Dayer
- Valentin Cantarrutti
