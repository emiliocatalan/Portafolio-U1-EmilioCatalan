# Portafolio Unidad 1 – Ensayo de compresión de hormigón
Emilio Catalán Contreras

## Propósito

Este repositorio corresponde a la organización y documentación de un proyecto heredado sobre un ensayo de compresión de hormigón.

El objetivo es dejar el proyecto de manera ordenada y comprensible, para que otra persona pueda revisar los datos, identificar el procedimiento realizado y continuar el trabajo sin depender del autor original.

## Estructura del proyecto

El repositorio se organizó de la siguiente manera:

- `Proyecto_heredado_U1/Datos/Origen/`: contiene las planillas originales recibidas.
- `Proyecto_heredado_U1/Documentacion/`: contiene el informe, las notas y el archivo original de declaración de IA.
- `Proyecto_heredado_U1/Figura_resultados/`: contiene el gráfico entregado junto al proyecto.

Los archivos originales se mantienen sin modificaciones ni sobrescritura.
Esta estructura fue elegida para diferenciar claramente los datos originales, la documentación y los resultados del proyecto. De esta forma se evita sobrescribir los archivos heredados, se facilita la identificación de la procedencia de cada archivo y se permite que otra persona pueda continuar el trabajo de manera más ordenada.

## Procedencia de los archivos

### Archivos heredados

Los siguientes archivos corresponden al proyecto original recibido:

- `ensayo_hormigon.xlsx`
- `ensayo_hormigon_FINAL_v2.xlsx`
- `grafico_final.png`
- `informe_final.docx`
- `notas.txt`
- `USO_IA_sin_completar.md`

### Archivos creados durante esta actividad

Los siguientes archivos fueron creados durante el desarrollo del portafolio:

- `README.md`
- `USO_IA.md`

Los archivos heredados fueron conservados sin modificaciones ni sobrescritura.

## Datos de entrada

El archivo `ensayo_hormigon.xlsx` contiene los datos originales del ensayo:

- tiempo
- carga
- desplazamiento
- diámetro de la probeta: D = 150
- altura de la probeta: H = 300

Las unidades no están indicadas claramente en el archivo original, por lo que deben verificarse antes de utilizar los datos en nuevos cálculos.

También se recibió el archivo `ensayo_hormigon_FINAL_v2.xlsx`, que contiene las variables:

- P
- u
- sigma

## Procedimiento

A partir de la revisión de la planilla de resultados, se identificó que el esfuerzo `sigma` se calcula utilizando la carga P y un área de 17671,46.

La fórmula presente en la planilla es:

sigma = P × 1000 / 17671,46

El valor 17671,46 coincide con el área de una sección circular de diámetro 150, calculada mediante:

A = π × D² / 4

La planilla también obtiene el valor máximo de sigma mediante la función `MAX`.

## Salidas y resultados

El proyecto heredado entrega como resultado:

- una planilla con los valores de P, u y sigma;
- el valor máximo de sigma;
- un gráfico de esfuerzo en función del desplazamiento denominado `grafico_final.png`.

El gráfico fue entregado como un archivo de imagen separado de las planillas.

## Procedimiento reproducible

Para revisar y repetir el cálculo realizado en el proyecto heredado:

1. Abrir el archivo `ensayo_hormigon_FINAL_v2.xlsx`.
2. Identificar las columnas correspondientes a P, u y sigma.
3. Revisar el diámetro indicado en los archivos originales: D = 150.
4. Calcular el área de la sección circular mediante:

A = π × D² / 4

5. Para D = 150 se obtiene aproximadamente:

A = 17671,46

6. Comparar este resultado con el valor 17671,46 utilizado en las fórmulas de la planilla.
7. Revisar el cálculo de sigma utilizado en la planilla:

sigma = P × 1000 / 17671,46

8. Obtener el valor máximo de la columna sigma y compararlo con el resultado presente en la planilla.
9. Comparar los valores de desplazamiento y sigma con el gráfico `grafico_final.png`.

Las unidades no se encuentran completamente documentadas en los archivos originales. Por esta razón, la verificación realizada se limita a la consistencia numérica de los cálculos y no asigna unidades que no puedan ser confirmadas.

## Herramientas utilizadas

- Microsoft Excel
- GitHub
- Markdown para la documentación
- ChatGPT como herramienta de apoyo para comprender las instrucciones, revisar los archivos y apoyar la redacción del README y parte de la bitácora.
## Unidades y supuestos

Las unidades de tiempo, carga, desplazamiento, diámetro, altura y esfuerzo no se encuentran documentadas de manera explícita en los archivos originales.

Por esta razón, no se asignaron unidades que no pudieran ser verificadas con la información disponible.

El valor 17671,46 utilizado en la fórmula de esfuerzo coincide numéricamente con el área calculada para un diámetro de 150, pero la unidad del área tampoco está especificada en el proyecto heredado.

## Limitaciones

- Las unidades de las variables no están claramente documentadas.
- No se especifica la procedencia original de los datos.
- No se identifica la norma utilizada para realizar el ensayo.
- No se informa el equipo utilizado para obtener los datos.
- Existen dos archivos Excel y originalmente no estaba claramente documentado cuál correspondía utilizar.
- El gráfico fue entregado como una imagen separada y su procedimiento de generación no está completamente documentado.

## Cómo continuar el trabajo

1. Mantener los archivos originales sin modificaciones.
2. Crear copias nuevas si es necesario procesar o corregir información.
3. Verificar las unidades antes de realizar nuevos cálculos.
4. Registrar los supuestos y decisiones tomadas.
5. Documentar los cambios mediante commits en GitHub.
6. Actualizar este README si se incorporan nuevos datos, procedimientos o resultados.
