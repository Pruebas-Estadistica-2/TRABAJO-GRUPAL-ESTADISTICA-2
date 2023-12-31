ENTREGA-1
============================================================

Miembros del grupo:

 + Joel B. Hu Ccallocunto (20196510)
 
 + Jose Rios (20181496)

Selección de las bases de datos
============================================================

Tema de investigación: Factores del desempleo juvenil en el mundo

## Variable dependiente: Desempleo de jóvenes de 15 a 22 años (BM) 

  - Porcentaje del resultado total de la mano de obra de jovenes que se encuentran en la edad de 15 a 22 años. Extraido de https://datos.bancomundial.org/

  - Data: [desempleoBM.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/desempleoBM.csv)

El desempleo es un problema económico, estructural por el cual miles de personas tienen que sobrevivir dia a dia. Consideramos que algunos factores socioeconomicos explicarán su incremento o disminución en el mundo. En ese sentido, de acuerdo a la revisión de literatura, consideraremos las siguientes variables:

## Variables independientes de José

- Cuatro variables independientes y sus respectivas metadatas:

### Infraestructura de Carreteras (CIA)

  - Revisa los kilometros de Carreteras pavimentadas y no pavimentadas y las suma.

Consideramos la importancia de los kilometros de carretera dentro del desempleo ya que una ausencia de carreteras dentro de un Estado puede terminar disminuyendo el area en la que un individuo puede trabajar, limitando sus opciones y por ende la posibilidad que este pueda o no trabajar.

  - Data: [RoadW.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/RoadW.csv)
  
       Extraido de https://www.cia.gov/the-world-factbook/field/roadways/country-comparison


### Libertad Civica (Democracy Index Wikipedia)

  - Revisa la Libertad civica, es decir, la libertad de los ciudadanos dentro del Estado en el que se encuentran residiendo.
  
Dentro de lo que se espera de la libertad civil podemos ver si los ciudadanos pueden o no tener acceso a un trabajo otorgado por el Estado o si les ayuda a conseguir uno mediante un intermediario. Horst Feldman (2010) considera que el desempleo tiene un efecto directo en la economias como reviso enel caso del Reino Unido y observa regiones y las tasas de dempleo que estas tienen al recolectar informacion de medios como la organizacion internacional del trabajo con el objetivo de legitimar su investigacion.

  - Data: Extraido de https://en.wikipedia.org/wiki/Democracy_Index en el xpath "/html/body/div[3]/div[3]/div[5]/div[1]/table[6]"


### Gastos en Educacion (CIA)
 
  - Los gastos de educacion compara el gasto publico en educacion como porcentaje al PIB
   
Consideramos que los gastos en eduacion influyen dentro del desempleo cuando consideramos que mientras mayor nivel educativo se puede alcanzar en un individuo, mas posibilidades de trabajo o de opciones de trabajo puede tener. Cesar Calvo (2012) considera tambien que los niveles educativos alcanzados tienen un efecto sobre los ingresos laborales dentro del Perú, por lo que podriamos extrapolar este pensamiento al resto de paises una vez asumido estas constantes.
   
  - Data: [GastosEdu.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/GastosEdu.csv)
   
       Extraido de https://www.cia.gov/the-world-factbook/field/education-expenditures/country-comparison


### Obesidad (CIA)

  - Considera el porcentaje de ciudadanos que son considerados obesos en un pais

La obesidad es un desorden que constituye un sobrepeso al punto de generar problemas psicologicos y fisicos de un individuo y puede tener efecto en la capacidad de una persona de mantener un empleo estable. Veronica Espinoza (2014) nos explica dentro del portal de la organizacion psico.org que la obesidad puede generar inseguridad y problemas a la hora de encontrar un empleo ya que se considera a la persona obesa fuera del parametro de una persona exitosa, lo que puede colaborar dentro del desempleo de las personas que se encuentran con este problema

  - Data: [ObesidadCIA.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/ObesidadCIA.csv)

       Extraido de https://www.cia.gov/the-world-factbook/field/obesity-adult-prevalence-rate/country-comparison


### Bibliografía:

-   Calvo, C. (2012) "La educacion como factor determinante de los ingresos laborales en el Perú"
https://repositorio.upch.edu.pe/bitstream/handle/20.500.12866/9686/Educaci%C3%B3n_CalvoRamirez_Cesar.pdf?sequence=3&isAllowed=y Fecha de consulta: 7 de octubre de 2022

-   Espinoza, V. (2014) "¿Es la obesidad una barrera para conseguir empleo?" Quito, Ecuador https://www.psico.org/articulos/obesidad-una-barrera-para-conseguir-empleo Fecha de consulta 6 de octubre de 2022

