# Semana 4: _Gacela_
## Turismo
En el [__notebook__](RallyDatos_Semana_4.ipynb) (que también puede consultar en [DeepNote](https://deepnote.com/project/RallyDatosSemana4-Duplicate-hEPqnBbtRymbhsxhpxB4Nw/%2Fnotebook.ipynb))
 se realiza un breve análisis de la base de datos _Presupuesto aprobado para proyectos de inversión territorializados 2021 al Primer trimestre_ (en formato _csv_) así como otras bases de datos que se encuentran en el [portal de ___Presupuesto Abierto Guanajuato___](https://presupuestoabierto.guanajuato.gob.mx/#/programaspresupuestariosGto).

Para revisar el trabajo resultante y descubrir más análisis, se le invita a visitar
[la página web de __Dataket__](https://dusty-sunstone-de5.notion.site/Dataket-Rally-de-datos-Guanajuato-ebdbfa97edd34b6dae1ffd3c5b8d121a).

### Nota 1
Con tal de mantener un repositorio cohesivo y autocontenido, en este directorio se incluyen las bases de datos usadas:
- La de los [Programas presupuestarios y sus ODS](alineacion_pp_ods.csv).
- Las de [inversiones aprobadas territorializadas en 2021 al primer trimestre](Inversion_1T_Qs_por_municipio.csv).

Sin embargo, se le recomienda nuevamente que visite la página de _Presupuesto Abierto_ para consultar con profundidad los metadatos, diccionarios y demás información descriptiva sobre esta base de datos. Además, en ese portal puede tener acceso a muchísimas más bases de datos con su respectiva información.

### Nota 2
Las gráficas donde aparece el estado de Guanajuato con su división por municipio se utilizaron a partir del archivo en formato _Geo json_ que realizó __Alberto Barradas__ en Diciembre del 2016 que se puede encontrar en el [siguiente sitio](http://datamx.io/sl/dataset/municipios-de-guanajuato).

### Nota 3
Con el fin de realizar un análisis más profundo del estado, se construyó una base de datos con la [población y la ubicación de las principales localidades de cada municipio del estado de Guanajuato](gto_poblacion_ubicacion.csv). Las poblaciones se obtuvieron de los datos publicados del [INEGI del 2020](http://cuentame.inegi.org.mx/monografias/informacion/gto/territorio/div_municipal.aspx?tema=me&e=11). Las ubicaciones (latitud y longitud) de los principales localidades se obtuvieron consultando cada uno de los lugares en Google Maps.
