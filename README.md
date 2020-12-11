# GridLayoutProject

Es un ejemplo de diseño de interfaces usando GridLayout. La tabla tiene 3 filas y 3 columnas, en todas las celdas hay un TextView menos en la última que tiene un Button. Los atributos más importantes para conseguir el diseño han sido:

- GridLayout: 
  - rowCount: número de filas de la tabla
  - columnCount: número de columnas de la tabla
  - layout_rowWeight: peso a repartir entre las filas 
  - layout_columnWeight: peso a repartir entre las columnas
  
- TextViews y Button:
  - layout_columnWeight: peso del TextView en su posición respecto de las columnas
  - layout_rowWeight: peso del TextView en su posición respecto de las filas
  - gravity: para centrar el texto en sentido vertical
  - textAlignment: para centrar el texto en sentido horizontal

- Interfaz gráfica de la actividad principal, vista de diseño

![Captura del diseño de la interfaz](https://raw.githubusercontent.com/pmdmdam2/GridLayoutProject/master/app/src/main/assets/gridlayout.png)
