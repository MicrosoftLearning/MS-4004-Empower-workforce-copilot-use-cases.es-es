#  Análisis de una hoja de cálculo financiera con Microsoft 365 Copilot en Excel
---
Para los profesionales financieros, Microsoft 365 Copilot en Excel ofrece numerosas ventajas, como la capacidad de formular preguntas sobre tu conjunto de datos en lenguaje natural en lugar de usar fórmulas. La herramienta puede revelar correlaciones, sugerir escenarios hipotéticos y crear visualizaciones eficaces basadas en sus consultas. Por ejemplo, puedes usar Microsoft 365 Copilot en Excel para desglosar los datos de ventas por tipo y canal. O bien puede proyectar el impacto de un cambio de variable en los datos y, a continuación, generar un gráfico para ayudarle a visualizarlo. También puede modelar cómo un cambio en la tasa de crecimiento de una variable afectaría al margen bruto.

La conclusión es que al automatizar las tareas repetitivas, Microsoft 365 Copilot en Excel hace posibles enfoques más creativos e innovadores dentro de la plantilla, lo que acelera el progreso en varias líneas de negocio. Es una valiosa herramienta para los profesionales de las finanzas que quieren simplificar sus procesos diarios y tomar decisiones mejor fundadas.

Al usar Microsoft 365 Copilot en Excel, debes tener una tabla de Excel que incluya datos en una hoja de cálculo. Puede convertir rápidamente un rango de celdas en una tabla de Excel siguiendo estos pasos:

1.  Seleccione la celda o el rango en los datos.
2.  Seleccione **Inicio &gt; Dar formato como tabla**.
3.  En el cuadro de diálogo **Dar formato como tabla**, active la casilla junto a **Mi tabla tiene encabezados** si desea que la primera fila del rango sea la fila de encabezado.
4.  Seleccione **Aceptar**.

En este ejercicio, usarás Microsoft 365 Copilot en Excel para analizar una hoja de cálculo de tendencias de mercado que ya está en una tabla de Excel. En este ejercicio se examinan muchas de las funciones e indicaciones precompiladas de Copilot.

### Ejercicio

Como director de Finanzas de Fabrikam, quiere analizar la eficacia de las campañas de marketing Q1 de la empresa. Su director de Marketing le proporcionó una hoja de cálculo que identifica cada una de las campañas de marketing que hizo la empresa durante el primer trimestre. La hoja de cálculo proporciona cifras básicas de presupuesto e ingresos y el número de usuarios dirigidos y comprometidos. Ahora es su trabajo analizar los números para determinar la eficacia de cada tipo de campaña.

Realiza los siguientes pasos para usar Microsoft 365 Copilot en Excel para analizar los datos que aparecen en la hoja de cálculo de las campañas de marketing del primer trimestre:

