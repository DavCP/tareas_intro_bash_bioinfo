# Filogenómica de *Tillandsia*

### - **Título del proyecto:** 
Filogenómica de *Tillandsia* subg. *TIllandsia*

### - **Introducción:** 
Dentro de la familia Bromeliaceae, la subfamilia más rica en especies es Tillandsioideae, y dentro de la familia y subfamilia, el género más rico en especies es *Tillandsia*, a su vez, el subgénero *Tillandsia* tiene una gran riqueza de especies. A pesar de grandes avances en los últimos años, para conocer las relaciones de parentezco dentro de este subgénero, ha sido dificil conciliar estas relaciones debido a procesos causantes de discordancia filogenómica, tales como la hibridación, introgresión y el reparto incompleto de linajes.

### - **Objetivos:**
1. Inferir las relaciones filogenéticas dentro de *Tillandsia* subg. *Tillandsia* a partir de datos de plastoma

### - **Estructura de carpetas:** 
```
$ tree -d -L 2 .
.
├── data
├── results
└── scripts

4 directories
```

![Estructura de directorios](/misc/images/screenshot.png "Estructura directorios")

### - **Programas a utilizar:** 

| Software | Versión | Descripción |
| -------- | ------- | ----------- |
| FastQC | 0.12.1 | Control de calidad de lecturas
| Trimmomatic | 0.40 | Limpieza de adaptadores y *reads* de baja calidad |
| Spades | 4.2.0 | Ensamble de novo de datos WGS |
| Captus | 1.6.1 | Pipeline bioinformático para la captura de loci |
| IQ-TREE | 3.0.1 | Software de inferencia filogenética |
| MAFFT | 7.525 | Alineamiento de secuencias |
| Trimal | 1.5.1 | Curación de alineamientos |
| GoTree | 0.5.1 | Editar árboles |

*Prueba del uso de tablas*


