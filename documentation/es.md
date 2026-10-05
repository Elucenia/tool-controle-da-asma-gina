<!-- ELUCENIA technical documentation · controle-da-asma-gina · es · no clinical/professional/rights approval -->

# Control de los síntomas del asma (GINA)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/controle-da-asma-gina)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Síntomas diurnos más de 2 veces por semana

`diurno`

### Algún despertar nocturno por asma

`noturno`

### Uso de medicación de alivio (SABA) más de 2 veces por semana

`alivio`

### Alguna limitación de actividades por asma

`limit`

## Edición del método

GINA estrategia 2021: síntomas de 4 semanas, 4 preguntas; SABA de rescate; 0/1–2/3–4

## Fórmula documentada

En las últimas 4 semanas cuente: síntomas diurnos \> 2×/semana; despertar nocturno por asma; SABA de rescate \> 2×/semana (no cuenta antes del ejercicio); limitación de actividad.

0 = controlada · 1–2 = parcialmente controlada · 3–4 = no controlada.

## Límites y población

La evaluación GINA 2021 calculada aquí abarca el control de síntomas en las últimas cuatro semanas en adultos y niños mayores de 5 años, con la pregunta de alivio referida a SABA. Este recuento no evalúa todo el riesgo futuro de exacerbación, la función pulmonar, las comorbilidades, la técnica inhalatoria ni la adherencia. El control sintomático y la gravedad del asma no son equivalentes. La adaptación del material sigue sujeta a las condiciones de derechos del titular.

## Referencias

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
