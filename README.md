# DataMining4

## Práctica 1
Una tienda online de venta de vino quiere hacer un estudio de mercado. Han descubierto que muchos clientes valoran como buenos o muy buenos vinos que no son tan conocidos. Con la intención de adelantarse a la competencia quiere encontrar que factores podrían influir mas en esta elección. Usando el archivo vinos.csv y para 5 de las características que consideres que mas influyen: calcula y establece que tipo de relación hay entre ellas, dibuja un diagrama de dispersión con los casos en el que también se incluya el modelo obtenido y por último haz una predicción con varios datos.
1) ¿Qué diferencias hay entre los 5 modelos? (1,5 puntos)
2) Explica cómo funcionaría el posible sistema para clasificar vinos (simplifica la variable “quality”
creando 4 clases: muy malo, malo, bueno, muy bueno) creado con los 3 parámetros que más influyen entre los descritos arriba. (0,5 puntos)


## Práctica 2
Una empresa de representación de futbolistas quiere encontrar una manera optima de ordenar los jugadores para que los clientes puedan hacer unas búsquedas más eficientes en sus bases de datos. Para ello dispone de un set de datos “futbol.csv”. Aplica un algoritmo de manera que se obtengan dichos grupos.
1) Realiza todo el preprocesamiento que sea necesario para adaptar las variables que no sean unívocas del Dataset y poder usar el algoritmo adecuado. (1punto)
2) Utiliza varias configuraciones teniendo en cuenta el número de grupos que se creará y cambiando cómo se mide la distancia entre individuos. Crea una tabla donde se incluya toda la información y el número necesario de iteraciones para llegar a dicha solución. Se considera la mejor solución aquella que necesite menos iteraciones. (1 punto)
3) Con la mejor configuración del punto anterior. Utiliza dos criterios para elegir el lugar inicial del punto central de los grupos. Dibuja cómo se van modificando los grupos y cómo van cambiando sus centroides en cada iteración. Obtén una conclusión acerca de donde deberían situarse los centroides. (1 punto)
4) Estudia que técnicas de postprocesamiento se podrían aplicar en base al error cometido en cada clúster. (1 punto)


## Práctica 3
Una empresa de colocación de trabajadores pretende hacer una aplicación para ser mas eficientes en los enfermeros y enfermeras que asignan para cuidados en hogares. Para ello se dispone del archivo csv “enfermeria” con las características de las distintas personas que pueden optar a los puestos. Crear un modelo que agrupe los candidatos y establezca como se relacionan entre ellos jerárquicamente.
1) Utiliza varias configuraciones para el modelo que más se adapte y teniendo en cuenta los tipos de distancias entre elementos. ¿Cuál es la k del modelo? (1punto)
2) Dibuja un dendograma con los clústers obtenidos. Explica alguna de las relaciones interesantes que puedas encontrar. (1 punto)


## Práctica 4
Una empresa de publicidad cuenta con los datos de las ventas obtenidas (en €) cuando sus anuncios de publicidad aparecen en diferentes medios de comunicación. Para ello, se dispone del archivo “Advertising” con el detalle de las inversiones realizados en cada una de los distintos medios. Crear un modelo logístico que permita determinar si hay un beneficio suficiente en las ventas para dicha empresa de publicidad o no. Teniendo en cuenta que dicha empresa considera unas ventas suficientes aquellas mayores a 15€.
1) Desarrollar un modelo de regresión logística. Justificar y explicar alguna de las relaciones interesantes que puedas encontrar. (1punto)
2) Si se analizan los beneficios obtenidos al llevar a cabo dos anuncios publicitarios, cuyos beneficios obtenidos en TV son de 130, cuyas inversiones en radio no se tienen en cuenta, y cuya inversión en periódicos, en un caso son significativos, y en el otro no. ¿Cuándo existe una mayor probabilidad de obtener beneficios en dichos anuncios?. (1 punto)
