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
Introducción
---
Microsoft 365 Copilot permite a los profesionales de TI mejorar su eficiencia, simplificar las tareas complejas y optimizar los flujos de trabajo técnicos. Con Copilot, los profesionales de TI pueden administrar sin problemas las operaciones de TI, solucionar problemas técnicos, garantizar la seguridad del sistema y aplicar información controlada por datos para la toma de decisiones estratégicas.

Microsoft 365 Copilot sirve como una herramienta valiosa para los profesionales de TI, que les permite navegar por las complejidades de la administración tecnológica con facilidad. Con Copilot, pueden identificar y resolver rápidamente problemas técnicos para optimizar el rendimiento del sistema. De este modo, Copilot se convierte en un aliado indispensable en el kit de herramientas del profesional de TI. Al usar Copilot, los profesionales de TI pueden ahorrar tiempo y centrarse en aspectos críticos de su rol, como mejorar la confiabilidad del sistema, implementar soluciones innovadoras y abordar proactivamente los desafíos de TI.

Este módulo proporciona a los profesionales de TI las aptitudes y conocimientos necesarios para aprovechar la herramienta de finalización de código con tecnología de inteligencia artificial de Copilot para optimizar el flujo de trabajo y mejorar la productividad. Como profesional de TI, tu capacidad para usar Microsoft 365 Copilot de manera eficaz es fundamental para lo siguiente:

 -  **Automatización.** Copilot puede ayudar a los profesionales de TI a automatizar tareas repetitivas. Por ejemplo, puede ayudar con la administración de revisiones, la implementación de software e incluso la supervisión de red.
 -  **Seguridad**. Copilot puede ayudar a los profesionales de TI a garantizar la seguridad de sus sistemas. Por ejemplo, puede ayudar con la detección de amenazas, la administración de vulnerabilidades e incluso la respuesta a incidentes.
 -  **Solución de problemas**. Copilot puede ayudar a los profesionales de TI a solucionar problemas de forma más eficaz. Por ejemplo, puede ayudar con el análisis de la causa principal, el análisis de registros e incluso sugerir soluciones a problemas comunes.
 -  **Colaboración** Copilot puede ayudar a los profesionales de TI a colaborar de forma más eficaz. Por ejemplo, puede ayudar con la administración de proyectos, la comunicación del equipo e incluso con el uso compartido de documentos.
 -  **Integración con Microsoft 365**. Copilot se integra con aplicaciones de Microsoft 365 como Teams, Word, Outlook, PowerPoint y Excel. Esto significa que los profesionales de TI pueden usar Copilot en estas aplicaciones para obtener ayuda con su trabajo.

Microsoft 365 Copilot actúa como un asistente de escritura con tecnología de IA. Entiende el contexto, sugiere frases y ayuda a generar contenido, lo que puede mejorar la calidad de su trabajo. Los ejercicios de este módulo de casos de uso están diseñados para ayudar a los profesionales de TI a desarrollar las siguientes aptitudes:

 -  Usar Microsoft 365 Business Chat para resumir la información de una especificación de producto y crear un plan de proyecto para implementar el producto.
 -  Usar Microsoft 365 Copilot en PowerPoint para crear una presentación en función del plan de proyecto que has creado.
 -  Usar Microsoft 365 Copilot en Word para modificar un informe de especificación técnica.
 -  Usar Microsoft 365 Copilot en Outlook para redactar un correo electrónico resaltando los puntos clave del informe de especificación técnica.
