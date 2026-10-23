### Gripper
GRIPPER: N"

##### Nota
EL gripper siempre va a ser la medida del margen inferior
![[Artios_Gripper_sheet size.png]]
## [[1UP]] texto
CUSTOMER: 
REF:
SIZE: X x Y x Z
MATERIAL: 

FOR ESTIMATE ONLY
##### Ejemplo
CUSTOMER: NAPOLI 081 LLC 
    Customer: nombre del cliente
REF: 004NPL DESSERT BOX 1UP SLEEVE
     004:numero del archivo
     *NPL: iniciales del cliente*
     *DESSERT BOX: Descripcion de la caja*
     *1UP: tipo de dibujo*
     *SLEEVE: accesorios de la caja*
SIZE: 5+9/16 X 3+5/16 X 2+5/16
    las medidas no dependen del eje, tienen jerarquia, manda el flute direccion y despues el nesting
MATERIAL: 16PTS 1CS
    16[[Pts]]: folding carton thickness
    1CS tipo de sheen del material

ONLY FOR ESTIMATE

## [[NESTING]] TEXTO
CUSTOMER:
REF:
SIZE:
SHEET SIZE:
MATERIAL:
TOTAL K:
GLUE:
IMPO: 

FOR ESTIMATE ONLY

##### Ejemplo
CUSTOMER: NAPOLI 081 LLC 
    Customer: nombre del cliente
REF: 004NPL DESSERT BOX NESTING SLEEVE
     004:numero del archivo
     *NPL: iniciales del cliente*
     *DESSERT BOX: Descripcion de la caja*
     *NESTING: tipo de dibujo*
     *SLEEVE: accesorios de la caja*
SIZE: 5+9/16 X 3+5/16 X 2+5/16
    las medidas no dependen del eje, tienen jerarquia, manda el flute direccion y despues el nesting
SHEET SIZE: 23 x 29 1/8
	Las medidas de la hoja, en folding carton el primer numero tiene que ser 23 o 48 (limites de hojas aplican)
MATERIAL: 16PTS 1CS
    16[[Pts]]: folding carton thickness
    1CS tipo de sheen del material
TOTAL K: 416
	416: cantidad de perimetro del crease + cut
GLUE: STRAIGHT LINE
	Tipo de pega necesaria
IMPO: 3UP
	NUP: cantidad de 1UP que caben en la hoja

ONLY FOR ESTIMATE
![[Artios_Nesting text.png]]



### [[Lithomounted]] [[Nesting]] Text
CUSTOMER:
REF:
SIZE:
LITHO SHEET SIZE:
CORRUGATED SHEET SIZE:
MATERIAL:
TOTAL K:
GLUE:
IMPO: 

FOR ESTIMATE ONLY

##### Ejemplo
CUSTOMER: NAPOLI 081 LLC 
    Customer: nombre del cliente
REF: 004NPL DESSERT BOX NESTING SLEEVE
     004:numero del archivo
     *NPL: iniciales del cliente*
     *DESSERT BOX: Descripcion de la caja*
     *NESTING: tipo de dibujo*
     *SLEEVE: accesorios de la caja*
SIZE: 5+9/16 X 3+5/16 X 2+5/16
    las medidas no dependen del eje, tienen jerarquia, manda el flute direccion y despues el nesting
LITHO SHEET SIZE: 23 x 29 1/8
	Las medidas de la hoja
CORRUGATED SHEET SIZE: (X;Y)
	las medidas del litho pero hay que quitarle 1/4" (X-1/4; Y-1/4) *se colococa la direccion del flue primero
MATERIAL: 16PTS 1CS
    16[[Pts]]: folding carton thickness
    1CS tipo de sheen del material
TOTAL K: 416
	416: cantidad de perimetro del crease + cut
GLUE: STRAIGHT LINE
	Tipo de pega necesaria
IMPO: 3UP
	NUP: cantidad de 1UP que caben en la hoja

ONLY FOR ESTIMATE


![[Artios_Lithonesting text.png]]


![[GP_tickect component.png]]