MSSubClass: Identifica el tipo de vivienda involucrada en la venta.	

        20	CASA DE 1 PLANTA 1946 Y MÁS NUEVA TODOS LOS ESTILOS
        30	CASA DE 1 PLANTA 1945 Y MÁS ANTIGUA
        40	CASA DE 1 PLANTA CON ÁTICO TERMINADO TODAS LAS EDADES
        45	CASA DE 1½ PLANTA - SIN TERMINAR TODAS LAS EDADES
        50	CASA DE 1½ PLANTA TERMINADA TODAS LAS EDADES
        60	CASA DE 2 PLANTAS 1946 Y MÁS NUEVA
        70	CASA DE 2 PLANTAS 1945 Y MÁS ANTIGUA
        75	CASA DE 2½ PLANTAS TODAS LAS EDADES
        80	SPLIT O MULTINIVEL
        85	SPLIT FOYER
        90	DÚPLEX - TODOS LOS ESTILOS Y EDADES
       120	PUD (Desarrollo Unitario Planificado) DE 1 PLANTA - 1946 Y MÁS NUEVO
       150	PUD DE 1½ PLANTA - TODAS LAS EDADES
       160	PUD DE 2 PLANTAS - 1946 Y MÁS NUEVO
       180	PUD - MULTINIVEL - INCLUYE SPLIT LEVEL/FOYER
       190	CONVERSIÓN A 2 FAMILIAS - TODOS LOS ESTILOS Y EDADES

MSZoning: Identifica la clasificación general de zonificación de la venta.
		
       A	Agricultura
       C	Comercial
       FV	Residencial Village Flotante
       I	Industrial
       RH	Residencial de Alta Densidad
       RL	Residencial de Baja Densidad
       RP	Residencial de Baja Densidad Parque 
       RM	Residencial de Densidad Media
	
LotFrontage: Pies lineales de calle conectados a la propiedad

LotArea: Tamaño del lote en pies cuadrados

Street: Tipo de acceso vial a la propiedad

       Grvl	Grava	
       Pave	Pavimentado
       	
Alley: Tipo de acceso por callejón a la propiedad

       Grvl	Grava
       Pave	Pavimentado
       NA 	Sin acceso por callejón
		
LotShape: Forma general de la propiedad

       Reg	Regular	
       IR1	Ligeramente irregular
       IR2	Moderadamente Irregular
       IR3	Irregular
       
LandContour: Planitud de la propiedad

       Lvl	Casi Plano/Nivelado	
       Bnk	En Bancales - Elevación rápida y significativa desde el nivel de la calle hasta el edificio
       HLS	Ladera - Pendiente significativa de lado a lado
       Low	Depresión
		
Utilities: Tipo de servicios públicos disponibles
		
       AllPub	Todos los servicios públicos (E,G,A,& S)	
       NoSewr	Electricidad, Gas y Agua (Fosa Séptica)
       NoSeWa	Solo Electricidad y Gas
       ELO	Solo Electricidad	
	
LotConfig: Configuración del lote

       Inside	Lote interior
       Corner	Lote en esquina
       CulDSac	Cul-de-sac
       FR2	Frente en 2 lados de la propiedad
       FR3	Frente en 3 lados de la propiedad
	
LandSlope: Pendiente de la propiedad
		
       Gtl	Pendiente suave
       Mod	Pendiente moderada	
       Sev	Pendiente severa
	
Neighborhood: Ubicaciones físicas dentro de los límites de la ciudad de Ames

       Blmngtn	Bloomington Heights
       Blueste	Bluestem
       BrDale	Briardale
       BrkSide	Brookside
       ClearCr	Clear Creek
       CollgCr	College Creek
       Crawfor	Crawford
       Edwards	Edwards
       Gilbert	Gilbert
       IDOTRR	Iowa DOT y Ferrocarril
       MeadowV	Meadow Village
       Mitchel	Mitchell
       Names	North Ames
       NoRidge	Northridge
       NPkVill	Northpark Villa
       NridgHt	Northridge Heights
       NWAmes	Northwest Ames
       OldTown	Old Town
       SWISU	Sur y Oeste de la Universidad Estatal de Iowa
       Sawyer	Sawyer
       SawyerW	Sawyer West
       Somerst	Somerset
       StoneBr	Stone Brook
       Timber	Timberland
       Veenker	Veenker
			
