# Reporte de comparación de comentarios de cambios contra el primer cuadro de revisión académica

**Documento con comentarios revisado:** `documento tesis gust y compas (1).docx`  
**Documento base del primer cuadro:** `CTFG-DOC-18 manoseable (1).docx`  
**Criterio usado:** se compararon los comentarios insertados en el documento con las observaciones del primer cuadro de revisión académica, usando el enfoque del prompt indicado: coherencia, objetivos, metodología, cronograma, redacción, formato, citas y referencias APA.

## 1. Resultado general

Se identificaron **5 comentarios de revisión** en el documento. Al compararlos con el primer cuadro:

| Resultado | Cantidad | Interpretación |
|---|---:|---|
| Coincidencias fuertes con el primer cuadro | 3 | El comentario coincide claramente con una observación ya señalada en el primer cuadro. |
| Coincidencias parciales | 1 | El comentario pertenece a una categoría ya señalada, pero el detalle específico no aparecía en el primer cuadro. |
| Observaciones nuevas / no iguales | 1 | El comentario no estaba cubierto de forma directa por el primer cuadro y debe agregarse como observación nueva. |
| Repetidos textuales exactos | 0 | No hay comentarios idénticos palabra por palabra respecto al primer cuadro. |

## 2. Matriz de comparación general

| N.º | Sección del documento | Comentario encontrado en el documento | Relación con el primer cuadro | Nivel de importancia | Recomendación de mejora | Redacción sugerida, cuando aplique |
|---:|---|---|---|---|---|---|
| 1 | Capítulo I. Introducción | “En 2010 poner punto seguido. Y reiniciar ‘Para esa entonces…’” | Coincidencia parcial. El primer cuadro ya advertía problemas de redacción y fluidez en la introducción, pero no señalaba esta oración específica. | Baja | Corregir la puntuación del primer párrafo y evitar oraciones extensas. | “La inauguración del nuevo edificio del Hospital San Vicente de Paúl se realizó el 4 de mayo de 2010. Para ese momento, según el Instituto Nacional de Estadística y Censos (INEC, 2010), la provincia de Heredia contaba con una población de 406.236 habitantes.” |
| 2 | Capítulo I. Introducción / cita del INEC | “No se indica de nuevo el nombre del INEC, ya lo hicieron. Solo el año. Favor revisar normas Appa en cuanto citas se refirere.” | Coincidencia fuerte. El primer cuadro ya solicitaba revisar citas, referencias, formato APA 7, correspondencia cita-referencia y fuentes incompletas. | Alta | Corregir la cita institucional según APA 7. Una vez definida la sigla, usar la sigla en citas posteriores. Corregir “Appa” por “APA”. | Primera cita: “Instituto Nacional de Estadística y Censos (INEC, 2010)”. Citas posteriores: “INEC (2022)” o “(INEC, 2022)”. |
| 3 | Estructura del documento / Resultados | “Esto se hizo?” | Coincidencia fuerte. El primer cuadro señalaba que los resultados debían evidenciar métricas de desempeño, evaluación del impacto, muestra, instrumento y análisis. | Alta | Verificar si realmente se incluyeron métricas de desempeño y evaluación. Si no se midieron, no debe afirmarse como resultado. Si sí se midieron, agregar evidencia, tabla, instrumento y análisis. | “Se presentan los productos desarrollados y la evaluación de la plataforma mediante los indicadores definidos, incluyendo métricas técnicas y valoración de usuarios del CGI.” |
| 4 | Capítulo IV / Portainer | “Se debe asignar numero posterior a revisar la numeración anterior.” | Coincidencia fuerte. El primer cuadro ya señalaba problemas de formato, numeración, índice, tablas y figuras. | Media | Revisar la numeración de apartados, tablas y figuras antes de la entrega formal. Usar estilos automáticos de Word. | “Aplicar estilos de título y actualizar el índice general, índice de tablas e índice de figuras antes de exportar la versión final.” |
| 5 | Capítulo IV / Configuración de InfluxDB | “Esto está mal” sobre `INFLUXDB_METRICS_INSECURE_CONNECTION: Permitir o no conexiones sin certificados SSL.` | Observación nueva. El primer cuadro no incluía esta corrección técnica específica. | Alta | Validar técnicamente la variable y su descripción. No dejar una explicación insegura o imprecisa sobre certificados SSL/TLS. Revisar documentación oficial de la herramienta usada antes de cerrar el manual técnico. | “Verificar el parámetro según la documentación oficial de InfluxDB. Si el parámetro habilita conexiones inseguras, debe explicarse como una configuración no recomendada para producción y sujeta a políticas de seguridad institucional.” |

## 3. Reporte de comentarios repetidos o coincidentes con el primer cuadro

Estos comentarios deben considerarse **repetidos por tema o criterio académico**, aunque no sean iguales palabra por palabra.

