# Trabajo practico final de Matematica III
## Red Neuronal para la Predicción de Enfermedades Cardiovasculares
Implementación de una red neuronal artificial, construida desde cero y comparada con scikit-learn, orientada a predecir la probabilidad de que una persona desarrolle una enfermedad cardiovascular a partir de variables clínicas y de estilo de vida.

### Nuestro dataset: 
Elegimos una base de datos que explora los factores de riesgo para las enfermedades cardiovasculares en adultos. Utiliza datos personales (peso, edad, altura) asi como también habitos (si fuma, si toma alcohol). Nos brinda 13 variables de entrada y 1 de salida.

### Nuestro trabajo
Aplicamos tecnicas de aprendizaje automatico creando una red que se encargara de predecir la posibilidad de que una persona tenga una enfermedad cardiovascular de acuerdo a sus valores asociados de edad, peso, si es fumador, si realiza actividad fisica, entre otros. Se va a poder establecer la presencia de qué variables representan un factor de riesgo para la salud cardiaca. Se tuvo que acondicionar el dataset para garantizar la calidad de datos antes de entrenar a la red y esta se creo utilizando NumPy.

### Tecnologías Utilizadas
 
- Python 3
- NumPy
- Pandas
- Matplotlib / Seaborn
- scikit-learn

### Cómo ejecutar
 
1. Clonar el repositorio
2. Asegurarse de tener el archivo `factor-de-riesgo.csv` en el mismo directorio que el notebook
3. Instalar dependencias:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tqdm
   ```
4. Ejecutar el notebook `tp-mate3-version-final.ipynb` de forma secuencial
 
---
 

[Link del dataset](https://www.kaggle.com/datasets/thedevastator/exploring-risk-factors-for-cardiovascular-diseas/data)
