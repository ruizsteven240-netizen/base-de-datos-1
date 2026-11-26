# Base de datos 2: Heart Failure Clinical Records

## a) Descripción general
- Nombre: Heart Failure Clinical Records
- ¿Qué es? Registros médicos de pacientes con insuficiencia cardíaca, para analizar qué factores clínicos se relacionan con el fallecimiento durante el seguimiento.
- ¿Cómo se obtuvieron? Historias clínicas de pacientes de un hospital de cardiología en Faisalabad, Pakistán, recogidas en 2015.
- Fuente: UCI Machine Learning Repository, https://doi.org/10.24432/C5Z89R
- Filas y columnas: 299 filas, 13 columnas
- Formato: CSV

Cita: Heart Failure Clinical Records [Dataset]. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5Z89R.

## b) Descripción de columnas
| Nombre de columna | Tipo de dato | Descripción | Ejemplo |
|---|---|---|---|
| age | Numérico (float) | Edad en años | 75 |
| anaemia | Binario (int) | Disminución de glóbulos rojos (0 no, 1 sí) | 0 |
| creatinine_phosphokinase | Numérico (int) | Enzima CPK en sangre (mcg/L) | 582 |
| diabetes | Binario (int) | Tiene diabetes (0 no, 1 sí) | 0 |
| ejection_fraction | Numérico (int) | Porcentaje de sangre que expulsa el corazón por latido | 20 |
| high_blood_pressure | Binario (int) | Hipertensión (0 no, 1 sí) | 1 |
| platelets | Numérico (float) | Plaquetas (kiloplaquetas/mL) | 265000 |
| serum_creatinine | Numérico (float) | Creatinina en sangre (mg/dL) | 1.9 |
| serum_sodium | Numérico (int) | Sodio en sangre (mEq/L) | 130 |
| sex | Binario (int) | 0 mujer, 1 hombre | 1 |
| smoking | Binario (int) | Fuma (0 no, 1 sí) | 0 |
| time | Numérico (int) | Días de seguimiento | 4 |
| DEATH_EVENT | Binario (int) | Murió durante el seguimiento (0 no, 1 sí) | 1 |