Condition1: Proximidad a varias condiciones
	
       Artery	Adyacente a calle arterial
       Feedr	Adyacente a calle alimentadora	
       Norm	Normal	
       RRNn	A menos de 200' de Ferrocarril Norte-Sur
       RRAn	Adyacente a Ferrocarril Norte-Sur
       PosN	Cerca de característica positiva fuera del sitio--parque, cinturón verde, etc.
       PosA	Adyacente a característica positiva fuera del sitio
       RRNe	A menos de 200' de Ferrocarril Este-Oeste
       RRAe	Adyacente a Ferrocarril Este-Oeste
	
Condition2: Proximidad a varias condiciones (si hay más de una presente)
		
       Artery	Adyacente a calle arterial
       Feedr	Adyacente a calle alimentadora	
       Norm	Normal	
       RRNn	A menos de 200' de Ferrocarril Norte-Sur
       RRAn	Adyacente a Ferrocarril Norte-Sur
       PosN	Cerca de característica positiva fuera del sitio--parque, cinturón verde, etc.
       PosA	Adyacente a característica positiva fuera del sitio
       RRNe	A menos de 200' de Ferrocarril Este-Oeste
       RRAe	Adyacente a Ferrocarril Este-Oeste
	
BldgType: Tipo de vivienda
		
       1Fam	Unifamiliar Separada	
       2FmCon	Conversión Bifamiliar; originalmente construida como vivienda unifamiliar
       Duplx	Dúplex
       TwnhsE	Casa Adosada Unidad Final
       TwnhsI	Casa Adosada Unidad Interior
	
HouseStyle: Estilo de la vivienda
	
       1Story	Un piso
       1.5Fin	Un piso y medio: 2º nivel terminado
       1.5Unf	Un piso y medio: 2º nivel sin terminar
       2Story	Dos pisos
       2.5Fin	Dos pisos y medio: 2º nivel terminado
       2.5Unf	Dos pisos y medio: 2º nivel sin terminar
       SFoyer	Split Foyer
       SLvl	Split Level
	
OverallQual: Califica la calidad general del material y acabado de la casa

       10	Muy Excelente
       9	Excelente
       8	Muy Buena
       7	Buena
       6	Por Encima del Promedio
       5	Promedio
       4	Por Debajo del Promedio
       3	Regular
       2	Pobre
       1	Muy Pobre
	
OverallCond: Califica la condición general de la casa

       10	Muy Excelente
       9	Excelente
       8	Muy Buena
       7	Buena
       6	Por Encima del Promedio	
       5	Promedio
       4	Por Debajo del Promedio	
       3	Regular
       2	Pobre
       1	Muy Pobre
		
YearBuilt: Fecha de construcción original

YearRemodAdd: Fecha de remodelación (igual a la fecha de construcción si no ha habido remodelaciones o adiciones)

RoofStyle: Tipo de techo

       Flat	Plano
       Gable	A dos aguas
       Gambrel	Gambrel (Granero)
       Hip	A cuatro aguas
       Mansard	Mansarda
       Shed	Cobertizo
		
RoofMatl: Material del techo

       ClyTile	Teja de Arcilla
       CompShg	Teja Estándar (Composite)
       Membran	Membrana
       Metal	Metal
       Roll	Rollo
       Tar&Grv	Grava y Alquitrán
       WdShake	Tablillas de Madera
       WdShngl	Tejas de Madera
		
Exterior1st: Revestimiento exterior de la casa

       AsbShng	Tejas de Asbesto
       AsphShn	Tejas de Asfalto
       BrkComm	Ladrillo Común
       BrkFace	Frente de Ladrillo
       CBlock	Bloque de Hormigón
       CemntBd	Tabla de Cemento
       HdBoard	Tablero Duro
       ImStucc	Estuco Imitación
       MetalSd	Revestimiento Metálico
       Other	Otro
       Plywood	Contrachapado
       PreCast	Prefabricado	
       Stone	Piedra
       Stucco	Estuco
       VinylSd	Revestimiento de Vinilo
       Wd Sdng	Revestimiento de Madera
       WdShing	Tejas de Madera
	
