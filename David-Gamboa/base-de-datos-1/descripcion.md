# Base de datos 1: Cirrhosis Patient Survival Prediction

## a) Descripción general
- Nombre: Cirrhosis Patient Survival Prediction
- ¿Qué es? Datos de un ensayo clínico de la Clínica Mayo sobre cirrosis biliar primaria, una enfermedad crónica del hígado. Compara el medicamento D-penicilamina con un placebo. Sirve para predecir la supervivencia y la etapa de la enfermedad.
- ¿Cómo se obtuvieron? Registros clínicos de pacientes con exámenes de laboratorio y seguimiento (1974 a 1984). De 418 pacientes, 312 participaron en el ensayo aleatorizado y 106 solo fueron seguidos, por eso hay valores vacíos.
- Fuente: UCI Machine Learning Repository, https://doi.org/10.24432/C5R02G
- Filas y columnas: 418 filas, 20 columnas
- Formato: CSV

Cita: Dickson, E., Grambsch, P., Fleming, T., Fisher, L., & Langworthy, A. (1989). Cirrhosis Patient Survival Prediction [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5R02G.

## b) Descripción de columnas
| Nombre de columna | Tipo de dato | Descripción | Ejemplo |
|---|---|---|---|
| ID | Numérico (int) | Identificador del paciente | 1 |
| N_Days | Numérico (int) | Días entre el registro y la muerte, el trasplante o el fin del estudio | 400 |
| Status | Texto (str) | D = murió, C = vivo, CL = vivo por trasplante | D |
| Drug | Texto (str) | D-penicillamine o Placebo | D-penicillamine |
| Age | Numérico (int) | Edad en días | 21464 |
| Sex | Texto (str) | M = hombre, F = mujer | F |
| Ascites | Texto (str) | Líquido en el abdomen (Y/N) | Y |
| Hepatomegaly | Texto (str) | Hígado agrandado (Y/N) | Y |
| Spiders | Texto (str) | Arañas vasculares en la piel (Y/N) | Y |
| Edema | Texto (str) | N sin edema, S edema sin diuréticos, Y edema con diuréticos | Y |
| Bilirubin | Numérico (float) | Bilirrubina sérica (mg/dl) | 14.5 |
| Cholesterol | Numérico (float) | Colesterol sérico (mg/dl) | 261 |
| Albumin | Numérico (float) | Albúmina (gm/dl) | 2.6 |
| Copper | Numérico (float) | Cobre en orina (ug/día) | 156 |
| Alk_Phos | Numérico (float) | Fosfatasa alcalina (U/litro) | 1718 |
| SGOT | Numérico (float) | Enzima hepática (U/ml) | 137.95 |
| Tryglicerides | Numérico (float) | Triglicéridos (mg/dl) | 172 |
| Platelets | Numérico (float) | Plaquetas (por ml cúbico / 1000) | 190 |
| Prothrombin | Numérico (float) | Tiempo de protrombina (segundos) | 12.2 |
| Stage | Numérico (float) | Etapa histológica de la enfermedad (1 a 4) | 4 |
