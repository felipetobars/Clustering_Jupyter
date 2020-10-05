# Clustering_Jupyter

_Se recomienda leer el reporte final donde se explica cuales variables se deben modificar para leer los datos binarios y para ajustar los parámetros de los algoritmos implementados._

## Pre-requisitos 📋
  El siguiente código fue probado en Jupyter Lab con python3.
  
  Se recomienda realizar un entorno virtual para hacer las instalaciones de librerías, así:
  
  En una terminal:
  
  python3 -m venv --system-site-packages ./<nombre_del_entorno>
 
  
  Ejemplo:
```
python3 -m venv --system-site-packages ./kittiv
 ```  
   
   Para iniciar el entorno virtual:
          ```
         source kittiv/bin/activate
        ```
   
   Para cerrar el entorno virtual:
    ```
         deactivate
        ```
        
  (Las instalaciones de las librerías se hicieron por medio de pip)
 
## Instalar librerías especiales 🔧

Con el entorno virtual **activado**, ejecutar:
```
pip install jupyterlab
pip install open3d-python
pip install hdbscan
```

Para más documentación sobre Open3D: http://www.open3d.org/docs/release/index.html

Para más documentación sobre HDBSCAN: https://hdbscan.readthedocs.io/en/latest/index.html

Para más documentación sobre algortimos de clustering con scikit learn: https://scikit-learn.org/stable/modules/clustering.html

## Abrir archivo .ipynb en Jupyter⚙️

Se usa el siguiente comando para ejecutar Jupyter Lab (con el entorno virtual **activado**):
```
jupyter lab
```

(El archivo .ipynb puede correr en otro entorno **local** difente al de Jupyter, pero se presentan problemas en entornos como el de Google Colab porque no permite ejecutar las ventanas emergentes de Open3D).
