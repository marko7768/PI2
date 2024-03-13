# Proyecto de Análisis de Datos - Observatorio de Movilidad y Seguridad Vial (OMSV)

## Descripción
Este repositorio contiene el proyecto de análisis de datos realizado sobre el material del Observatorio de Movilidad y Seguridad Vial (OMSV) de la Ciudad Autónoma de Buenos Aires. El objetivo principal es generar información que permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales en siniestros viales.

## Datos
El dataset original utilizado para este análisis se encuentra en formato xlsx y abarca el periodo 2016-2021. Consta de dos hojas llamadas 'hechos' y 'víctimas'. Además, se proporcionan dos hojas adicionales de diccionarios de datos que sirven como guía para entender mejor la información compartida. Por comodidad y preferencia se decidioó pasar los datasets a formato csv.

## Estructura del Repositorio
- [datasets](https://github.com/marko7768/PI2/tree/main/datasets): Contiene el conjunto de datos en formato csv.
- [eda.ipynb](https://github.com/marko7768/PI2/blob/main/eda.ipynb): cuaderno de Jupyter utilizado para el análisis exploratorio de datos (EDA).

## Requisitos
- Python 3.x
- Jupyter Notebooks
- Bibliotecas de Python: Pandas, seaborn, scipy y numpy.

## Conclusiones 📝
Gracias al análisis exhaustivo de los datos aportados por el gobierno de la ciudad, notamos que:
- El género con mayor cantidad de víctimas es el masculino.
- Los principales acusados del hecho son los autos, transportes públicos y vehículos de carga.
- Históricamente la mayor cantidad de víctimas son conductores en moto, peatones y conductores de auto.
- La mayor cantidad de las víctimas en moto son de género masculino.
- La mayor cantidad de hechos sucede en los cruces (es decir, en esquinas).
- El rango etario de las víctimas fatales es entre 16 y 30 años, el género más afectado es masculino y suelen ser conductores de motos.
- En la comuna 1 es donde históricamente suceden mayormente los siniestros viales con fatalidades, los barrios son: Constitución- Montserrat- Puerto Madero - Retiro - San Nicolás - San Telmo, en este caso el tipo de víctima más afectado es el peatón y en segundo lugar motos.
- El tipo de calle donde mayormente suceden los incidentes es en avenidas, por ejemplo, en el mapa si se ve por comuna 1 se ve en la Avenida 9 de Julio los casos en mención.
- Los hechos que históricamente terminan en fatalidad suelen ser en el horario de 7,6 y 5 am (principalmente) y en cuanto a los días de la semana no hay días con menos o mayor diferencia a nivel histórico que marque gran diferencia.
- Los días que históricamente terminan en siniestro vial con homicidios son entre 13 y 15 de cada mes y; a fin de mes entre 26 y 29 de cada mes.
