# Paso 1 - recibir informacion
 por medio de los [[tickets]] voy a recibir las especificaciones de la caja, pueden ser en medidas, en producto en ideas etc, la meta es adaptar esa informacion a las necesidades del cliente

# Paso 2 - Crear el proyecto
hay que ir a ...Customer/ "Inicial del cliente"/ "nombre del cliente"
## paso 2.1A 
Si la carpeta del cliente ya existe entonces se crea unicamentela carpeta del proyecto 
	XXX"Inicials" - "nombre del proyecto"
	`EJ: "...Customer/A/AmazingLLC/Estimate/420AMZ - Awesome Box"`
## paso 2.1B
Si la carpeta del cliente no existe, se crea en la carpeta con la inicial del cliente,
- luego se compia los contenidos de ...Customer/ Empty Folder,
- se abre la nueva carpeta copiada "Estimate" y alli se crea la carpeta del proyecto XXX"Inicials" - "nombre del proyecto"
- `EJ: "...Customer/A/AmazingLLC/Estimate/420AMZ - Awesome Box"`

# Paso 3 - Dibujar caja/[[1UP]]
Dependiendo de la informacion y el requerimiento, hay que empezar un nuevo dise;o o usar un standard de [[ArtiosCAD]] 
- el primer dibujo que se hace es un [[1UP]] y se tiene que guardar con medidas y el [[Textos|texto]] estandar de CTP 

# Paso 4 - Dibujar el [[Nesting]]
El [[1up]] que acabamos de dibujar se pasa a manufacturing ![[Pasted image 20261105165104.png|27]]  y se aplican los estandars y parametros de CTP para Nestings que suele variar mucho segun el [[Material]]

# Paso 5 - Guardar PDF
Se guarda un PDF con capas con escala 1:1 usando las medidas de salida, en CTP usan los margenes de 2.5" para el pdf (tiene que ver con procesos de produccion mas adelanteen la cadena)

