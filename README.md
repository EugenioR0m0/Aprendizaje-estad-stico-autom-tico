# Aprendizaje estadístico automático

Los niveles de obesidad de la población son cada vez más preocupantes, sobre todo en países latinoamericanos. Por lo mismo, científicos de la Universidad de la Costa en Colombia se dieron a la tarea de recolectar información relacionada a este tema para individuos de Colombia, Perú y México.  
La base de datos original se encuentra en el *UCI Machine Learning Repository*, pero una versión simplificada la encontrarás disponible con el nombre **"A1.1 Obesidad.csv"** en la misma página de la plataforma donde descargaste esta plantilla.

La base de datos cuenta con la siguiente información:

- **Sexo**: Se describe como femenino (*Female*) o masculino (*Male*).
- **Edad**: Número entre 14 y 61.
- **Estatura**: Número en metros.
- **Peso**: Número en kilogramos.
- **FamiliarConSobrepeso**: Indica si algún familiar ha sufrido sobrepeso (*yes*) o no (*no*).
- **ComeMuchasCalorias**: Indica si el individuo come comidas con alto contenido calórico de forma frecuente (*yes*) o no (*no*).
- **ComeVegetales**:  
  - (1) Nunca come vegetales  
  - (2) Algunas veces  
  - (3) Siempre  
- **Fumador**: Si la persona es fumadora activa (*yes*) o no (*no*).
- **ConsumoDeAgua**:  
  - (1) Menos de un litro de agua al día  
  - (2) Entre uno y dos litros al día  
  - (3) Más de dos litros al día  
- **NivelDeObesidad**: Calculado con el índice de masa corporal (peso dividido entre estatura al cuadrado) y categorizado como:  
  - *Insufficient_Weight*: IMC < 18.5  
  - *Normal_Weight*: 18.5 ≤ IMC ≤ 24.9  
  - *Overweight_Level_I*: 25.0 ≤ IMC ≤ 29.9  
  - *Overweight_Level_II*: 30.0 ≤ IMC ≤ 34.9  
  - *Obesity_Type_I*: 35.0 ≤ IMC ≤ 39.9  
  - *Obesity_Type_III*: IMC > 40.0  

- [Reporte en ipynb](A1.1 612348.ipynb)