-   Feldman, H. (2010) "Capitulo 5: Libertad económica y desempleo" en Libertad Economica en el mundo: informe anual 2010
https://www.elcato.org/pdf_files/efw2010/efw-capitulo5-2010.pdf fecha de consulta 6 de octubre de 2022


## Variables independientes escogidas por Joel

- Cuatro variables independientes y sus respectivas metadatas:

### Inversión extranjera directa 

  - Entrada neta de capital (balanza de pagos, US$ a precios actuales)
 
En los paises desarrollados ha permitido mejorar el nivel de vida de sus miembros y una reactivación económica a corto plazo, por ello, queremos saber si influye aun si tomamos en cuenta a los demás países del mundo. Es decir, puede estar  relacionado con la dinámica de la actividad económica, en el sentido de que un insuficiente inversión extranjera eleva los niveles de desempleo general, y en especial el de los sujetos jóvenes.

  - Data: [inverex.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/inverex.csv)
  
    - La inversión extranjera directa constituye la entrada neta de de inversiones para obtener un control de gestión duradero (por lo general, un 10% o más de las acciones que confieren derecho de voto) de una empresa que funciona en un país que no es el del inversionista. Es la suma del capital accionario, la reinversión de las ganancias, otras formas de capital a largo plazo y capital a corto plazo, tal como se describe en la balanza de pagos. Esta serie refleja el neto total, es decir, la IED neta en la economía informante proveniente de fuentes extranjeras menos la IED neta de la economía informante hacia el resto del mundo. Esta serie refleja las entradas netas en la economía informante y se divide por el PIB. Datos en US$ a precios actuales.


### Crecimiento del PIB (% anual)

De acuerdo con Garavito (1998), el desempleo está vinculado de algun modo a los cambios en el ciclo económico, en ese sentido, en periodos de crisis, el desempleo se eleva, pese a que los asalariados estén remunerados relativamente bien. Por ello, advertimos una relación entre la tasa del desemppleo y el crecimiento del PBI.

  - Data: [PBI.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/PBI.csv)

    - Tasa de crecimiento anual porcentual del PIB a precios de mercado en moneda local, a precios constantes. Los agregados están expresados en dólares de los Estados Unidos a precios constantes del año 2010. El PIB es la suma del valor agregado bruto de todos los productores residentes en la economía más todo impuesto a los productos, menos todo subsidio no incluido en el valor de los productos. Se calcula sin hacer deducciones por depreciación de bienes manufacturados o por agotamiento y degradación de recursos naturales.


### Gestión económica

  - Promedio grupal de la CPIA (1=bajo a 6=alto). El grupo de gestión económica incluye la gestión macroeconómica, la política fiscal y las políticas de deuda.

Otro factor determinante es la gestión económica de cada país. La legislación laboral o política económicas pueden influir en la tasa de desempleo. Por ejemplo, los contratos de Formación Laboral Juvenil implementados hace un tiempo abaratan los costos de contratación de la fuerza~laboral joven, por lo que se eleva el desempleo en distintas empresas (Garavito).

  - Data: [geseco.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/geseco.csv)


### Población que vive en barrios de tugurios (% de la población urbana)

  - La población que vive en barrios marginales es la proporción de la población urbana que vive en hogares de barrios marginales. Un hogar de tugurios se define como un grupo de personas que viven bajo el mismo techo y carecen de una o más de las siguientes condiciones: acceso a agua mejorada, acceso a saneamiento mejorado, espacio suficiente para vivir y durabilidad de la vivienda.

En concordancia con De La Hoz et. al (2012), las condiciones socioeconómicas influyan en la situación laboral de lxs jóvenes. Según el ingreso del hogar, aquellos sujetos jóvenes integrantes de hogares con menores ingresos tienden a experimentar una menor probabilidad de ser empleadxs, en comparación con los integrantes de hogares con mayor ingreso. 

  - Data: [tugurio.csv](https://github.com/luccemhu/TRABAJO-GRUPAL-ESTADISTICA-2/raw/main/dfs_E2/tugurio.csv)


### Bibliografía:

-   Garavito, C. (1998). Determinantes del Desempleo en Lima Metropolitana, 1970-1996. Economia, 21(41), 143-183. Retrieved from https://revistas.pucp.edu.pe/index.php/economia/article/view/150

-   De La Hoz, F. J., Quejada, R. & Yánez, M. (2012). El desempleo juvenil: problema de efectos perpetuos. Revista Latinoamericana de Ciencias Sociales, Niñez y Juventud, 10, (1), pp. 427-439. Retrieved from http://www.scielo.org.co/pdf/rlcs/v10n1/v10n1a27