# <p align=center> Cantidad de droga decomisada - Índice Bienestar Material <p>

#### Descripción General del Tema: 
El análisis propuesto se centra en la relación entre el Índice de Bienestar Material (IBM) y la cantidad de droga decomisada en los cantones de Costa Rica durante los años 2018-2020. Este estudio busca entender cómo el narcotráfico puede estar relacionado con la calidad de vida de los ciudadanos en diferentes áreas geográficas del país.

#### Descripción de los Datos y sus Principales Variables: 
Los datos utilizados en este análisis incluyen el Índice de Bienestar Material, que evalúa la calidad de vida en función del acceso a bienes y servicios esenciales, y la cantidad de droga decomisada, estandarizada en kilogramos, que incluye cocaína, crack y marihuana. Los datos se recopilaron a nivel de cantón y provienen del Programa de las Naciones Unidas para el Desarrollo (PNUD) y el Instituto Costarricense de Drogas (ICD).

#### Problemas que se Desea Resolver o Preguntas que se Espera Contestar:

**1.** ¿Existe una correlación entre el Índice de Bienestar Material en los cantones de Costa Rica y la cantidad de droga decomisada en esas áreas?
**2.** ¿Cuáles son los cantones con el mayor Índice de Bienestar Material y los mayores decomisos de droga?
**3.** ¿Cómo se visualiza la relación entre el Índice de Bienestar Material y la cantidad de droga decomisada utilizando un Sistema de Información Geográfica (SIG)?

## Objetivo General:

- Analizar la relación dada entre el Índice de Bienestar Material y la cantidad de droga decomisada para los años 2018-2020.

## Objetivos Específicos:
**1.** Determinar si existe una correlación entre el Índice de Bienestar Material en los cantones de Costa Rica y la cantidad de droga decomisada en esa misma área geográfica. 
**2.** Identificar los cantones con mayor Índice de Bienestar Material y cantidad de droga decomisada. 
**3.** Desarrollar una representación visual de la relación existente entre el Índice de Bienestar Material y la cantidad de droga decomisada mediante la utilización de un SIG.

## Justificación
En 2018, la relación entre la cantidad de droga decomisada y el índice de bienestar material en Costa Rica se justifica por la necesidad de entender el impacto del narcotráfico en la calidad de vida de los ciudadanos. Por lo que evaluar la relación entre las actividades delictivas relacionadas con las drogas y el bienestar material puede ayudar a identificar las áreas más afectadas y las posibles correlaciones entre el aumento del decomiso de drogas y la disminución o mejora del bienestar material.

Para 2020, la situación mundial había cambiado considerablemente debido a la pandemia de COVID-19. Este nuevo contexto afectó tanto al tráfico de drogas como al bienestar material de la población. La justificación para crear un mapa de relación en 2020 radica en analizar cómo la pandemia y las medidas de confinamiento afectaron estas variables. Además, permite evaluar si las estrategias implementadas en años anteriores tuvieron algún impacto duradero en la reducción del narcotráfico y la mejora del bienestar material.
 
 
 **_<p align=center>"Debido a que el tráfico de sustancias psicoactivas ilegales se realiza clandestinamente, a través de flujos de comercio y bienes legales, los mercados de drogas ilícitas dependen de una economía lícita que funcione. Por lo tanto, los cambios fundamentales en las actividades sociales y económicas de los países, resultantes de las restricciones a la movilidad y las medidas de distanciamiento social introducidas por los gobiernos para contener la pandemia de COVID-19, han tenido el potencial de afectar la oferta, distribución y demanda de drogas de diferentes manera."_** (UNODC, 2021)

## Metodología
Pasando ahora a la realización de este trabajo, se obtuvo la capa de cantones proporcionada por el SNIT. Seguidamente, se escogieron las variables a trabajar; en nuestro caso, el índice de bienestar material es una medida que evalúa la calidad de vida de una población basándose en su acceso a bienes y servicios esenciales. A esto se le suma la cantidad de droga decomisada, que se estandarizó a kilogramos. Cabe mencionar que los tipos de droga seleccionados fueron específicamente: 
- La cocaína 
- El crack  
- La marihuana. 
  