1.  Seleccione el siguiente vínculo para descargar la hoja de cálculo [Fabrikam Q1 marketing campaigns](https://go.microsoft.com/fwlink/?linkid=2269124).
2.  Una vez completada la descarga, mueva el archivo a su cuenta de OneDrive y, a continuación, abra y cierre el archivo para obtenerlo en la lista de archivos usados más recientemente (MRU).
3.  Si tiene una pestaña de Microsoft 365 abierta en su explorador de Microsoft Edge, selecciónela ahora; de lo contrario, abra una nueva pestaña y escriba la siguiente URL: **https://www.office.com**
4.  En la página principal de **Microsoft 365**, seleccione el icono de **Excel** en el panel de navegación de la izquierda.
5.  En **Excel**, en la página **Archivo**, seleccione **Fabrikam Q1 marketing campaigns** en la lista de archivos.
6.  Seleccione la opción **Copilot** en la parte derecha de la cinta.
7.  En el panel **Copilot** que aparece, observe las indicaciones predefinidas que se muestran encima del campo de indicación. Antes de seleccionar cualquiera de estas indicaciones predefinidas para mejorar el análisis, primero quiere que Copilot haga algunos cambios específicos en la hoja de cálculo. Para empezar, quiere que Copilot identifique qué tipos de campaña son más rentables. Para ello, escriba la siguiente indicación:
    
    **Cree una tabla dinámica para analizar los ingresos totales generados por cada tipo de campaña**.
8.  Revise los resultados de este mensaje. Copilot mostró dos ventanas de respuesta. La primera respuesta incluía una tabla dinámica que resumía los ingresos totales por tipo de campaña. La segunda respuesta incluía una explicación de lo que hizo en la primera. En la primera respuesta que contiene esta tabla, seleccione el botón **+Agregar a una hoja nueva**. Al hacerlo, se agrega esta tabla a la **hoja 2** de esta hoja de cálculo, que Copilot abrió automáticamente.
9.  Al examinar la **hoja 2**, observa que Copilot no creó ningún gráfico para acompañar a la tabla dinámica. Al examinar la indicación que envió, se da cuenta de que acaba de pedirle que cree una tabla dinámica; en ningún momento mencionó nada de un gráfico. Le gustaría ver una visualización de estos datos, por lo que quiere escribir una indicación que pida a Copilot que genere un gráfico para que continúe con la tabla dinámica de la **hoja 2**. Sin embargo, tenga en cuenta que mientras se encuentra en la **hoja 2**, el campo de indicación está deshabilitado.
    
    > **NOTA:** El campo de indicación solo está habilitado en la hoja que tiene la tabla de Excel. Para esta hoja de cálculo, es la **hoja 1**. A medida que continúe con este ejercicio, cada vez que Copilot agrega datos a una nueva hoja, debe volver a la **hoja 1** para solicitar más cambios.
10. Seleccione **Hoja 1** y, a continuación, escriba la siguiente indicación:
    
    **En la hoja 2, ha creado una tabla dinámica para analizar los ingresos totales generados por cada tipo de campaña. Cree un gráfico en la hoja 2 para visualizar estos datos**.
11. Revise el resultado. Si Copilot creó un gráfico que muestra los ingresos por tipo de campaña, continúe con el paso siguiente. Sin embargo, si Copilot muestra un mensaje que indica que no puede pedirle que trabaje en una hoja distinta de la original que tiene la tabla de Excel, deberá simplificar la indicación anterior. En este caso, escriba la siguiente indicación:
    
    **Calcule los ingresos totales generados por cada tipo de campaña**.
12. Revise el gráfico que creó Copilot mostrando los ingresos por tipo de campaña. Este resultado es lo que quería, así que seleccione el botón **+Agregar a una nueva hoja** en la parte inferior de la ventana. Al hacerlo, se agrega este gráfico a la **hoja 3** de esta hoja de cálculo.
13. Al examinar la **Hoja 3**, observas cómo Microsoft 365 Copilot ha incluido la tabla dinámica junto con el gráfico. Se da cuenta de que la **hoja 2** tiene la misma tabla dinámica, mientras que la **hoja 3** tiene la tabla y el gráfico. Puesto que quiere que la **hoja 3** tenga la tabla y el gráfico, decide quitar la **hoja 2** para evitar cualquier confusión futura. Para eliminar la **hoja 2**, haga clic con el botón derecho en ella, seleccione **Eliminar** en el menú que aparece y, a continuación, seleccione **Aceptar** para confirmar la eliminación. De esta forma, se quedará con las hojas 1 y 3.
14. Ya que quiere hacer más cambios, seleccione **Hoja 1** para volver a la hoja que tiene la tabla dinámica.
15. Ahora quiere identificar qué campañas eran las más eficaces. Para ello, quiere que Copilot calcule la rentabilidad de la inversión (ROI) de cada campaña. Para calcular el ROI, escriba la siguiente indicación:
    
    **Calcule el ROI de cada campaña**.
16. Revise los resultados de este mensaje. Copilot le muestra el cálculo; puede seleccionar la opción **Explicar fórmula** para obtener una explicación del cálculo del ROI. Quiere que Copilot agregue el ROI a la hoja de cálculo, así que seleccione el botón **+Insertar columna** que aparece en la parte inferior de la ventana.
17. Anote los resultados. Copilot agregó una nueva columna que contiene el ROI de cada campaña. Aunque está bien, quiere que determine el ROI de cada tipo de campaña. Se dio cuenta de su error al revisar la indicación anterior. Pidió a Copilot que calculara el ROI de cada campaña, cuando, de hecho, quería calcular el ROI de cada tipo de campaña. Escriba la siguiente indicación para calcular el ROI de cada tipo de campaña:
    
    **Ese cambio parece bueno. Sin embargo, me gustaría que también calculara el ROI de cada tipo de campaña**.
18. Consulte los resultados. Copilot creó un gráfico que muestra el ROI por tipo de campaña. Seleccione la opción en la parte inferior de la ventana para **+Agregar a una hoja nueva**. Al hacerlo, se agrega esta tabla a una nueva **hoja 2** de esta hoja de cálculo. Además del gráfico de barras agrupadas que creó (mantenga el cursor sobre el gráfico para ver el tipo de gráfico), también creó una tabla dinámica que contiene el ROI por tipo de campaña. Después de terminar de revisar estos datos, seleccione **Hoja 1**.
19. Ahora quiere que Copilot determine qué campañas eran más eficaces para atraer a los usuarios. Considera que la mejor manera de visualizar estos datos es hacer que Copilot cree un gráfico que muestre la relación entre el total de usuarios dirigidos y el total de usuarios comprometidos. Para ello, escriba la siguiente indicación:
    
    **Cree un gráfico que muestre qué campaña era más eficaz para atraer a los usuarios**.
20. Consulte los resultados. Copilot creó un gráfico de barras de **usuarios comprometidos por nombre de campaña**. Sin embargo, si Copilot se limita a resumir el total de usuarios comprometidos por campaña, eso no es exactamente lo que quería. Para corregir este resultado, escriba la siguiente indicación:
    
    **Ese tipo de gráfico no es lo que estaba buscando. Cree un gráfico que muestre la relación entre el total de usuarios dirigidos y el total de usuarios comprometidos**.
21. Consulte los resultados. En nuestras pruebas, Microsoft 365 Copilot ha indicado que no pudo crear ningún gráfico de dispersión con estos datos. Sin embargo, explicó la tabla dinámica que creó. Cree que el resultado es lo suficientemente bueno por ahora, así que debe seleccionar el botón **+Agregar a una nueva hoja** en la parte inferior de la ventana de la tabla dinámica. Al hacerlo, se agrega esta tabla a la **hoja 4** de esta hoja de cálculo. Cuando haya terminado de revisar estos datos, seleccione **Hoja 1**.
22. Tiene un último dato que quiere que Copilot le proporcione. Quiere que Copilot identifique las campañas con mayor rendimiento en función de los ingresos generados. A continuación, puede usar esta información para identificar qué campañas son más rentables. Escriba lo siguiente:
    
    **Identifique las campañas con mayor rendimiento en función de los ingresos generados**.
23. Consulte los resultados. Copilot creó un gráfico que muestra los ingresos por nombre de campaña. Seleccione la opción en la parte inferior de la ventana para **+Agregar a una hoja nueva**. Al hacerlo, se agrega esta tabla a la **hoja 5** de esta hoja de cálculo. Además del gráfico de barras agrupadas que creó, también creó una tabla dinámica que muestra los ingresos totales por campaña. Cuando haya terminado de revisar estos datos, seleccione **Hoja 1**.
24. Esto completa los datos que quería que Copilot analizara. Sin embargo, tiene curiosidad por saber qué otras sugerencias puede tener Copilot para analizar mejor los datos de su campaña. En la lista de indicaciones predefinidas que aparecen encima del campo de indicación, busque una sugerencia titulada **Mostrar sugerencias para las columnas de fórmulas**. Si ve esta sugerencia, selecciónela ahora; si no la ve, escríbala manualmente en el campo de indicación.
25. Revise la columna sugerida. Si desea agregarla a la hoja de cálculo, seleccione el botón **+Insertar columna**. Si aparece una indicación predefinida que indica **Dame otra sugerencia**, selecciónela ahora. Sin embargo, si esta indicación predefinida no aparece, escríbala manualmente en el campo de indicación (en nuestras pruebas, a veces apareció antes de insertar la columna, pero desapareció después de insertar la columna).
26. Repita el paso anterior varias veces para que Copilot sugiera cálculos diferentes. Inserte los que quiera y omita los que no.
27. Ahora quiere que Copilot muestre algunos gráficos más que visualicen varios tipos de datos. En la lista de indicaciones predefinidas, seleccione el botón **Mostrar conclusiones de datos**.
28. Consulte los resultados. Si este gráfico le interesa, seleccione el botón **+Agregar a una hoja nueva** y, a continuación, vuelva a la **hoja 1**.
29. A continuación, seleccione el botón **¿Puedo ver otra conclusión?**. De nuevo, si este gráfico le interesa, seleccione el botón **+Agregar a una hoja nueva** y, a continuación, vuelva a la **hoja 1**.
30. Después de ver estos dos primeros gráficos, se da cuenta de que le gustan los distintos gráficos que proporciona Copilot. En lugar de examinar más gráficos uno por uno, quiere que Copilot agregue a la hoja de cálculo todas las conclusiones que pueda crear a partir de los datos. En las indicaciones predefinidas, seleccione la indicación **Agregar todas las conclusiones a la cuadrícula**.
31. Consulte los resultados. Copilot creó varios gráficos en la hoja final, junto con varias tablas dinámicas. Determinas que tu análisis está completo teniendo en cuenta todos los datos proporcionados por Microsoft 365 Copilot en Excel. Como Excel guardó automáticamente el archivo, cierre la pestaña del explorador Microsoft Edge.
