DESARROLLO DEL PROBLEMA: 


MENDOZA CHAVEZ, CLAUDIA GABRIELA

 ANÁLISIS DE REGRESIÓN LINEAL MÚLTIPLE
 
 HT:	Investigar  en las mujeres que factores generan la tolerancia hacia la violencia por parte de sus parejes													     												
 El objetivo del estudio es determinar la relación y qué mantiene la tolerancia hacia la violencia. Por tanto, se realizará un análisis de regresión lineal múltiple. Se plantea el modelo de regresión lineal múltiple, donde se asocia una Variables dependiente cuantitativa (en este caso, la tolerancia hacia la violencia) con las Variables independientes (7)														
 
 modelo:	tolerancia (Y) = B0 + B1(autoestima) + B2(compromiso) + B3(dependencia) + B4(experiencia) + B5(intencion) + B6(rompimiento)+ B7(violenciaG) +- E.E											    
 
 se busca comprobar: 
     (AUTOESTIMA)		B1<0			
     (COMPROMISO)		B2>0			
     (DEPENDENCIA)		B3>0			
     (EXPERIENCIA)		B4>0			
     (INTENCIÓN) 		B5>0 	(de acuerdo a la codificación de sí)		
     (ROMPIMIENTO)		B6≠0			
     (VIOLENCIA G)		B7≠0	
 
 1. Contraste de ANOVA					
 H0	no habrá impacto de las VI's sobre la tolerancia				
 H1	al menos una de las VI's tiene impacto sobre la tolerancia 				
 
 conclusión: significancia obtenida =0.000, esto es menor a 0.05, por ende se rechaza H0, habrá influencia de al menos una de las variables independientes sobre la variable dependiente TOLERANCIA 
 
 2. Ajuste del modelo
 R² obtenido=0.843, esto supera a 0.25 por lo que se considera un buen ajuste según criterios de Cohen. Luego representa que 84.3% de la variabilidad de la tolerancia se debe a los cambios en al menos una de las variables independientes. 
 
LINARES LUQUE, SANDRA CAROLINA

Contraste de coeficientes nulos
 Hipotesis:
 Autoestima 	
 	H0	B1=0
 	H1	B1<0
 Compromiso	
	 H0	B2=0
	 H1	B2>0
 Dependencia	
	 H0	B3=0
	 H1	B3>0
 Experiencia	
	 H0	B4=0
	 H1	B4>0
 Intención 	
	 H0	B5=0
	 H1	B5>0
 Rompimiento 	
	 H0	B6=0
	 H1	B6≠0
 ViolenciaG	
	 H0	B7=0
	 H1	B7≠0
 
Impacto de las variables											
 Se observa que la variable más influyente es la de experiencias de violencia anteriores, esto debido a que su B tipificada es 20.552 en valor absoluto. 						Los cambios en esta variable generarán mayores cambios en la tolerancia 	

LIZARBE VILCA, ANGIE PAMELA

En cuanto al Supuesto de que No hay Heterocedasticidad en los residuos:
 Según lo que es posible apreciar en el gráfico, a partir de la prueba de Park, se observa que los residuos no poseen una tendencia o patrón definido, los datos se encuentran dispersos y la varianza es negativa, lo que la hace igual a cero. En ese sentido, podríamos afirmar que sí se estaría presentando homocedasticidad en los residuos. Entonces, se cumple el supuesto que requiere que se verifique la falta de heterocedasticidad en los residuos. 
 
 
 En cuanto al Supuesto de que NO existe una Relación Espúrea:
 •	Distancia de Cook: Su valor es de 0.003. Entonces, como es menor a 1, se puede afirmar que no habrán valores influyentes dentro de los residuos.
 •	Valor de influencia centrado (VIF): Su valor es de 0.015. Entonces, como es menor a 0.2, se puede afirmar que no habrán valores influyentes dentro de los residuos. 
 Con esta información, se comprueba que, efectivamente, los coeficientes son independientes.
 
 Comparación de Modelos
 
 •	Debido a que la Variable independiente de “Rompimiento” no tenía un efecto sobre la variable “Tolerancia”, se decidió generar un nuevo modelo que no incluyese dicha variable para así comprobar qué modelo predice mejor la 	Tolerancia hacia la violencia. El modelo original contaba con siete variables y el nuevo modelo cuenta con seis, por ello, se comparan los modelos utilizando el R cuadrado corregido o ajustado. 
 •	El R cuadrado corregido de este modelo de seis variables es mayor a 0.25, lo cual indica que existe un buen ajuste del modelo. Así el 84% de la variabilidad de Tolerancia se debe a los cambios en al menos una de las variables independientes.
 •	Se observa que R cuadrado corregido para ambos modelos es similar (con una diferencia decimal de 0.4, pues para el modelo de siete variables que incluía “Rompimiento” el R cuadrado corregido era 0.843) por lo que podríamos sostener que ambos modelos serían igual de buenos en la predicción de la Tolerancia. 
 •	No obstante, se prefiere el modelo original por obtener una mayor variabilidad. 
			

