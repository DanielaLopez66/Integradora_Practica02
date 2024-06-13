# Integradora Practica02
En está práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones, documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la Asignatura de Integradora I.
## Comandos Básicos para la documentación, utilizando el estándar (md)
Markdown es el estándar utilizado por Git y GitHub, para maquetar la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.
### 1. Encabezados o Titulos (HEADERS)
Para poder realizar una buena documentación del proyecto debemos, distribuir correctametne los contenidos, para poder delimitar o hacer énfasis (enfatizar), es decir, resaltar las secciones importantes, podemos utilizar los siguientes:
# Encabezado de Nivel 1 -Similar a H1 en HTML
## Encabezado de Nivel 2 -Similar a H1 en HTML
### Encabezado de Nivel 3 -Similar a H1 en HTML
#### Encabezado de Nivel 4 -Similar a H1 en HTML
##### Encabezado de Nivel 5 -Similar a H1 en HTML
###### Encabezado de Nivel 6 -Similar a H1 en HTML
####### Encabezado de Nivel 7 -Solo 6 son los niveles permitidos
### 2. Separadores (SEPARATORS)
Si se desea marcar una separación más visual de contenidos podemos utilizarlos indicando 3 caracteres de "-" continuos, en el maquetado.
EJEMPLO:
---
*Esto es similar a un tag de < HR > en HTML.
### 3. Párrafos (PARAGRPANS)
Son utilizados para por presentar grandes sesiones de texto que describen detalladamente las sesiones de la documentación del proyecto. 
EJEMPLO:

Este texto permanece al párrafo 1  Este texto permanece al párrafo 1 Este texto permanece al párrafo 1 Este texto permanece al párrafo 1 Este texto permanece al párrafo 1 Este texto permanece al párrafo 1  Este texto permanece al párrafo 1  Este texto permanece al párrafo 1.

Este texto permanece al párrafo 2  Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2.

Lo que es una página utilizaríamos etiqueta < P >
También podemos aplicar estilos básicos de alineación:

<p align="right">
Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación
<\p>
  
<p align="center">
Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación 
<\p>

<p align="justify">
Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineación
</p>

### 4. Texto Enfatizado (BOLD,ITALIC,BOLD/ITALIC)
Si el texto qué deseamos enfatizar se encuentra en un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación

##### Texto en Negrita (BOLD)
Para poder poner el texto en negrita, este deberá ser encerrado entre dobles *
EJEMPLO:
Texto Texto Texto Texto Texto Importante Texto Texto Texto Texto Texto Texto 

##### Texto en cursiva (ITALIC)
Para poder poner el texto en cursiva, este deberá ser encerrado con la 
Texto Texto Texto Texto <i>Texto Importante</i> Texto Texto Texto Texto Texto Texto


##### Texto en cursiva y negrita(BOLD/ITALIC)
Para poder poner el texto en cursiva y negrita, este deberá ser encerrado con la 
Texto TextoTexto Texto Texto Texto **Texto importante** Texto Texto Texto Texto
**Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto**
~~Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto~~
#### Subrayado (UNDERLINE)
algunas veces necesitaremos subrayar texto dentro de la documentacion, para ello, si bien markdown no tiene atajo o codificacion rapida podemos utilizar el estilo que use el estandar HTML usando tag/<ins> y cerrando con /</ins>.
**EJEMPLO**
TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO

##### Texto subrayado (UNDERLINE) 

Algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML usando el tag \<ins> y cerrando con \</ins>.

Ejemplo:
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto importante*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto importante Texto Texto</ins> Texto Texto Texto Texto Texto 


# Integradora-Practica03

Continuamos con los comandos básicos de Git y Github para el maquetado de la documentación.

### 5. Cuadros para código o Reseñas (BLOCKQUOTES)

  Estos elementos para resaltar instrucciones específicas para la instalación, configuración y/o inicialización o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (\>).
  
  **EJEMPLO:**
  Para listar las carpetas y archivos desde una terminal de sistema operativo Windows debemos ingresar el comando: 

  > C:/dir

Después oprimimos la tecla "enter". 
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

También podemos ingresar textos multilineales

**EJEMPLO:**

>Aquí se ingresa un conjunto de instrucciones
>para explicar al usuario, como instalar el
>software que hemos diseñado.

 Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el caracter 
 -dentro del texto a documentar.

**EJEMPLO**
 **Pasos para instalar la base de datos**
 > - Descargar MySQL Server delsitio oficial
>  - Instalar el SistemaGestor de Base de Datos, definiendo el puerto y contraseña para el usuario ***root***
>  - Descargamos el archivo de respaldo de la base de datos (.sql)
>  - Restauramla Base de Datos usando el comando *mysql *
>> C:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password \< respaldo.sql
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

### 6.Listas Ordenadas y Listas Desordenadas

Si en nuestra documentación necesitamos incluir información en modo de lista, un elemento tras otro podemos hacerlo utilizamos los números con un punto decimal si las deseamos ordenadas o un guión medio - si solo queremos una viñeta.

**EJEMPLO**
Para crear tu primer repositorio en GitHub deberás:
1. Contar con cuenta de GitHub.
1. Dar click en el boton: **Nuevo Repositorio*
2. Asignarle un Nombre a tu repositorio, por ejemplo:  *practicas3-3b*
8. Asignarle un nivel de privacidad entre
   - **Público:** Si quieres que éste disponible para todos los usuarios.
   - **Privado:** Deseas que solo a quien tu decidas puedan ver y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripción llamado : *README.md*
50. Definir si habrá exclusiones de archivo a través de archivo: *.gitignore*
3. Guardar los cambios.  
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

#### 7. Ligas (HIPERVINCULOS)
Las ligas son utilizadas para víncular elementos o referencias delproyecto dentro del mismo repositorio o fuera de él. Y se maquetan utilizando los corchetes \[ \]

**EJEMPLO**
Mi buscador favorito es: [Google](https://www.google.com)
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Pero si deseamos ponersolo lasligas directas o un correo electrónico podemos utilizas los símbolos \< \>

**EJEMPLO**

Documentación creada por: ***Ana Daniela Lopez Neri***

<230415@utxicotepec.edu.mx>

<http://www.utxicotepec.edu.mx>

### 9. Imágenes 
Se puede añadir Imágenes al ingresar en el repositorio, por medio de la opción **Add file** teniendo esto se deberá usar la siguiente ruta:
<\img src=https://\raw.githubusercontent.com/usuario/repositorio/rama/ruta-al-asset/>
**EJEMPLO**
<\img src=https://\raw.githubusercontent.com/Daniela/Integradora02/main/IMG-20240611-WA0113.jpg>
