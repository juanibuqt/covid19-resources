# covid19-resources
Por donde empezar!

## Informacion general sobre COVID-19 e impresion 3D de protectores faciales

### Cuanto tiempo vive el virus en superficies y como afecta a los protectores o piezas impresas?

Aun esta investigandose cuanto tiempo el virus sobrevive en distintas superficies como metales y plasticos, pero papers especializados e investigaciones recientes hablaban de 2 a 3 dias, aunque hay opiniones distintas.

El 11/03/20 un estudio publicado en https://www.medrxiv.org/content/10.1101/2020.03.09.20033217v1.full.pdf habla de permanencia en el aire de 3hs, en el cobre 4hs, carton 24hs y plasticos o aceros inoxidables hasta 72hs. El 17/03/20 se ha publicado una actualizacion de estos estudios en https://www.nejm.org/doi/10.1056/NEJMc2004973.

Hay reportes de la CDC (Centers for Disease Control and Prevention) https://www.cdc.gov/mmwr/volumes/69/wr/mm6912e3.htm?s_cid=mm6912e3_w
de que se ha encontrado SARS-CoV-2 RNA hasta 17 dias despues del desembarque de todas las personas en cuarentena abordo del crucero "Diamond Princess". Sin embargo, esto fue antes de que los procedimientos de desinfección tuvieran lugar y "los datos no pueden usarse para determinar si la transmisión se produjo desde superficies contaminadas", según el análisis. En otras palabras, no está claro si las partículas virales en estas superficies podrían haber infectado a las personas del crucero.

Otro estudio publicado en febrero en The Journal of Hospital Infection analizó varias docenas de artículos publicados previamente sobre coronavirus humanos (aparte del nuevo coronavirus) para tener una mejor idea de cuánto tiempo podrian sobrevivir fuera del cuerpo humano https://www.journalofhospitalinfection.com/article/S0195-6701(20)30046-3/fulltext.

