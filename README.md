# Geothermometers
Reservoir Temperatures calculation with SiO2 and cations geothermometers

Aquí los enclaces de los cuadernos de jupyter notebook para abrirlos en Google Coolab y poder ejecutar el código python. 

https://colab.research.google.com/github/RosiMoreno/Geothermometers/blob/main/Geothermometres_Calculation_PouTermal.ipynb

https://colab.research.google.com/github/RosiMoreno/Geothermometers/blob/main/Geothermometres_Calculation_ALL_TEW.ipynb

Copiar y ejecutar este código en una "code cell" de Google Coolab si no existe previamente. Este código nos permite acceder a los excel e imágenes que se utilizan en el cuaderno. Las referencias no se abren directamente desde Google Coolab, pero se pueden consultar en la carpeta de "References" dentro de este repositorio.

# Descargar el repositorio completo desde GitHub
try:
    import google.colab
    IN_COLAB = True
except:
    IN_COLAB = False

if IN_COLAB:
    # Código para Colab
    !rm -rf proyecto
    !git clone https://github.com/RosiMoreno/Geothermometers.git proyecto
    import os
    os.chdir("proyecto")
    print("Directorio actual:", os.getcwd())
else:
    print("Estás en Jupyter local: se usa el directorio actual.")
