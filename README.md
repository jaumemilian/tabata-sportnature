# Sport&Nature — Tabata & Interval Timer

Temporizador web minimalista de alta visibilidad diseñado para las pantallas/TV de sala y dispositivos móviles de **Sport&Nature**.

## Características principales

- **Diseño 100% adaptado a TV de sala (16:9) y Móvil**:
  - En TV/Desktop aprovecha todo el ancho de la pantalla con números gigantes y barras de gran grosor legibles desde cualquier punto de la sala.
  - En móvil se adapta automáticamente a una interfaz vertical tipo App con cuadrícula de controles `2×2` y tarjetas independientes.
- **Línea de Tiempo de la Sesión**:
  - Barra de progreso del intervalo actual con marca central del **50% (Mitad de tiempo)**.
  - Barra global segmentada proporcionalmente con todos los bloques de trabajo, descanso y series de la sesión (interactiva: permite saltar a cualquier bloque haciendo clic).
- **Sonidos Animados + Voz de Entrenador (`Web Audio API` + `SpeechSynthesis`)**:
  - **Preparación**: Arpegio ascendente + *"¡Preparados!"*
  - **Cuenta atrás (`3, 2, 1`)**: Pulso rítmico + *"Tres, Dos, Uno"*
  - **Arranque de Trabajo**: Fanfarria energética + campana de gimnasio + *"¡Empezamos! ¡Vamos!"* / *"¡Última ronda, a tope!"*
  - **Mitad de Tiempo (50%)**: Jingle triple ascendente + *"¡Mitad!"*
  - **Descanso**: Melodía descendente cálida + *"¡Descanso!"* / *"¡Fin de serie, recupera!"*
  - **Final**: Fanfarria triunfal + *"¡Tiempo! ¡Entrenamiento completado, buen trabajo!"*
- **Configuración por defecto**: `40s` Trabajo / `20s` Descanso × `8` Rondas (con guardado automático en `localStorage`).

## Uso y Despliegue

El archivo `index.html` es **100% autónomo** (incluye estilos, lógica, sintetizador de audio y el logotipo oficial incrustado en Base64). Basta con abrir `index.html` en cualquier navegador o desplegar el repositorio directamente en **Netlify**, **Cloudflare Pages** o **GitHub Pages**.
