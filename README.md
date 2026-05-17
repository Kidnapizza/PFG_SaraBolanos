# The Dimming

Prototipo de videojuego 3D desarrollado en Unreal Engine 5 como Proyecto de Fin de Grado.  
El proyecto se centra en el uso de la iluminación como mecánica principal, combinando exploración, tensión ambiental, gestión de recursos, enemigos reactivos a la luz y puzles de progresión.

## Demo

[Ver vídeo de demostración](AQUÍ_PONES_EL_ENLACE)

También se incluyen capturas del prototipo en la sección de imágenes.

## Descripción

El juego plantea una experiencia de exploración en tercera persona donde el jugador debe avanzar por un entorno oscuro utilizando una linterna como herramienta principal.  
La luz no solo permite mejorar la visibilidad, sino que también afecta a la interacción con enemigos, superficies especiales, generadores y zonas seguras.

El objetivo del prototipo es validar una experiencia jugable basada en la tensión ambiental, evitando el combate directo y dando prioridad a la exploración, la gestión de recursos y la resolución de puzles.

## Características principales

- Sistema de linterna con consumo de batería.
- Diferentes usos de la iluminación dentro de la jugabilidad.
- Enemigos que reaccionan ante la luz.
- Zonas seguras iluminadas.
- Generadores que desbloquean nuevas zonas.
- Puzle basado en ondas sinusoidales.
- Superficies reflectantes y superficies atravesables mediante luz.
- Integración de efectos visuales con Niagara.
- Uso de Lumen para iluminación dinámica en tiempo real.
- Prototipo jugable desarrollado principalmente con Blueprints.

## Tecnologías utilizadas

- Unreal Engine 5
- Blueprints
- Lumen
- Niagara
- NavMesh
- AI Perception
- UMG / Widgets
- Git LFS

## Capturas

### Sistema de linterna

![Sistema de linterna](Media/screenshots/flashlight_system.png)

La linterna funciona como herramienta principal del jugador, permitiendo iluminar el entorno, gestionar la visibilidad y activar determinadas interacciones.

### Enemigos reactivos a la luz

![Enemigo](Media/screenshots/enemy_detection.png)

Los enemigos generan presión durante la exploración y modifican su comportamiento en función de la presencia de luz.

### Generadores y progresión

![Generador](Media/screenshots/generator_puzzle.png)

Los generadores actúan como elementos de progresión, desbloqueando nuevas zonas tras completar determinadas interacciones o puzles.

### Nivel final

![Nivel final](Media/screenshots/final_level.png)

El entorno combina zonas oscuras, puntos seguros iluminados y espacios de exploración diseñados para reforzar la tensión ambiental.

## Sistemas implementados

### Sistema de iluminación

La iluminación es el núcleo del prototipo. Se utiliza una linterna controlada por el jugador para afectar tanto a la visibilidad como a la interacción con distintos elementos del entorno.  
El uso de Lumen permite trabajar con iluminación dinámica en tiempo real, reforzando la relación entre las acciones del jugador y la respuesta visual del escenario.

### Sistema de batería

La linterna dispone de una batería limitada, lo que obliga al jugador a gestionar su uso. Este sistema introduce una capa de tensión y evita que la luz pueda utilizarse de forma constante sin consecuencias.

### Sistema de enemigos

Los enemigos se han diseñado como entidades de presión ambiental. No están orientados al combate directo, sino a condicionar el movimiento del jugador.  
Su comportamiento se apoya en navegación mediante NavMesh y lógica reactiva implementada en Blueprints.

### Sistema de puzles

El prototipo incluye puzles vinculados a la progresión, como un sistema basado en ondas sinusoidales donde el jugador debe ajustar parámetros para completar la interacción.

### Sistema de progresión

La activación de generadores permite desbloquear nuevas zonas del nivel, modificar el entorno y estructurar el avance del jugador.

## Cómo ejecutar el proyecto

1. Clonar el repositorio.
2. Abrir el proyecto con Unreal Engine 5.
3. Activar los plugins necesarios si Unreal los solicita.
4. Abrir el mapa principal.
5. Pulsar Play desde el editor.

> Nota: debido al tamaño del proyecto, algunos assets o builds pueden estar disponibles mediante enlaces externos.

## Estado del proyecto

Este repositorio contiene un prototipo académico desarrollado como Proyecto de Fin de Grado.  
El objetivo principal no es presentar un producto comercial final, sino una versión funcional que permita validar las mecánicas principales propuestas.

## Autora

Sara Bolaños Díez  
Proyecto de Fin de Grado — Ingeniería Informática / Videojuegos
