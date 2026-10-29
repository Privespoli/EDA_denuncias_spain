# Análisis de denuncias por desaparición en España

Análisis exploratorio de datos realizado con Python, pandas y matplotlib a partir de datos abiertos publicados por la Comunidad de Madrid y procedentes del Centro Nacional de Desaparecidos.

## Objetivo

Explorar cómo se distribuyen las denuncias por desaparición por año, estado y sexo registrado, e identificar tendencias en los datos disponibles.

## Dataset

- **Periodo analizado:** 2010–2025
- **Ámbito:** toda España
- **Unidad:** número de denuncias
- **Fuente:** [Datos abiertos del gobierno de España](https://datos.gob.es/es/catalogo/a13002908-personas-desaparecidas-por-ano-de-denuncia-y-estado)
- **Formato original:** CSV

El archivo no permite comparar comunidades autónomas o provincias, porque sus columnas territoriales están vacías. Tampoco contiene edades.

## Preguntas de análisis

- ¿Cómo cambian las denuncias activas y cesadas por año?
- ¿Cómo se distribuyen las denuncias por sexo registrado?
- ¿Cómo evoluciona el total anual de denuncias activas y cesadas?
- ¿Qué porcentaje de las denuncias de cada año figura como activo en los datos?

## Visualizaciones

### Denuncias activas y cesadas por año

![Denuncias activas y cesadas por año](graficos/01_denuncias_por_estado_y_ano.png)

### Denuncias por sexo registrado

![Denuncias por sexo registrado](graficos/02_denuncias_por_sexo.png)

### Evolución anual de las denuncias

![Evolución anual de las denuncias](graficos/03_evolucion_anual.png)

### Porcentaje de denuncias activas por año

![Porcentaje de denuncias activas por año](graficos/04_porcentaje_activas.png)

## Herramientas

- Python
- pandas
- matplotlib
- Google Colab

## Limitaciones

Los datos cuentan denuncias, no necesariamente personas únicas. El estado mostrado corresponde a la fecha de extracción del dataset. Las denuncias cesadas pueden tener distintos desenlaces, que este CSV no detalla.

## Archivo del análisis

[Ver o descargar el notebook](analisis_desapariciones.ipynb)