Por lo que los datos de los kilogramos de droga decomisada son el resultado de la suma de los decomisos de la cocaína, el crack y la marihuana en sus respectivos años. Los datos fueron proporcionados por el Atlas del Programa de las Naciones Unidas para el Desarrollo (PNUD) y por el Instituto Costarricense de Drogas (ICD).

Seguidamente se adjuntaron los datos a un excell con los códigos de cantones y de esta forma se unieron por medio de Qgis. Lo que fue la edición y la elección de colores de los mapas se realizó completamente gracias a herramientas digitales que ofrece ArcGIS. Entre las opciones proporcionadas se seleccionó una paleta con verdes, amarillos y azules; el amarillo se asocia mayormente a sustancias psicoactivas, aunque el verde tiene una asociación mayor debido a la hoja de marihuana, por lo que es de una fuerza mayor, junto a un alto índice de bienestar material. Por otro lado, el IBM se representa de color azul por comodidad de la paleta proporcionada y tiene significados de seguridad y pureza que representan variables positivas  (Brewer, 2016) .

Para finalizar, se eliminaron aquellos cantones que no proporcionaban datos porque afectaban directamente el análisis posterior. También se escogió el método de clasificación de Rupturas Naturales con clases de 4x4 debido a que ofrecía un mapa más armonioso y equilibrado, aprovechando mejor los colores de la paleta, ya que bajo el método de Cuantiles se observa un mapa predominantemente verde/amarillo con casi nulo uso de azules, además no presenta los cambios de dinámicas que representan los datos  (Monmonier, 2018) .

## Resultados

<p align=center> <img src="C:\Users\CHRISTOPHER\Documents\Tarea 1 progra\fig1.jpg" width=800>

**<p align=center> Figura 1. [Relación Cantidad de Droga Decomisada - Índice de Bienestar Material en 2018](https://arcg.is/1zrTyW)**


<p align=center> <img src="C:\Users\CHRISTOPHER\Documents\Tarea 1 progra\fig2.jpg" width=800>

**<p align=center> Figura 1. [Relación Cantidad de Droga Decomisada - Índice de Bienestar Material en 2020](https://arcg.is/1TCSXP0)**
## Conclusiones 
Al comparar los mapas de 2018 y 2020, se puede observar que algunos patrones y relaciones entre la cantidad de droga decomisada y el índice de bienestar material se mantienen constantes en ciertos cantones. No obstante, también puede haber ligeras variaciones en algunas áreas, lo que sugiere que las condiciones y dinámicas socioeconómicas pueden haber cambiado debido a diversos factores, incluyendo la pandemia de COVID-19.


## Referencias

Atlas de Desarrollo Humano Cantonal 2022. (2023). Programa de las Naciones Unidas para el Desarrollo. 
https://www.undp.org/es/costa-rica/publicaciones/atlas-de-desarrollo-humano-cantonal-2022  
 Brewer, C. (2016). DESIGNING BETTER MAPS: A GUIDE FOR GIS USERS, 2N D EDITION. ESRI press. 
 https://cartographicperspectives.org/index.php/journal/article/download/cp84-tickner/1473/7038 
Decomisos de Droga por Cantón y Distrito 2022. (2023). Instituto Costarricense sobre Drogas
 https://www.icd.go.cr/portalicd/index.php/estad-drogadecomisada?view=article&id=326&catid=2  
IGN-RN Limite Cantonal. Escala 1:5000, 2024. 
 Monmonier, M. (2018). How to lie with maps. University of Chicago Press.  
 https://books.google.com/books?hl=es&lr=&id=MwdRDwAAQBAJ&oi=fnd&pg=PP8&dq=How+to+lie+with+maps&ots=NvqML9Ha1b&sig=KQkEtGJEoMXw1xjoeG-yka7li_k 
UNODC, (2021), World Drug Report 2021 (United Nations publication, Sales No. E.21.XI.8).
 https://www.unodc.org/unodc/en/data-and-analysis/wdr2021.html