Como regla general podriamos decir que considerando que el virus puede sobrevivir hasta 90 dias en superficies plasticas, dejar las piezas impresas o mascaras ensambladas a resguardo por 4 dias aprox antes de distribuirlas es una buena idea y reducirias criticamente la probabilidad de transmision del virus, aunque no se puede asegurar al 100% la efectividad de esta medida. (Referencia: https://www.nejm.org/doi/pdf/10.1056/NEJMc2004973)

### Se habla mucho sobre limpieza de las mascaras, su desinfeccion, esterilidad y del problema de su porosidad, que hay de cierto y que tan viable es esta opcion si no se dispone de mascaras de uso medico?

La tecnica de impresion 3D que se esta utilizando hoy dia para la rapida impresion de estas piezas es FDM (Fused Deposition Modeling), este tipo de impresion es por capas de material (filamento) que se va fundiendo sobre la anterior y de esta manera consolidando la pieza. Utilizar PETG o PLA no cambia esta caracteristica, siempre se mantiene la condicion de "porosidad" en el objeto impreso y por ende el "riesgo" de no poder "desinfectar" del todo la pieza.

Tambien hay que decir que las mismas no estan pensadas para ser "esteriles" sino que sean lo mas "limpias o desinfectadas" posibles. Hablamos de esterilidad cuando las piezas van a entrar en contacto con el organismo de un paciente de forma directa. En este caso hablamos de desinfeccion al no tener contacto directo con el mismo.

Sin embargo hay que tener en cuenta la situacion actual de faltante total de este tipo de proteccion en los trabajadores de salud, por lo que podemos decir que en circunstancias de emergencia como las actuales, darian cierta via libre de utilizarse, pero tambien errar por el lado de la seguridad y tratarlos como de un solo uso es prudente, por lo que considerarlas como una "solucion temporal" de emergencia a corto plazo contra la escasez de otras opciones certificadas seria una buena practica.

En caso de intentar esterilizarlas, los impresos en PLA pueden hacerse con oxido de etileno, sin embargo por costos, tiempos no es lo mas recomendable.

Para mas informacion sobre metodos de esterilizacion consultar el PDF "Plastics Compatibility with Sterilization Methods from ISM and IS Med Specialties" que se encuentra en el repositorio en la seccion "Papers>Info" - https://github.com/juanibuqt/covid19-resources/raw/master/Papers%20-%20Info/plastics-sterilization-compatibility-chart-from-is-med-specialties.pdf

La recomendacion es desinfectarlas con alcohol al 70%, tanto las piezas impresas como las pantallas.

### Materiales de impresion

Actualmente se esta imprimiendo con lo que se tiene, pero los materiales ideales para impresion son PETG o PLA.
ABS no lo recomiendo por ser mas dificil para imprimir por tema temperaturas o tener una impresora cerrada idealmente, tambien aunque menor, por tema toxicidad en el proceso de impresion.

### Regulacion actual sobre la fabricacion de este tipo de protecciones (Ultima check de informacion oficial: 24/03/2020)

Actualmente la fabricacion de las mascaras esta exceptuada de regulacion en EEUU por FDA - https://www.cdc.gov/coronavirus/2019-ncov/hcp/ppe-strategy/face-masks.html. Por el momento no hay comunicacion ni documentacion emitida en Argentina por ANMAT, ni a favor o en contra de las mismas.

### Comprendo todo lo anterior, como tendria que manipular las piezas impresas o las mascaras ya ensambladas para entregarlas a profesionales de la salud?

* Lo ideal es manejarse como si uno estuviera infectado por COVID-19, basicamente porque por mas que no tengamos sintomas o lo estemos, podemos ser portadores sin saberlo. 
* Utiliza una mascara o barbijo, un par de guantes sin utilizar previamente para manipular las piezas impresas o ensamblar las mascaras.
* Guarda las partes o mascaras ensambladas en una bolsa y sellala inmediatamente de forma hermetica.
* Habla con el personal de salud a quien le estas haciendo las mascaras y contale donde y como es el entorno donde estas imprimiendo.
* Como explicaba arriba, aun esta investigandose cuanto tiempo el virus sobrevive en plastico o superficies, pero no entregues las mascaras hasta pasados 4 dias de haberlas impreso y que esten en una bolsa sellada y aislada con una etiqueta con la fecha de envasado (super importante!).
* No almacenes las piezas impresas o mascaras en un solo lugar, minimiza el riesgo de contaminacion cruzada, y trata de entregarlas lo antes posible una vez cumplido el plazo de "cuarentena" de las mismas para evitar el riesgo de que se contaminen al permanecer en tu casa o el entorno donde las almacenas.

### Soy personal de salud, nunca use EPP (Equipo de Proteccion Personal) y desconozco los cuidados, cuales son? hay alguna forma de utilizar todo esto que tenga que saber?

Si, existe una guia muy detallada sobre como se debe utilizar el EPP, cuidados y secuencia de colocacion de cada uno de los elementos, como tambien el descarte de los mismos. Toda esa informacion podes encontrarla en https://www.argentina.gob.ar/salud/coronavirus-COVID-19/recomendaciones-uso-epp


----------------------------------------------------------------------------------------------------------------------

## Modelos de FaceShields o Protectores Faciales Impresos 3D

Los protectores faciales son extremadamente necesarios para la gente de salud, los mismos sirven para proteger cara, ojos, nariz y boca. No son reemplazo de los barbijos N95 o comunes en algunos casos, sino que se deben utilizar en conjunto y forman parte de lo que se denomina EPP (Equipo de Proteccion Personal).

Hay cientos de diseños, testie algunos, pongo cada uno a continuacion con sus ventajas y desventajas y algunos datos importantes a tener en cuenta, materiales a utilizar y como mantener una cadena de seguridad para que no se contaminen y lleguen sin riesgo a quienes lo van a utilizar.

### Prusa Protective Face Shield - RC1 & RC2

![Image description](https://github.com/juanibuqt/covid19-resources/raw/master/Images/Prusa%20RC2%20Model.jpg)

https://www.prusaprinters.org/prints/25857-protective-face-shield-rc1/remixes

Tiempo Impresion: 2 hs de impresión (ø0.4mm Nozzle - 0.35mm de altura de capa) 

Consumo de material: 52 gr de PETG / PLA

PRO
- El diseño cumple su funcion, es resistente y comodo. 
- Es un modelo muy testeado y fue aprobado por el Ministerio de Salud de Republica Checa.
- Muy bien documentado todo el proyecto

CONS
- Sistema de encastre del acetato al modelo, puede salirse, pero funciona.
- Es preciso utilizar muchisimo material vs otros modelos.
- Mucho tiempo de impresion.

### Reversion Argentina de Prusa Face Shield - RC2

![Image description](https://github.com/juanibuqt/covid19-resources/raw/master/Images/FaceShieldArg_Rev_02.jpg)

https://www.thingiverse.com/thing:4235551

Tiempo Impresion: 
1:30 hs de impresión (ø0.4mm Nozzle - 0.3mm de altura de capa) 
0:55 hs de impresión (ø0.6mm Nozzle - 0.4mm de altura de capa)

Consumo de material: 25 gr de PLA

Optimizacion Maxima: 1:20 hs de impresion / 22 gr de PLA

PRO
- El diseño cumple su funcion, es resistente y comodo. 
- Se colaboro para llegar a este modelo pensando en reducir tiempos de impresion y consumo de material.
- Bien documentado, es posible escalarlo a produccion haciendo corte laser en el acetato.

CONS
- Sigue demandando bastante material vs otros modelos mas simples.
- Sigue siendo necesario bastante tiempo de impresion.


### Prusa Protective Face Shield - RC2 - A4 Remix

![Image description](https://github.com/juanibuqt/covid19-resources/raw/master/Images/Covid-19_headband_rc2_a4_fast.jpg)

https://www.prusaprinters.org/prints/26214-prusa-protective-face-shield-rc2-a4-remix/files

Tiempo Impresion: 
40 min de impresión (ø0.4mm Nozzle - 0.35mm de altura de capa) 

Consumo de material: 14 gr de PLA

PRO
- El diseño cumple su funcion, es resistente. 
- Es uno de los modelos mas basicos y rapidos de imprimir consumiendo la menor cantidad de material

CONS
- No es tan comodo como los otros modelos.
- No esta tan bien resuelta la sujecion de la pantalla frontal al impreso.

----------------------------------------------------------------------------------------------------------------------

## FaceShields o Protectores Faciales utilizando Corte laser

### LaserCut Medical Shield - Protector Facial por corte laser

https://hackaday.io/project/170481-laser-cut-medical-shield

----------------------------------------------------------------------------------------------------------------------

## FaceShields o Protectores Faciales caseros

### Protector Facial casero - Opcion 1
https://github.com/juanibuqt/covid19-resources/tree/master/Faceshield-casero-opcion1

Por Lic. Fga Florencia Araoz y Dra. Beatriz Araoz (Lab3bio - UNSAM)

### Protector Facial casero - Opcion 2
https://github.com/juanibuqt/covid19-resources/raw/master/Faceshield-casero-opcion2/Mascara%20casera.pdf

Por Marcos Bertuola - mbertuola@unsam.edu.ar / Marcos.bertuola@gmail.com (Lab3bio - UNSAM)

EoF
