Descripción
Esta aplicación es una PWA (Progressive Web App) de alto rendimiento diseñada específicamente para profesores y personal administrativo que requieren un registro inmediato de gestiones en entornos sin acceso a impresoras o conexión estable a Internet. A diferencia de las soluciones basadas en la nube, esta herramienta prioriza la privacidad y la autonomía al procesar y almacenar toda la información localmente en el dispositivo del usuario.

Pilares del Proyecto
Zero-Cloud / Local-First: Utiliza localStorage para el almacenamiento de datos. No requiere cuentas, suscripciones ni conexión a internet para funcionar, eliminando cualquier límite de uso o riesgo de privacidad.

Speech-to-Action Nativo: Implementa SpeechRecognition de forma nativa para transformar dictados en registros estructurados (Agregar/Modificar/Borrar) de manera inmediata.

Gestión de Datos Soberana: Permite la exportación de la base de datos local a archivos CSV con nomenclatura cronológica automática (ej. oficios_docente_2026-05-13.csv), facilitando su posterior integración en reportes administrativos o sistemas como Notion.

UX Dinámica: Al detectar un nuevo comando de voz o entrada manual, la interfaz conmuta automáticamente a la pestaña de "Oficios" para una verificación visual instantánea.

Especificaciones Técnicas
Almacenamiento: Window.localStorage para persistencia de datos persistente sin base de datos externa.

Despliegue: Optimizado para GitHub Pages mediante protocolo HTTPS seguro.

Instalación: Configurada como PWA con Manifiesto de Aplicación; Chrome en Android detectará automáticamente el banner de instalación.

Control de Voz: Lógica de procesamiento de lenguaje natural (NLP) básica para la detección de intenciones (operaciones CRUD administrativas).
