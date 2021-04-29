# Analisis de dataset de videojuegos con Regression Lineal y metodos de regularizacion
 
Proyecto para Lenguajes modernos de programación. (Enero-Junio de 2020).
 
 ### El proyecto se divide en 2 partes
 
 ## I. Explicacion e intuicion detras de los métodos, utilizando pocos datos
 
 ![imagen](https://user-images.githubusercontent.com/30305964/80812388-79e63100-8b8d-11ea-94b1-60db60d65ab2.png)

![imagen](https://user-images.githubusercontent.com/30305964/80812414-8e2a2e00-8b8d-11ea-9383-8cd72ab5ed5f.png)

![imagen](https://user-images.githubusercontent.com/30305964/80812435-984c2c80-8b8d-11ea-9548-7d644cec196f.png)

![imagen](https://user-images.githubusercontent.com/30305964/80812454-a26e2b00-8b8d-11ea-974d-fcfaad95c53a.png)
 
 ## II. Analisis de dataset de videojuegos
 
 Link del dataset: https://www.kaggle.com/xapulc/jpsales
 Gracias Victor Kharlamov por crear el dataset. 
 
 Antes de alimentar el modelo se hace un proceso de ingenieria de datos para seleccionar features, remover outliers, datos faltantes, etc.
 
 ![imagen](https://user-images.githubusercontent.com/30305964/80812523-c598da80-8b8d-11ea-8269-2d6e752a463e.png)

![imagen](https://user-images.githubusercontent.com/30305964/80812590-dcd7c800-8b8d-11ea-9a71-8738b82b9109.png)

 
 Para la prediccion se usan los features de 
 <ul>
 <li>Ventas en Europa</li>
 <li>Ventas en el resto del mundo</li>
 <li>Calificacion de los usuario</li>
 </ul>
 
 Y se busca predecir las ventas en Norteamerica (NA_Sales).
 
 Primero se utiliza regresion lineal, y después los metodos de regularizacion ridge, lasso y elastic net regression. 
 
 
![imagen](https://user-images.githubusercontent.com/30305964/80812683-08f34900-8b8e-11ea-9955-b6d1ea7f5acb.png)

![imagen](https://user-images.githubusercontent.com/30305964/80812718-1c061900-8b8e-11ea-950a-1965f243e313.png)
 
 
 
 
