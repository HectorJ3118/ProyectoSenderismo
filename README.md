# OPTITRAIL
El proyecto es una aplicación desarrollada en python que permite **calcular la mejor ruta de senderismo**, basandose en ciertos aspectos como el desnivel, la distancia y el tiempo que te llevaria recorrer cada camino,  haciendo que cada ruta que recorras sea una ruta superada.
![Image](https://github.com/user-attachments/assets/d5b8b652-1128-4d45-949c-51e112396844)
## Caracteristicas

- Lectura de archivos Excel con nodos (puntos de interés) y tramos entre ellos.
- Representación de los puntos y conexiones como un **grafo no dirigido**.
- Cálculo del camino más eficiente mediante el algoritmo de **Dijkstra**, dando más peso al desnivel.
- Visualización del grafo general y de las rutas posibles con resúmenes individuales.
- Interfaz basada en consola (con posibilidad de ampliar a GUI con `tkinter`.
- Soporte para rutas alternativas y generación de gráficas por ruta.
## Requisitos
- Python 3.10 o superior
- Bibliotecas:
  - `networkx`
  - `matplotlib`
  - `pandas`
  - (opcional) `tkinter` para futura interfaz gráfica
  ![Image](https://github.com/user-attachments/assets/10c5bde8-866c-4b14-a931-c3cb82fd762d)
## Recomendaciones para una correcta ejecución

**1-Asegurarse que se encuentre el archivo 
main.py, ubicado en ProyectoSenderismo/src y el directorio 
ProyectoSnederismo/src/data.**

2-Al momento de ejecutarse, estar seguro que se este dentro del directorio **ProyectoSenderismo**

3-Ejecutar python
```
python main.py
```
En el CMD
##
## Contribución
1-Crea un fork del repositorio

2-Clona mediante git clone:

3-Crea nueva rama 

4-Realiza tus cambios

5-Manda Pull Request

## Licencia

```
MIT
```
