
# Movilidad urbana y productividad económica en ciudades de LATAM 🚙 🚘

>[!NOTE]
> PROYECTO REALIZADO EN TRIPLETEN

Se analizó cómo la movilidad urbana se relaciona con la productividad económica en las principales ciudades latinoamericanas.

Para ello, se trabajó con datos reales de TomTom Traffic Index y OECD Cities, realizando procesos de limpieza, combinación y análisis para identificar en qué ciudades conviene invertir en infraestructura de transporte.


### Objetivos 🎯

1. Crear un dataset único y limpio a partir de dos fuentes diferentes.

2. Aplicar limpieza, estandarización y validación de tipos de datos.

3. Filtrar y enfocar el análisis en ciudades latinoamericanas.

4. Calcular indicadores agregados (por ciudad–año).

5. Realizar análisis exploratorios y visuales.

6. Documentar todos los pasos en Jupyter Notebook, exportar un dataset final y listo para análisis.



### Proceso 📝

- Carga de datos y vista rápida.
- Explorar, limpiar y preparar los datos.
- Renombrar columnas.
- Corregir formatos numéricos y de fecha.
- Extraer columna año y filtrar 2024.
- Calcular promedios de tráfico por ciudad.
- Unir tráfico (tabla principal) con indicadores económicos.



### Dataset

- tomtom_traffic.csv : Datos sobre congestión vehicular y condiciones de tráfico en ciudades del mundo.
- oecd_city_economy.csv : Indicadores económicos y ambientales por ciudad, recopilados por la OECD (Organización para la Cooperación y el Desarrollo Económico). 
 descar el archivo en: https://drive.google.com/file/d/1mnp9WWdmr9_A39IZ23JHhMZzh-N_KcD1/view?usp=sharing 


###  Principales Hallazgos  🔧

Ciudad de México es la ciudad con mayor tráfico y retraso en la movilidad, a diferencia de Montevideo, que presenta niveles significativamente menores de tráfico y retraso, aunque la diferencia en el PIB entre ambas ciudades es reducida.

Ciudad de México, Bogotá y São Paulo son las ciudades con mayor tráfico y retraso en Latinoamérica; sin embargo, mantienen un PIB considerable.
Montevideo presenta bajos niveles de tráfico y retraso, y lidera en PIB.
Santiago muestra niveles de tráfico y retraso equivalentes a aproximadamente la mitad de su PIB relativo.
 
                                      
