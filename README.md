# Moodle-Config
### 1- *Configuración del curso y nuestro usuario*
Modificamos los datos que saldran en nuestro perfil de moodle.
![User](1.png)
Debemos de ponerle nombre al curso, completando todas las casillas obligatorias.
![User](2.png)
### 2- *Configuraremos el idioma y la configuración visual de Moodle*
![Preferences](3.png)
Añadimos el tamaño de la contraseña a **4 caracteres** en la configuración del curso para que se necesite ponerla al intentar entrar en el curso.
![Preferences](4.png)

Vamos a crear 2 cursos, uno con el nombre A y otro con el nombre B selecionando el boton de color azul ***Crear Curso*** .

![Cursos](4.1.png)

Dentro del curso **A** cambiaremos el nombre de 3 temas
Dentro del curso **B** cambiaremos el nombre a 5 temas
![Temas](3.1.png)
![Cursos](5.1.png)

Y de esta manera podemos tener nuestros propios temas para el curso.
#### + Añadir una actividad o un recurso
Dentro del curso **A** vamos a añadirle 2 PDF en forma de tarea para cada **TEMA** al cual le hemos cambiado el nombre.
![Curso](100.png)
![Curso](101.png)
### 3- *Añadir usuarios y asignar roles*
Vamos a entrar en el apartado:
#### Administración del sitio --> Usuarios --> General 
Lo llamaremos Bob, añadiendole una contraseña.
![Curso](102.png)
Vamos a Descargar datos de tabla como Valores separados por comas **(.csv)**
![Curso](103.png)
Una vez lo descargemos vamos a ir a la carpeta en la cual se ha **DESCARGADO** el archivo y lo vamos a modificar metiendonos dentro del bloc de notas que usemos.
Vamos a copiar lo que sale en la imagen de abajo dentro de las notas
![Curso](104.png)

#### Entraremos en la administración del sitio --> Cuentas --> Subir usuarios
Vamos a importar el archivo (.csv)
![Curso](105.png)

Si lo hemos hecho bien nos saldran todos los usuarios de manera correcta talcual se ve en las imagenes

![Curso](106.png)

Vamos a borrar 2 usuarios.

![Curso](108.png)

![Curso](107.png)

Primero nos vamos a dirigir a el curso **A** y **B** vamos a configurar que absolutamente nadie se pueda inscribir al curso
Vamos a irnos a los metodos de matriculación

#### Participantes --> Métodos de matriculación

![Curso](109.png)

![Curso](110.png)

Vamos a irnos a los metodos de matriculación

#### Participantes --> Métodos de matriculación
Nos vamos a asegurar de que este activada la matriculación manual **(tenemos el ojo sin tachar)**
![Curso](111.png)

#### Nos dirijiremos al curso B y matricularemos a los usuarios añadiendo los cuales hicimos en el bloc de notas. Tambien añadiremos a Bob como profesor.


![Curso](112.png)
#### Participantes --> Usuarios matriculados --> *Matricular usuarios*
![Curso](113.png)

Hacemos que bob sea profesor de los cursos **A** y **B** y añadimos a los 8 usuarios que tenemos
![Curso](114.png)
![Curso](119.png)
![Cursos](118.png)

Entramos al curso **A** para hacer una tarea con **PDF**, nos vamos a dirigir a una tema y seleccionaremos:
#### + Añadir una actividad o un recurso
Y lo configuraremos de esta manera siguiendo los pasos

![Curso](35.png)

![Curso](37.png)

# Tareas y UF
Vamos a crear 2 Unidades Formativas en las cuales añadiremos 2 NF
#### + Añadir una actividad o un recurso
Seleccionaremos **Area de texto y medios**

![Curso](02.png)

Le pondremos el nombre de NF1 y NF2

![Curso](04.png)

![Curso](01.png)
![Curso](05.png)

### Seleccionaremos Actividad --> Tareas
Y la crearemos

![Curso](07.png)
![Curso](08.png)

Una vez este creada nos meteremos como alumno y entregaremos la tarea

### Usuarios --> Student Eight --> Entrar como

![Curso](300.png)

![Curso](10.png)
![Curso](11.png)

Una vez entregada vamos a volver a dirigirnos a nuestro perfil de profesor cerrando sesion y entrando al perfil para poder evaluar la tarea que nuestro alumno ha enviado.

### Boton azul (Calificar)

![Curso](12.png)

Ahora si nos dirigimos al apartado de calificaciones podemos ver que ese alumno tendra un **100%** en el curso ya que solo tenemos como nota la actividad.

![Curso](13.png)

# Insignias
El primer paso sera dirigirnos a 

#### Administración del sitio --> Insignias (en la barra de busqueda)
![Curso](14.png)

Gestion de insignias
![Curso](15.png)

Vamos a seleccionar el boton azul de **Añadir una nueva insignia**
![Curso](16.png)

Cuando se nos despliegue el menu vamos a poner el **Nombre** la **Descripción** y la **Imagen**

![Curso](17.png)

Vamos a poner que el criterio en **Concesión manual por rol**

![Curso](22.png)

#### Marcamos la casilla de ✅*Profesor*

![Curso](23.png)

Cuando ya terminemos de hacerla se la asignaremos a una persona (en este caso debe de ser a un profesor porque anteriormente marcamos que lo sea)

![Curso](24.png)

Vamos a **Habilitar acceso**

![Curso](25.png)

#### Habilitar

Cuando nos salga este menu deberemos de **Otorgar insignia** a una persona

![Curso](26.png)

En el panel de la derecha seleccionaremos a **bob bob** 

#### Otorgar insignia
![Curso](27.png)

Y ya podremos ver que nuestro profesor **bob** tiene la insignia asignada

![Curso](28.png)

## Cuestionarios y examenes

Vamos a volver al curso **A**

![Curso](4.1.png)

Y dentro del NF que queramos vamos a hacer

#### + Añadir una actividad o un recurso

![Curso](201.png)

#### Actividades --> Cuestionario

Seleccionaremos el nombre que queramos

![Curso](202.png)
![Curso](203.png)

#### Agregar pregunta

Vamos a seleccionar la puntuación que queramos en nuestro **EXAMEN** *(en este caso he puesto 10)*

![Curso](204.png)

Vamos a seleccionar ✅**Opciones multiples**

![Curso](205.png)

*Podemos agregar todas las preguntas que deseemos*

Agregamos el titulo de nuestra pregunta y el enunciado que les saldra a nuestros alumnos

![Curso](207.png)

Y pondremos todas las opciones que queramos en **Eleccion x** y en **Calificación** pondremos el % que queremos que cueste la respuesta al responderla

![Curso](208.png)

## Exportar copia de seguridad y cursos
*En proceso*





## Seguridad

Vamosa a banear una IP, para que tenga prohibido entrar a las clases, esto sirve para garantizar una buena seguridad a nuestro curso, de esta manera los banearemos de forma manual.

Nos dirijimos a 

#### Administración del sitio --> Seguridad --> Bloqueador de IP

![Curso](500.png)

Y en **Lista de IPs bloquedas** ponemos la ip la cual no va a poder acceder a nuestros cursos.

![Curso](501.png)

**Guardar cambios**