| Sección del documento | Observación encontrada | Nivel de importancia | Recomendación de mejora | Redacción sugerida, cuando aplique |
|---|---|---|---|---|
| Introducción / citas INEC | El comentario sobre no repetir el nombre completo del INEC y revisar APA coincide con el primer cuadro, donde ya se solicitaba revisar citas, referencias, formato APA 7 y correspondencia entre citas y bibliografía. | Alta | Corregir las citas institucionales según APA 7. Después de introducir la sigla, utilizarla de forma consistente. | “Instituto Nacional de Estadística y Censos (INEC, 2010)” en la primera aparición; luego “INEC (2022)” o “(INEC, 2022)”. |
| Resultados | El comentario “Esto se hizo?” coincide con la observación previa sobre falta de evidencia de métricas, evaluación de impacto, muestra e instrumento de validación. | Alta | Incluir evidencia concreta de evaluación o ajustar la redacción para no afirmar resultados no demostrados. | “La plataforma fue evaluada mediante indicadores técnicos y valoración de usuarios, cuyos resultados se presentan en la sección correspondiente.” |
| Portainer / formato | El comentario sobre asignar numeración después de revisar la numeración anterior coincide con la observación previa sobre inconsistencias de formato, índice, tablas, figuras y numeración. | Media | Corregir estilos automáticos, numeración jerárquica y referencias cruzadas. Actualizar el índice antes de entregar. | “La sección se numerará automáticamente conforme a los estilos de título aplicados en el documento.” |

## 4. Reporte de comentarios no iguales o nuevos frente al primer cuadro

Estos comentarios no aparecían de forma específica en el primer cuadro y conviene agregarlos al reporte de revisión.

| Sección del documento | Observación encontrada | Nivel de importancia | Recomendación de mejora | Redacción sugerida, cuando aplique |
|---|---|---|---|---|
| Introducción | El comentario sobre colocar punto seguido después de “2010” es una observación puntual de puntuación no detallada en el primer cuadro. Aunque se relaciona con redacción general, debe atenderse directamente. | Baja | Separar la oración inicial para mejorar claridad y estilo académico. | “La inauguración del nuevo edificio del Hospital San Vicente de Paúl se realizó el 4 de mayo de 2010. Para ese momento, la provincia de Heredia contaba con una población de 406.236 habitantes…” |
| Configuración de InfluxDB | El comentario “Esto está mal” sobre `INFLUXDB_METRICS_INSECURE_CONNECTION` es una observación técnica específica que no estaba en el primer cuadro. | Alta | Revisar la descripción técnica del parámetro, su relación con certificados SSL/TLS y sus implicaciones de seguridad. No debe quedar una explicación ambigua. | “Este parámetro debe documentarse conforme a la documentación oficial de InfluxDB y a las políticas de seguridad institucional. No se recomienda habilitar conexiones inseguras en ambientes productivos.” |

## 5. Revisión de citas y referencias APA

A partir del comentario relacionado con el INEC y del primer cuadro de revisión, se identifican estos puntos de atención:

| Problema APA detectado | Nivel de importancia | Recomendación |
|---|---|---|
| Se repite el nombre completo del INEC después de haber introducido la sigla. | Alta | En APA 7, cuando se define una abreviatura institucional, debe usarse de manera consistente en las citas posteriores. |
| La cita del INEC puede simplificarse para evitar duplicidad dentro de la misma oración. | Media | Usar una forma clara: “según el Instituto Nacional de Estadística y Censos (INEC, 2010)” o “(Instituto Nacional de Estadística y Censos [INEC], 2010)”. |
| Se debe verificar que las referencias completas del INEC 2010 y 2022 aparezcan en la lista de referencias. | Alta | Confirmar que ambas fuentes estén en la bibliografía con autor institucional, año, título exacto, entidad responsable y URL si corresponde. |
| El comentario usa “Appa”, pero el término correcto es “APA”. | Baja | Corregir en el comentario interno o en el reporte de atención de observaciones. |
| Debe revisarse la correspondencia cita–referencia en todo el documento. | Alta | Toda cita dentro del texto debe aparecer en referencias, y toda referencia debe estar citada en el cuerpo del documento. |
| Las fuentes institucionales y técnicas deben tener datos completos. | Alta | No dejar referencias incompletas, enlaces genéricos, autores sin título de documento, fechas ausentes o DOI mal formateados. |

## 6. Lista priorizada de atención

1. **Corregir la observación técnica sobre InfluxDB**, porque afecta la precisión técnica y puede tener implicaciones de seguridad.
2. **Verificar el comentario “Esto se hizo?”**, porque afecta la coherencia entre estructura del documento, resultados, métricas, evaluación e impacto.
3. **Corregir la cita del INEC según APA 7**, incluyendo siglas y correspondencia en referencias.
4. **Revisar numeración general antes de entregar**, especialmente capítulos, secciones, tablas, figuras y apartados técnicos como Portainer.
5. **Corregir la puntuación del párrafo inicial de la introducción**, como parte de la revisión final de estilo académico.

## 7. Comentario final como comité asesor

Al comparar los comentarios insertados en el documento con el primer cuadro de revisión académica, se observa que la mayoría de las observaciones ya estaban cubiertas de forma general: APA, evidencia de resultados, formato y numeración. Sin embargo, los comentarios del documento aportan dos elementos importantes que deben incorporarse explícitamente al reporte final de revisión: la corrección puntual del primer párrafo de la introducción y la validación técnica del parámetro `INFLUXDB_METRICS_INSECURE_CONNECTION`.

Como comité asesor, se recomienda atender primero los aspectos que comprometen la validez técnica y metodológica del documento, especialmente la corrección de configuraciones técnicas y la evidencia real de métricas o evaluación. Posteriormente, debe realizarse una revisión formal de APA, numeración, redacción y estilo antes de presentar la versión final.
