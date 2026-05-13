Descripción
Esta aplicación es una PWA (Progressive Web App) de alto rendimiento diseñada específicamente para profesores y personal administrativo que requieren un registro inmediato de gestiones en entornos sin acceso a impresoras o conexión estable a Internet. A diferencia de las soluciones basadas en la nube, esta herramienta prioriza la privacidad y la autonomía al procesar y almacenar toda la información localmente en el dispositivo del usuario.

🚀 Características Principales
Offline-First & Privacy-Focused: Toda la información se almacena localmente en el dispositivo mediante localStorage. No requiere cuentas, servidores externos ni conexión a internet para la gestión de datos.

Reconocimiento de Voz Nativo: Implementa la SpeechRecognition API (vía HTTPS) para capturar comandos de voz y transformarlos en registros estructurados.

Detección Inteligente de Comandos:

Agregar: Detecta automáticamente el nombre del oficio y el estatus sugerido (Pendiente, En proceso, Completado).

Modificar/Borrar: Gestión simplificada de los registros existentes.

Interfaz de Usuario Adaptativa: Diseño limpio con Tabler Icons, modo de pestañas dinámico y retroalimentación visual mediante waveforms durante la grabación.

Exportación Soberana: Descarga de base de datos completa en formato CSV compatible con Excel (UTF-8 con BOM) y Google Sheets.

Instalación PWA: Banner automático de instalación para dispositivos Android, permitiendo su uso como una aplicación nativa.

🛠️ Stack Tecnológico
Frontend: HTML5, CSS3 (Flexbox/Grid), JavaScript Vanilla.

Iconografía: Tabler Icons (Webfont).

Persistencia: Web Storage API (localStorage).

Audio: Web Speech API.

Offline: Service Worker con almacenamiento en caché de activos principales.

📖 Instrucciones de Voz
La aplicación está optimizada para el dialecto es-MX. Puedes utilizar frases como:

"Agregar oficio de solicitud de mantenimiento pendiente"

"Circular informativa de rectoría completada"

"Permiso económico en proceso"

Al terminar de hablar, la aplicación detectará el nombre del oficio y te sugerirá el estatus correspondiente.
