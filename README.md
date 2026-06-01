# Int1-Practica02-250900"
---
En esta practica aprenderemos a utilizar la sherramientas Git y Github para el control de versiones de proyecto de desarrollo de software, aplicando principios de buena practica
en documentos , desarrollo colaborativo y respaldo en la nube del proyecto integrador

Elaborado por: **Leslie YAriveth Tellez Ortega**\

Materia: **Proyecto Integrador**\

Docente: **M.T.Z. Marcco Antonio Ramirez Hernandez**\

Periodo: **Marzo - Agosto 2026*  \

---

## comando basicos para maqutado de la documentacion utilizando el estandar de Markdown (.md)

---

Markdown es el estandar utilizando Git Github para estilizar (maquetar) la documentacion de proyecto entender el contexto y operacion del mismo

### 1. Encabezados o titulos (HEADERS)

Para poder realiza una buena documentacion del proyecto debemos distribuir correctamente los contenidos para poder delimitar o hacer enfasis (enfatizar) es decir resaltar las secciones mas importantes, podemos utilizar lo siguiente:

**EJEMPLO**

# Encabezado de nivel 1
## encabezado de nivel 2
### encabezado de nivel 3
#### encabezado de nivel 4
##### encabezado de nivel 5
###### encabezado de nivel 6
####### encabezado de nivel 7 -  *El estandar solo permite 6 niveles para titulos, a partir del septimo seran presentado como texto plano (sin estilo)*

### 2. separadores (SEPATORS) 

Si se desea marcar una separacion visual de los contenidos podemos utilizar una linea horizontal indicando tres caracteres - continuos, en el maquetado 

**EJEMPLO**

### Titulo de la seccion
---
parrafo 1: este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 

parrafo 2:este texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2, el estandar de markdown distingue los parrafos 

en caso de quue necesitemos alinear el parrafo a **izquierda**, **derecha**, **central** o **justificar** deberemos utilizar una etiqueta <p> con la propiedad align y direccion deseada

<p align="left"> parrafo alineado parrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineado
<p align="center"> parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro 

<p align="right"> parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha 

<p align="justify"> parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado 

### 4. Enfatizado de Texto

- Texto en negritas: Para resaltar texto importante que no sea un titulo por  questo inicialmente estan el éstan en negrita, deberemos encerrar el texto deseado entre dos asteríscos simples(*).

Ejemplo: Este *texto* estará *inclinado*.

- Texto en Cursiva y Negrita: Para lograr esta estilización en la documentación basta con juntar ambas configuraciones, es decir encerramos el texto en un triple asterísco (***)

Ejemplo ***Este texto esta Negrito e Itálico.***

- Texto Tachado: En aslgunas ocaciones es necesario dar dformato en un efecto de como es incorrecto, generalmente esta idea se transmite porque el texto esta tachado, es decir con una linea que lo marca por la mitad. Para logar este efecto tendremos que encerrar el texto en una doble tilde de (~).

Ejemplo se dice haya no ~~haiga~~.

-Texto Subrayado: En este tipo de formato el texto queda sobre una linea inferior para denotar su relevancia , este formato no tiene una version rapida en el estandar MARKDOWN, pero dado su similiaridad a HTML podemos utilizar las etiquetas ```<u>```y```</u>```.

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

- Texto en Super Indice: En algunas ocaciones se requiere dar formato a fórmulas estadísticas que requiere potencias entre otras aplicaciones, podemos utilizar en tag en HTML ```<sup>```y```</sup>``` para delimitar el formato.

Ejemplo: Para elevar x al cuadrado tendriamos lo siguiente: x <sup>2</sup>

- Texto en Subindice: En el caso de quimica se utilizan subindicies para representar formulas, para ello podemos utilizar el formato de texto con la etiqueta HTML ```<sub>```y```</sub>```.

Ejemplo: La formula del Agua es H<sub>2</sub>0.

### 5. Listas

Cuando realizamos documentación utilizando el estándar de MARKDOWN, es común que tengamos que listar elementos, requisitos de hardware, requisitos de software o enumerar pasos de como el software debe ser instalado paso a paso, por eso debemos saber como creas listas de las cuales hay de 3 tipos: **Ordenadas (numeros)**, **Desordenas(Viñetas)** y **Mixtas(viñetas y numeros)**.

1. Listas Ordenadas.

Estas deberán estar enumeradas con un número seguido por un punto y un espacio en blanco para comenzar con el listado.

1. PC
2. Wifi
3. Modém
4. Smartphone 
6. Smart TV
5. Tablet

Para reiniciar el contenido se debe poner una linea de texto sin numeralia.

2.  Listas Desordenadas.

 Estas listas no llevan un numero, si no una viñeta (simbolo), y suele listar elementos que no requieren un orde especifico.

-Pan
-Leche
-Huevo
-Arroz

3. Listas Mixtas.

Son aquellas que mezclan ambos elementos.
- 3° A DSM
1. Juan
2. Pedro
3. Alejandro
- 3° B DSM
1. Romina
2. Daniel
3. Pablo
- 3° C DSM
1. Leslie
2. Paola
3. Jovo

### 6. Bloques de Código (CODE BLOCKS) O Citas (BLOCK QUOTES)

Estos estilos de texto se utilizan para llamar la atencion del ector, en pasos que son importantes, rrealizarv alguna reseña o segmentar lineas de codigo que se deberan ingresar en una terminal de comandos o lineas de ejecucion.

- cuadros de citas (Block Quotes)
Son cajas estilizadas en colores frisees por defecto con un marfen mas claro.

Ejemplo:

Para listar las carpetas y archivosd de una terminal de comandos del sitema operativo de Windows debemos usar el comando:

>C: /dir

Despues opimimos la tecla *enter*.

Tambien podemos usar texto multitarea

Ejemplo :

> - descargar el archivo instalado desde la pagina oficial www.mysql.com
> - instalar el servidor de base de datos
> - definir el puerto y contraseña para el usuario **root**
> - inicializar el servidor de base de datos
> - conectarnos a la base de datos para verificar que se instalo corectamente

- Bloques de codigo

Es comun que en la documentacion del proyecto de software demos eal usuario un par de instruccioones de como instalar, configurar, desplegar y testear(purebas), nuestro producto desarrollado . Por tal motivo el estándar markdown nos permite enfatizar estas instrucciones, simulando estar en una terminal de sitema operativo, para delimitar este codigo basta encerrarlo en triples caractewres de bacltic (acento o tilde inversa ``` ` ```)

Ejemplo: 

Para clonar el proyecto ingresa la siguiente instrucción 
C:\Users\PC-04\Desktop>git clone https://github.com/250683-less/int1-Practica1_250683

A diferencias de los bloques de citas, la tipografia y asociado cambian.

### 7. Tablas

En caso de que necesitemos estructurar datoso informacion relevante para la documentación podremos utilizar el formato de tablas, para lo que tenemos que considerar la estructura base de una tabla:

- Usa | para delimitar columnas
- usa --- para separar las filas del encabezado

Ejemplo:

|Título 1 |Título 2 | Título 3 |Título 4 |
|---|---|---|---|
|Fila 1, Celda 1 |Fila 1, Celda 2 |Fila 1, Celda 3 |Fila 1, Celda 4 |
|Fila 2, Celda 1 |Fila 2, Celda 2 |Fila 2, Celda 3 |Fila 2, Celda 4 |
|Fila 3, Celda 1 |Fila 3, Celda 2 |Fila 3, Celda 3 |Fila 3, Celda 4 |

