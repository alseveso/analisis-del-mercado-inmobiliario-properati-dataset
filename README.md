# analisis-del-mercado-inmobiliario-properati-dataset
Se buscará ayudar a los tasadores/as de una gran inmobiliaria llamada Properati, a valuar las propiedades, ya que es un proceso difícil y, a veces, subjetivo.
Para ello, se crearán modelos de Machine Learning que, dadas ciertas características de la propiedad, prediga su precio de venta (previo EDA y preprocesamiento de datos).
Adicionalmente, se procederá a realizar la comparación de 3 algoritmos de Clustering (K-Means, Silhouette y DBSCAN), con el fin de observar los resultados arrojados por cada uno de ellos, respecto a cómo se encuentran concentrados los Barrios.

## Filas y columnas
En el presente Dataset, cada fila es una propiedad que se encuentra a la venta.

Con el fin de estimar el valor de un bien inmueble, se deben considerar ciertas cualidades y características del predio a analizar.
A continuación se detallan aquellas que podemos obtener del Dataset; algunas de ellas corresponden al nombre de cada columna, mientras que otras se obtienen del contenido de las mismas:

Ubicación: El encontrarse en un determinado barrio o en otro, puede aumentar el valor del metro cuadrado de la vivienda.  
Tipo de Inmueble: Se deberá consignar el tipo de propiedad. Puede ser Casa (incluye chalet) o dúplex, Departamentos, PH, Oficina, Lote, entre otros.  
Antiguedad: Se deberá evaluar la depreciación por la edad del inmueble. Variará en funcion del Estado de Conservación.  
Estado de Conservación: Del Inmueble Particular y del Edificio en caso de corresponder, valorándose el buen estado de las instalaciones, así como la realización de reformas recientes que hayan revalorizado la vivienda.  
Destino: Puede ser Residencial para vivienda, Industrial para uso fabril o Comercial para el desarrollo de espacio de oficinas y comercios, u Otros.  
Superficie Total: El precio unitario de una fracción urbana es un tanto menor cuanto mayor sea el área de la misma, a igualdad de las demás condiciones y viceversa.  
Superficie Cubierta: Se calcula con la suma total de áreas cubiertas o techadas del inmueble.  
Calidad de la vista: Es decir, si No tiene vista, si tiene Alguna vista del área circundante, o si tiene una Vista Importante, del horizonte, espejo de agua o río, muy buena vista, u otra característica escénica muy deseable.  
Orientación: Norte, Sur, Este, Oeste.  
Ambientes: Se contabilizarán la/s cocinas y dormitorio/s.  
Número de Baños: Si no se indica nada al respecto, supone que el inmueble tiene 1 sólo baño (salvo en caso de lotes, terrenos, cocheras, depósitos).  


## Recursos
1. Properati Dataset. Disponible en https://drive.google.com/file/d/1n9_Yc1ciLONPnoec7ginsoZn7f789sxo/view?usp=sharing
2. Cómo detectar y remover outliers. Obtenido de https://towardsdatascience.com/ways-to-detect-and-remove-the-outliers-404d16608dba
3. XGBoost Documentation. Obtenido de https://xgboost.readthedocs.io/en/latest/
4. Regresión Lineal. Obtenido de https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
5. DBSCAN. Obtenido de https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html
