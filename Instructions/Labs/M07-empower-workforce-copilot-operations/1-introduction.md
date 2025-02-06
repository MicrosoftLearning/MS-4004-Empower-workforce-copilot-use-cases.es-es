# Configuración del laboratorio:

En este módulo, crearemos avisos para Microsoft 365 Copilot que hagan referencia a archivos. En primer lugar, vamos a cargar todos los archivos necesarios en OneDrive para asegurarnos de que son accesibles en todo el laboratorio.


### Cargar archivos en OneDrive

Sigue los pasos siguientes para cargar todos los archivos necesarios en **OneDrive**:

1. Inicia sesión en la máquina virtual proporcionada por el proveedor de inquilinos con la cuenta de **administrador** local con la contraseña `Pa55w.rd`.
2. En la barra de tareas de Windows, selecciona **Microsoft Edge**.
3. En la barra de direcciones, escribe `https://www.office.com`.
4. En **Bienvenido a Microsoft 365**, selecciona **Iniciar sesión**.
5. En la **solicitud de inicio de sesión**, escribe `userx@yourtenant.onmicrosoft.com` (nombre de usuario e inquilino proporcionado por el inquilino proporcionado) y selecciona **Siguiente**.
6. En la pantalla **Escribir contraseña**, escribe la contraseña (proporcionada por el proveedor de inquilinos) para la cuenta de usuario y selecciona **Iniciar sesión**.
7. Si se te pide **Mantener la sesión iniciada**, selecciona **No volver a mostrar** y **Sí**.
8. En **Microsoft 365**, selecciona **Aplicaciones**.
9. En **Aplicaciones**, selecciona **OneDrive**.
10. En **OneDrive**, en la esquina superior izquierda, selecciona **+** (agregar nuevo) > **Carga de archivo**.
11. En **Explorador de archivos**, selecciona **Este equipo** > ** Disco local (C:)** y abre la carpeta **ResourceFiles**.
12. Selecciona todos los archivos de la carpeta **ResourceFiles** y, después, selecciona **Abrir** para cargarlos en **OneDrive**.
13. Una vez completada la carga, deberías ver **Se han cargado 29 elementos en Mis archivos** en el centro inferior de la pantalla.
14. Deja **Edge** abierto y ve a la siguiente tarea.

### Hacer referencia a archivos en Copilot

Al usar Copilot, es posible que descubras que algunos archivos no están disponibles inmediatamente en las sugerencias. Esto ocurre porque ciertas experiencias de Copilot solo hacen referencia a archivos de la lista de **Utilizado recientemente (MRU),** mientras que otros te permiten examinar **OneDrive** directamente. Para asegurarte de que un archivo aparece en la lista **MRU**, basta con abrirlo en la aplicación de Microsoft 365 pertinente y se agregará automáticamente.

> [!IMPORTANT]
> Microsoft 365 Copilot solo funcionará con archivos guardados en **OneDrive**. Los archivos almacenados localmente en el equipo deberán moverse a **OneDrive** para que Copilot pueda acceder a ellos.

A medida que avanzas en el módulo, tendrás oportunidades de probar varios mensajes en estos archivos. No dudes en probar diferentes enfoques para mejorar tus aptitudes con Copilot.

# Introducción
---
Este módulo dota a los Operations Manager de las aptitudes y los conocimientos necesarios para usar la herramienta de finalización de código basada en IA de Copilot con el fin de agilizar su flujo de trabajo y mejorar su productividad. Como administrador de operaciones, tu capacidad para usar Microsoft 365 Copilot de forma eficaz es fundamental para lo siguiente:<br>

 -  **Administración de proyectos**. Copilot puede ayudar a los Operations Manager a administrar proyectos de forma más eficaz. Por ejemplo, puede ayudarles con la asignación de tareas, la programación e incluso proporcionar información sobre el rendimiento del proyecto.
 -  **Automatización de procesos**. Copilot puede ayudar a los Operations Manager a automatizar tareas repetitivas. Por ejemplo, puede ayudarles con la entrada de datos, la generación de informes e incluso la revisión.
 -  **Colaboración** Copilot puede ayudar a los Operations Manager a colaborar de forma más eficaz. Por ejemplo, puede ayudarles con la comunicación del equipo, el uso compartido de documentos e incluso proporcionar recordatorios.
 -  **Personalización**. Copilot puede personalizarse para satisfacer las necesidades específicas de los Operations Manager. Por ejemplo, puede ayudarles con la administración del inventario, la optimización de la cadena de suministro e incluso el control de calidad.

Microsoft 365 Copilot actúa como un asistente de escritura con tecnología de IA. Entiende el contexto, sugiere frases y ayuda a generar contenido, lo que puede mejorar la calidad de su trabajo. Los ejercicios de este módulo de casos de uso están diseñados para ayudar a los Operations Manager a desarrollar las siguientes aptitudes:

 -  Usar Microsoft 365 Copilot en Whiteboard para generar ideas de plan de proyecto para instalar un nuevo sistema de caldera.
 -  Usar Microsoft 365 Copilot en Outlook para resumir un hilo de correo real y generar una respuesta.
 -  Usar Microsoft 365 Copilot en Word para crear un informe que analice los sistemas de calefacción de caldera frente a los de horno y comparar también los tipos de resultados que puede generar Copilot.
 -  Usar Microsoft 365 Copilot en PowerPoint para crear una presentación basada en el informe que has creado y que analiza los sistemas de calefacción de caldera y horno.