Exterior2nd: Revestimiento exterior de la casa (si hay más de un material)

       AsbShng	Tejas de Asbesto
       AsphShn	Tejas de Asfalto
       BrkComm	Ladrillo Común
       BrkFace	Frente de Ladrillo
       CBlock	Bloque de Hormigón
       CemntBd	Tabla de Cemento
       HdBoard	Tablero Duro
       ImStucc	Estuco Imitación
       MetalSd	Revestimiento Metálico
       Other	Otro
       Plywood	Contrachapado
       PreCast	Prefabricado
       Stone	Piedra
       Stucco	Estuco
       VinylSd	Revestimiento de Vinilo
       Wd Sdng	Revestimiento de Madera
       WdShing	Tejas de Madera
	
MasVnrType: Tipo de enchapado de mampostería

       BrkCmn	Ladrillo Común
       BrkFace	Frente de Ladrillo
       CBlock	Bloque de Hormigón
       None	Ninguno
       Stone	Piedra
	
MasVnrArea: Área de enchapado de mampostería en pies cuadrados

ExterQual: Evalúa la calidad del material en el exterior 
		
       Ex	Excelente
       Gd	Buena
       TA	Promedio/Típica
       Fa	Regular
       Po	Pobre
		
ExterCond: Evalúa la condición actual del material en el exterior
		
       Ex	Excelente
       Gd	Buena
       TA	Promedio/Típica
       Fa	Regular
       Po	Pobre
		
Foundation: Tipo de cimentación
		
       BrkTil	Ladrillo y Azulejo
       CBlock	Bloque de Hormigón
       PConc	Hormigón Vertido	
       Slab	Losa
       Stone	Piedra
       Wood	Madera
		
BsmtQual: Evalúa la altura del sótano

       Ex	Excelente (100+ pulgadas)	
       Gd	Buena (90-99 pulgadas)
       TA	Típica (80-89 pulgadas)
       Fa	Regular (70-79 pulgadas)
       Po	Pobre (<70 pulgadas)
       NA	Sin Sótano
		
BsmtCond: Evalúa la condición general del sótano

       Ex	Excelente
       Gd	Buena
       TA	Típica - se permite ligera humedad
       Fa	Regular - humedad o algunas grietas o asentamientos
       Po	Pobre - Grietas severas, asentamientos o humedad
       NA	Sin Sótano
	
BsmtExposure: Se refiere a paredes a nivel del jardín o con salida

       Gd	Buena Exposición
       Av	Exposición Promedio (los split levels o vestíbulos típicamente puntúan promedio o superior)	
       Mn	Exposición Mínima
       No	Sin Exposición
       NA	Sin Sótano
	
BsmtFinType1: Calificación del área terminada del sótano

       GLQ	Buenas Habitaciones
       ALQ	Habitaciones Promedio
       BLQ	Habitaciones Por Debajo del Promedio	
       Rec	Sala de Recreación Promedio
       LwQ	Baja Calidad
       Unf	Sin Terminar
       NA	Sin Sótano
		
BsmtFinSF1: Pies cuadrados terminados tipo 1

BsmtFinType2: Calificación del área terminada del sótano (si hay múltiples tipos)

       GLQ	Buenas Habitaciones
       ALQ	Habitaciones Promedio
       BLQ	Habitaciones Por Debajo del Promedio	
       Rec	Sala de Recreación Promedio
       LwQ	Baja Calidad
       Unf	Sin Terminar
       NA	Sin Sótano

BsmtFinSF2: Pies cuadrados terminados tipo 2

BsmtUnfSF: Pies cuadrados sin terminar del área del sótano

TotalBsmtSF: Pies cuadrados totales del área del sótano

Heating: Tipo de calefacción
		
       Floor	Calefacción por Suelo
       GasA	Calefacción de gas por aire forzado
       GasW	Calefacción de gas por agua caliente o vapor
       Grav	Calefacción por Gravedad	
       OthW	Calefacción por agua caliente o vapor distinta a gas
       Wall	Calefacción de Pared
		
HeatingQC: Calidad y condición de la calefacción

       Ex	Excelente
       Gd	Buena