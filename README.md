# English Adventure 3.0 — Android tablet

Juego infantil sin anuncios ni cuentas, diseñado para tablets Samsung en horizontal.

## Incluye
- Dino animado (SVG local) y tres mundos: animales, colores y números.
- 5 preguntas por partida, 3 opciones táctiles y recompensas.
- Repetición de instrucciones y síntesis de voz nativa Android (`TextToSpeech`, inglés británico).
- Progreso local en WebView, sin permisos de red.
- Versión HTML de prueba en el archivo `app/src/main/assets/index.html`.

## Compilar APK
1. Abrir esta carpeta en Android Studio (con Android SDK 35 y JDK 17).
2. Esperar sincronización Gradle (plugin 8.7.3).
3. `Build > Build Bundle(s) / APK(s) > Build APK(s)`.
4. APK de depuración habitual: `app/build/outputs/apk/debug/app-debug.apk`.
5. Copiar a la tablet e instalar tras autorizar la instalación desde esa fuente.

## Nota sobre las voces
La tablet debe tener instalado un motor TTS y datos de voz inglesa. Si faltan, instalar la voz inglesa desde los ajustes de texto a voz de Android. El juego funciona sin internet, pero sin voz inglesa instalada no se oirán las instrucciones.

## Estado
Proyecto fuente preparado, no compilado ni probado en una tablet física. Para un lanzamiento posterior conviene añadir ilustraciones y audios propios, pruebas de accesibilidad y controles parentales.
