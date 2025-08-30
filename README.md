📘 J&A (Juega y Aprende)
1. Nombre de la App

J&A (Juega y Aprende)

2. Propósito y problema que resuelve

El propósito es ayudar a los niños a aprender de manera intuitiva e interactiva a leer.
Esto aporta al desarrollo del aprendizaje de los niños, fomentando la lectura y la comprensión de frases mediante narración en voz y niveles de juego.

3. Pantallas iniciales (Activities)

Pantalla de Inicio: tendrá dos botones, Jugar y Opciones.

Menú de Niveles: muestra etapas y niveles disponibles.

Juego: pantalla principal para unir frases y escuchar narraciones.

Resultados: muestra puntaje y progreso del jugador.

Opciones: configuración de sonidos del juego.

4. Navegación entre pantallas

Inicio → Menú de Niveles (al presionar Jugar).

Menú de Niveles → Juego (se pasa el número de nivel como extra).

Juego → Resultados (se pasa puntaje y progreso como extra).

Resultados → Menú de Niveles (continuar o repetir nivel).

Inicio → Opciones (configurar sonidos y narración).

5. Componentes de Android previstos

Activities: para cada pantalla principal.

Intents: para navegación y envío de datos entre pantallas.

Palette y Attributes: para el diseño de interfaz.

Service: para mantener datos cuando el usuario minimiza la app o recibe una llamada.

BroadcastReceiver: para notificar al usuario cuando cambia la conexión (WiFi/Datos móviles).

ContentProvider: para manejar base de datos interna con frases, palabras e historias.

6. Datos a manejar

Puntajes y progreso del jugador.

Frases y palabras predefinidas.

Historias narradas y audios.

(Fuentes internas y/o externas según sea necesario).

7. Riesgos o desafíos iniciales

Integración de la narración por voz (Text-to-Speech).

Creación de una interfaz atractiva e intuitiva para niños pequeños.

8. Hitos de avance (3 semanas)

Semana 1: Crear estructura básica del proyecto.

Semana 2: Implementar la navegación entre pantallas y primeras pruebas de niveles.

Semana 3: Integrar narración de voz y sistema de guardado de progreso del jugador.

9. Repositorio Git

🔗 URL: https://github.com/xluket3/Juega-y-Aprende.git

El README esta semana contendrá:

Nombre de la App

Propósito

Pantallas iniciales

Navegación entre pantallas

Componentes de Android previstos

👨‍💻 Integrantes

Lucas Arce

Jorge Moncada

SDK: Android SDK 33+

Control de versiones: GitHub
