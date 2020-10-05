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
         source kittiv/bin/activate
        ```
        
  (Las instalaciones de las librerías se hicieron por medio de pip)
 
## Instalar librerías especiales 🔧
```
pip install open3d-python
pip install hdbscan
```

Para más documentación sobre Open3D: http://www.open3d.org/docs/release/index.html
Para más documentación sobre HDBSCAN: https://hdbscan.readthedocs.io/en/latest/index.html
Para más documentación sobre algortimos de clusterin con scikit learn: https://scikit-learn.org/stable/modules/clustering.html
