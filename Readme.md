# Red social para detección de fraudes

La red social tiene como finalidad encontrar relaciones entre agentes, la intensidad de la relación es medida en base al número de clientes que tienen en común.

La descripción de los archivos se da a continuación:

1. La base de datos [BI.csv](/BI.csv) contiene los registros de entradas y salidas de clientes que salen y entran a la agencia.

2. El preprocesamiento de los datos puede localizarse en el archivo [Python Notebook](/main.ipynb).

3. El procesamiento de los datos da como resultado la [tabla_red_social.csv](/tabla_red_social.csv), la cual contiene los agentes y el número de clientes que tienen en común, datos que se usarán para realizar la red.

4. El notebook también brinda el archivo [social_net.html](/social_net.html) el cual es una red en formato html (esperar el renderizado).

5. El resultado final se resume en [dashboard_h1.pbix](/dashboard_h1.pbix), archivo que puede ser visualizado en Power BI.

## Dash board online
[Ver dashboard online](https://app.powerbi.com/view?r=eyJrIjoiOTQxYWQyNzAtNTExNC00MmMxLWE0MGYtZTUzOWNhMjc3OWNjIiwidCI6ImNhY2E5MDExLTdiNmEtNDRkZS04NjFmLTA5NWEyY2E4ODNiNyIsImMiOjR9&pageName=ReportSection)