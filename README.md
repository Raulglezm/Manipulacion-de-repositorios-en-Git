# Manipulación-de-repositorios-en-Git

![image](https://user-images.githubusercontent.com/91153605/140454717-4a0ca8e9-b5a6-421e-acdf-e7ace54f0587.png)

## Pasos 

### Paso 1

###### 1. El primer comando que utilizaremos es ```git config --global user.name "Your-Full-Name"``` e introduciremos nuestro nombre entre las comillas.
###### 2. Ahora introduciremos el comando ```git config --global user.email "your-email-address"``` y entre las comillas pondremos nuestro gmail.
###### 3. El tercer comando será ```git config --global color.ui auto``` con el que activaremos el coloreado de salida.
###### 4. Con el último comando mostraremos la lista```git config --list```.

![1](https://user-images.githubusercontent.com/91153605/140449663-0536a033-f417-4cee-a133-1336411a6555.PNG)

### Paso 2

###### Crearemos un repositorio con el nombre dpl, para posteriormente mostrar su contenido, para ellos usaremos los comandos: 
###### 1. ```mkdir dpl```
###### 2. ```cd dpl```
###### 3. ```git init```
###### 4. ```ls -la```

![2](https://user-images.githubusercontent.com/91153605/140451056-04c71920-9b43-4471-99a7-4ca74e0f8ccc.PNG)

## Paso 3

###### En este paso comprobaremos el estado del repositorio y crearemos varios ficheros.
###### Para comprobar el estado del repositorio utilizaremos el comando ```git status```.
###### Ahora crearemos un fichero indice.txt usando el comando ```cat > indice.txt``` y dentro del introduciremos: 
###### ```Capítulo 1: Instalación de Git por el alumno XXX```.
###### ```Capítulo 2: Flujo de trabajo básico```.
###### Pulsaremos Ctrl+D para salir.
###### Usaremos de nuevo ```git status```.
###### Añadiremos el ```git indice.txt```.
###### Y finalizaremos con un ```git Status```.

![nueva 3](https://user-images.githubusercontent.com/91153605/140452955-69373dd7-632c-48df-bc84-e9a18e214e7f.PNG)

## Paso 4 

###### En este paso realizaremos un commit de los cambios dejando constancia de lo que hemos hecho.

###### Primero usaremos el comando ```git commit -m "Añadido índice de la asignatura DPL."```.
###### Y finalizaremos con el comando ```git Status```.

![4](https://user-images.githubusercontent.com/91153605/140453324-df87910a-a4d5-4830-ac97-66bc0682f582.PNG)

## Paso 5
###### En este paso modificaremos los ficheros creados anteriormente.
###### Igual que antes introduciremos el comando ```cat > indice.txt``` y dentro del el: 
###### ```Capítulo 1: Instalación de Git por el alumno XXX _(donde XXX es el nombre del alumno)```
###### ```Capítulo 2: Flujo de trabajo básico```
###### ```Capítulo 3: Gestión de ramas```
###### ```Capítulo 4: Repositorios remotos```
###### Ahora cerraremos con ```Ctrl+D```
###### Usaremos ```git diff```
###### Lo siguiente será un ```git add indice.txt```
###### Y para finalizar haremos ```git commit -m "Añadido los capitulos 3 y 4"```

![image](https://user-images.githubusercontent.com/91153605/140454079-539a1570-47c2-4719-8f90-6e23ef106108.png)
![image](https://user-images.githubusercontent.com/91153605/140454108-0ab4f55e-c3b3-4024-a30f-00e2af8056c9.png)

## Paso 6

###### Este es el último paso y en el mostraremos el historial.
###### Primero mostraremos los cambios con el comando ```git show```.
###### Ahora cambiaremos el mensaje del último commit que hemos hecho con el comando ```git commit --amend -m "Añadido el capítulo sobre gestión de ramas al índice."```.
###### Y para finalizar usaremos el comando ```git show``` para ver los cambios.
![6 git show](https://user-images.githubusercontent.com/91153605/140454824-b52aa289-9eba-4afa-a885-92aadbac2696.PNG)
![7 commit](https://user-images.githubusercontent.com/91153605/140454673-91860f9a-c092-4c5e-a3d3-9fe18f60167e.PNG)
![8 show](https://user-images.githubusercontent.com/91153605/140454831-4e50ea00-598f-40c5-a48e-9136bcdd4437.PNG)


