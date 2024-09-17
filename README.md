# Arroz
Predicción de arroz
url <- "https://raw.githubusercontent.com/ssvegahe/Arroz/main/Arroz%20Datos.txt"
data <- read_table(url)

## Estructura de base de datos
Datos|Significado|Tipo de variable
-----|-----------|---------
fecha|Fecha de evaluación|factor 
dds|Días despues de siembra|factor 
variedad|Variedad de arroz|factor
sistema|Sistema de siembra|factor
rendimiento|Rendimiento de arroz,kg/ha|númerico
NDVI|Indice de vegetación de diferencia normalizada|númerico
CIGREEN|Indice de clorofila verde|númerico
CVI|Indice de vegetación de clorofila|númerico
EVI|Indice mejorado de vegetación|númerico
GNDVI|Indice de vegetación diferencial normalizado verde|númerico
LCI|Indice de clorofila de la hoja|númerico
MCARI|Indice de clorofila y área foliar de la planta|númerico
ReCl|Indice de clorofila rojo|númerico
SAVI|Indice de vegetación ajustado por suelo|númerico