SALINAS LOYER, MARIA XIMENA

Comprobación de supuestos (Multicolinealidad, normalidad de residuos e independencia de residuos)
 
 Se verifica el supuesto de multicolinealidad: Se espera que las variables independientes sean independientes entre sí para que sus efectos se puedan separar y no se anulen entre sí .
 Para las variables significativas, se observa que la tolerancia en todos los casos se acerca a uno, mientras que el factor de inflación de varianza (VIF) es menor a 4.  En ese sentido, se puede concluir que no existiría una correlación excesiva entre las variables independientes dentro del modelo, las variables serán independientes entre sí.  	
 
 Se verifica la normalidad de los residuos, es decir, la normalidad de las diferencias entre los valores observados y  los valores pronosticados.
 Se obtiene que la significancia (sig: 0) es menor a cero, por lo que se rechaza la hipótesis nula, es decir, se acepta la hipótesis alterna. De tal manera se comprueba que los residuos no tienen una distribución normal.
 No obstante, se ha observado que para muestras muy grandes (como la presente que cuenta con más de 100 casos) se detecta la falta de normalidad debido a que una distribución normal exacta no existe en la realidad. Por esta razón se utiliza la asimetría y curtosis para examinar la severidad de la falta de normalidad.
 Se obtiene como resultado que la asimetría (1.634) tiene un valor menor a 3 y que la curtosis (9.181) presenta un valor menor a 10, por ende se puede aceptar la normalidad de  muestra.
 
 Por último, se verifica el supuesto de independencia de residuos, ya que al igual que las variables, se espera que los residuos sean independientes entre sí.
 Se obtiene que el estadístico Durbin-Watson se encuentra entre el intervalo de (1.5 - 2.5) por ende se considera que los residuos son independientes, sobre todo porque 1.851 es muy cercano a 2. 	

(CLAUDIA) CONCLUSIÓN GENERAL:	
 
 de acuerdo al estudio se comprobó que las variables que influyen en que las mujeres mantengan la conducta de tolerancia serán: el autoestima, el compromiso, la dependencia, la experiencia de violencia	
 rompimiento y la violencia G. se confirmó además las hipótesis en relación a las mismas y la direccionalidad o influencia (ser diferente de cero); se evidenció no obstante, que distinto a lo que pensaban	
 la intencion de terminar no tuvo efecto sobre la tolerancia a la violencia con lo que se niega que quienes tengan intencion de dejar a su pareja tendrán mayor tolerancia a la violencia. 	
 Asímismo, se evidencio que la variable que tuvo mayor impacto en los cambios en tolerancia fue el haber tenido experiencias de violencia anteriores con lo cual se podría inferir que habría una tendencia	
 a aguantar más violencia si ya se lo ha hecho antes (se puede relacionar con el hecho psicológico que involucra que si ya se ha hecho algo por alguien una vez, una segunda sería más sencilo - my usado en la persuacion). 	
 en relación a los supuestos, se cumplió todo, con lo que se puede indicar que el modelo resulta ser un buen predictor, que no hay influencia de la correlacion de las variables independientes ni de los residuos	
 y que estos ultimos son bastante pequeños por lo que lo pronosticado será bastante cercano a lo observado. 	
 

