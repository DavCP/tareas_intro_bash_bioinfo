# Filogenómica de *Tillandsia*

### - **Título del proyecto:** 
Filogenómica de *Tillandsia* subg. *TIllandsia*

### - **Introducción:** 
Dentro de la familia Bromeliaceae, la subfamilia más rica en especies es Tillandsioideae, y dentro de la familia y subfamilia, el género más rico en especies es *Tillandsia*, a su vez, el subgénero *Tillandsia* tiene una gran riqueza de especies. A pesar de grandes avances en los últimos años, para conocer las relaciones de parentezco dentro de este subgénero, ha sido dificil conciliar estas relaciones debido a procesos causantes de discordancia filogenómica, tales como la hibridación, introgresión y el reparto incompleto de linajes.

### - **Objetivos generales:**
1. Inferir las relaciones filogenéticas dentro de *Tillandsia* subg. *Tillandsia* a partir de datos de plastoma completos

### - **Objetivos particulares:**
1. Hacer ensambles *de novo* de los plastomas de *Tillandsia*

### - **Estructura de carpetas:** 
```
$ tree -d -L 2 .
.
├── data
├── metadata
├── results
└── scripts
5 directories
```

![Estructura de directorios](/misc/images/screenshot.png "Estructura directorios")

### - **Programas a utilizar:** 

#### Apptainer

Se utilizarán contenedores de Biocontainers obtenidos desde [Quay.io](https://www.quay.io/)


| Software | Versión | Descripción | Contenedores Apptainer |
| -------- | ------- | ----------- | ------------- |
| FastQC | 0.12.1 | Control de calidad de lecturas | fastqc:0.12.1--hdfd78af_0 |
| Trimmomatic | 0.40 | Limpieza de adaptadores y lecturas de baja calidad | trimmomatic:0.40--hdfd78af_0 |
| Spades | 4.2.0 | Ensamble de novo de datos WGS | spades:4.2.0--h8d6e82b_2 |
| Captus | 1.6.1 | Pipeline bioinformático para la captura de loci | captus:1.6.1--pyh05cac1d_0 |
| IQ-TREE | 3.0.1 | Inferencia filogenética por máxima verosimilitud | iqtree:3.0.1--h503566f_0 |
| MAFFT | 7.525 | Alineamiento de secuencias | mafft:7.525--h031d066_1 |
| Trimal | 1.5.1 | Curación de alineamientos | trimal:1.5.1--h9948957_0 |
| GoTree | 0.5.1 | Manejo y edición de árboles filogenéticos | gotree:0.5.1--he881be0_0 |

*Prueba del uso de tablas*

#### Pixi
Para Pixi, se incluyen los archivos pixi.toml y pixi.lock que definen el software a utilizar en este proyecto. (pendiente)


