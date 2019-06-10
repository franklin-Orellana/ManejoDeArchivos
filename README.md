# Manejo De Archivos

**NOMBRE: FRANKLIN ORELLANA **

**CARRERA: COMPUTACIÓN**

**MATERIA: PROGRAMACIÓN APLICADA**

**PRACTICA N° 6**

**OBJETIVO ALCANZADO**

El objetivo alcanzado de esta practica fue interpretar mediante una interfaz grafica el manejo de archivos, creado, renombrando

y eliminando archivos a la vez poderlos manipular y obtener informacion como en la ruta en la que se encuentra, la modificacion que tubo 

y el tamaño de dicho directorio, archivo y archivos ocultos.

**ACTIVIDADES DESARROLLADAS**

**1.- CREAR UN REPOSITORIO EN GITHUB**

![1](https://user-images.githubusercontent.com/49034691/59171762-33698d00-8b0a-11e9-89f8-47e514104ac0.PNG)

**2.-SINCRONIZAR EL REPOSITORIO CREADO CON UN PROYECTO EN NETBEANS Y REAIZA UN COMIT Y PUSH POR CADA REQUERIMIENTO PEDIDO EN LA GUIA DE

PRACTICA(INCLUIR MENSAJES QUE IDENTIFIQUE CLARAMENTE LOS COMMITS REALIZADOS EN GITHUB).**

  - Se realizo 5 commits, a continuacion se mostraran mediante una imagen.
  
![2](https://user-images.githubusercontent.com/49034691/59171964-27ca9600-8b0b-11e9-8e54-8d8f0a6764e8.PNG)

**3.- CREAR UN NUEVO PROYECTO EN NETBEANS**

  - A continuacion se indicara la creacion del nuevo proyecto.
  
![3](https://user-images.githubusercontent.com/49034691/59172047-8e4fb400-8b0b-11e9-9eff-faac79ca8c88.PNG)

**4.- CREAR UN PAQUETE**

  - Se creo un paquete con el nombre ec.edu.ups.vista
  
![4](https://user-images.githubusercontent.com/49034691/59172108-eedef100-8b0b-11e9-9d6b-fc9ef77c12bc.PNG)

**5.- CREAR UNA NUEVA CLASE PARA LA INTERFAZ GRAFICA**

  - Se procedio ah crear una clase con el nombre Principal para gnerar la interfaz grafica
  
![5](https://user-images.githubusercontent.com/49034691/59172227-8a706180-8b0c-11e9-823d-583a4e6a799d.PNG)

**6.- CREACION DE INTERFAZ GRAFICA**

  - S implemento dos menus para Archivo y Carpeta
    
    - Crear
    
    - Renombrar
    
    - Eliminar

  - Se implemento tres botones 
    
    - LISTAR: Nos mostrara los directorios, archivos y archivos ocultos en los JList.
    
    - REGRESAR: Al momento de ingresar a varias carpetas nos ayudara a regresar a las carpetas anteriores.
    
    - SALIR: Saldra del programa totalmente
    
  - Se implemento 3 JList para que nos imprima todos los Directorios, Archivos y Archivos Ocultos
    
  - Se implemento Jlabel para que nos devuelva los datos de los de los Directoios, Archivos y Archivos Ocultos
    
    - Ruta
    
    - Modificacion
    
    - Tamaño
    
![6](https://user-images.githubusercontent.com/49034691/59172832-be00bb00-8b0f-11e9-8b28-9ff79553c4a5.PNG)

**7.- INDICACIONES DEL CODIGO**

  - En el siguiente codigo se indicara el momento que se ingresa la ruta en la caja de texto nos mostrara toda la informacion 
  
  en los JList y asi poder hacer las modificaciones necesarias.
  
![7](https://user-images.githubusercontent.com/49034691/59173538-e9d17000-8b12-11e9-9ee1-b4980a936fb8.PNG)

![8](https://user-images.githubusercontent.com/49034691/59173671-a7f4f980-8b13-11e9-9e76-8f56cf04eac7.PNG)

  -  En el siguiente codigo crearemos un nuevo archivo asi designando la ruta en la que deseemos que se encuentre, al momento
  
  de crear un archivo nos saldra una pantalla indicandonos que ingresemos el nombre del archivo y finalmente nos devolvera un mensaje
  
  diciendonos que el archivo se ah creado y nos mostrara automaticamente en la lista.
  
![9](https://user-images.githubusercontent.com/49034691/59173932-c8718380-8b14-11e9-8dc3-fa4457174eef.PNG)

![10](https://user-images.githubusercontent.com/49034691/59174083-70874c80-8b15-11e9-84f6-9a4acebf3556.PNG)

![11](https://user-images.githubusercontent.com/49034691/59174085-70874c80-8b15-11e9-9596-a2912f2e3f4d.PNG)

![12](https://user-images.githubusercontent.com/49034691/59174086-70874c80-8b15-11e9-84a7-8d4ecc1e5bb5.PNG)

  - De igual manera se trabajo con el renombrar nos pedira que señalemos el archivo que queramos renombrar y nos saldra una pantalla
  
  que ingresemos el nuevo nombre una vez modificado nos devolvera una pantalla avisandonos que el archivo se ah modificado.
  
![15](https://user-images.githubusercontent.com/49034691/59174290-5e59de00-8b16-11e9-8848-31e8bb81d944.PNG)

![16](https://user-images.githubusercontent.com/49034691/59174292-5e59de00-8b16-11e9-900b-913c09d096e9.PNG)

![13](https://user-images.githubusercontent.com/49034691/59174293-5e59de00-8b16-11e9-9b64-7751884eb761.PNG)

![14](https://user-images.githubusercontent.com/49034691/59174294-5ef27480-8b16-11e9-8652-1114e51eca2a.PNG)

  - Y por ultimo el eliminar archivos nos pedira que señalemos el archivo que deseemos eliminar y nos devolvera un mensaje
  
  diciendonos que el archivo ah sido eliminado y se quetara automaticamente del Jlist sin tener volver a listar los JList.
  
![18](https://user-images.githubusercontent.com/49034691/59174402-d7f1cc00-8b16-11e9-8467-3bee5f990730.PNG)

![17](https://user-images.githubusercontent.com/49034691/59174403-d7f1cc00-8b16-11e9-8975-fbb8fe321c5d.PNG)

  - Para poder ingresar ah cada carpeta se implemento un evento al JList llamado mouseClicked el cual nos ayudara a ingresar a 
  
  cualquier carpeta y nos dejara manipularla a nuestro gusto cabe recalcar que al momento de querer eliminar una carpeta
  
  que este dentro de otra carpeta primero debemos asegurarnos que no tengo ningun contenido dentro ya que no nos dejara elimanarla.
  
![21](https://user-images.githubusercontent.com/49034691/59174635-b6451480-8b17-11e9-91f2-0ce18d842df7.PNG)

![22](https://user-images.githubusercontent.com/49034691/59174636-b6ddab00-8b17-11e9-9a6c-8107129392ae.PNG)

![19](https://user-images.githubusercontent.com/49034691/59174638-b6ddab00-8b17-11e9-92d5-dded7d390971.PNG)

![20](https://user-images.githubusercontent.com/49034691/59174639-b6ddab00-8b17-11e9-940f-b705ea06eaf1.PNG)

  - Se creo un boton regresar el cual nos ira regresando a la ruta o carpeta que deseemos.
  
![23](https://user-images.githubusercontent.com/49034691/59174721-20f65000-8b18-11e9-95f9-0bb8ef37d357.PNG)

![24](https://user-images.githubusercontent.com/49034691/59174719-205db980-8b18-11e9-8e7d-16c04ffc7591.PNG)
  
![25](https://user-images.githubusercontent.com/49034691/59174720-205db980-8b18-11e9-914b-7dd4ec87efd8.PNG)

**CONCLUSIONES**

Se puede decir que el manejo de directores nos ayuda a controlar y manipular archivos a nuestro gusto mediante rutas,

a la vez se supo interpretar el uso del File en java y a la vez la creacion de carpetas, archivos y renombrar a nuestro

gusto, cabe recalcar que al momento de eliminar archivos o carpetas no se podran recuperar de ninguna manera.

**RECOMENDACIONES**

Trabajar con directores de prueba ya que al momento de realizar pruebas del eliminar no se podra recuperar la informacion

que se elimino en ese momento.

**GITHUB**

  - Usuario: franklin-Orellana
  
  -Repositorio: https://github.com/franklin-Orellana/ManejoDeArchivos






 
