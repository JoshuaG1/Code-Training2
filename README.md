### Code-Training

En el siguiente documento se encuentra de manera detallada la realización de un repositorio en tu directorio local en el que crearemos un código de Python que imprima un mensaje cualquiera, y posteriormente subirlo a GitHub.

**NOTA:** Los directorios locales que se mostrarán en el código de GIT son propios de mi ordenador.

Para fines prácticos imprimiremos el clásico: "Hello World!"

    print("Hello World!")

# Sowftware utilizado
- GIT
- Visual Studio Code
- GitHub

# GIT
Primero crearemos una directorio nuevo con el comando _"mkdir <Nombre_del_directorio>"_, y nos moveremos al mismo con el comando _"cd <Nombre_del_directorio>"_.

![image](https://github.com/JoshuaG1/Code-Training2/assets/76781328/30b7bc2e-eb14-49c1-af1b-c38cd61730e8)
> 1.0. Se crea el directorio "Prueba" y entramos a él.

Como se puede observar en la imagen 1.0, nuestra barra de comandos cambia al movernos al directorio "Prueba", y podemos comprobar que estamos en él cuando nos aparece _~/CICY/Prueba_

Para crear un repositorio en el directorio creado anteriormente usamos el comando _git init_ el cual realiza dicha acción. Nos debe aparecer un mensaje que nos compruebe que se creó un repositorio de Git que se encuentra vacío.

    $ git init
    Initialized empty Git repository in C:/Users/joshu/CICY/Prueba/.git/

Posteriormente usamos el comando _code ._ para que nos abra "Visual Studio Code". Una vez abierto nos aparecerá abierto el directorio "Prueba" que fue el aue creamos en el primer paso, aquí mismo crearemos un archivo de Python que lo llamaremos "_HelloWorld.py_"

![image](https://github.com/JoshuaG1/Code-Training2/assets/76781328/72693143-882e-4262-9823-0b39ac49dbad)
> 1.1.1. Usamos el comando "Code ." que nos abrirá automáticamente el VS Code. Podemos observar que después de crear el repositorio de Git nos aparecerá que nos encontramos en la rama principal _"master"_.

![image](https://github.com/JoshuaG1/Code-Training2/assets/76781328/c6d5a8f5-e850-4eb4-a223-fad48b32ef92)
>1.1.2. Dentro del VS Code creamos un archivo de Python llamado "_HelloWorld.py_"


Dentro del archivo "_HelloWorld.py_" imprimiremos un mensaje cualquiera con el siguiente código:

    print("Hello World!")

Guardamos el archivo con "Ctrl + s" y regresamos a Git. A continuación usaremos el comando _git status_ para ver el estado de los archivos en el directorio de trabajo y en el área de preparación.

![image](https://github.com/JoshuaG1/Code-Training2/assets/76781328/4b5d523c-1cbc-48c7-9916-196b97e4bfdc)
>1.2. El comando *git status* nos muestra el estado del archivo _HelloWorld.py_ en el directorio. El comando *git status -s* muestra el estado de una forma más reducida.

El siguiente paso sería añadir el archivo al área de preparación para después comprometerlo con los comandos *git add <Nombre_del_archivo>* y *git commit -m "Mensaje descriptivo"*, respectivamente.

![image](https://github.com/JoshuaG1/Code-Training2/assets/76781328/17834990-e98b-4a36-bce0-60209deb352a)
>1.3. Añadimos el archivo "HelloWorld.py" al área de trabajo y después lo comprometemos con el mensaje "Commit inicial". Nota: el mensaje puede ser cualquiera, pero que pueda ser entendible para el grupo de colaboradores.

Finalmente, añadimos todos los cambios al repositorio de GitHub con el siguiente comando: "*git remote add origin <link_del_repositorio_de_GitHub>*", y usamos el comando "*git push -u origin master*" para subir los commits desde tu rama (branch) local en tu repositorio git local al repositorio remoto.

![image](https://github.com/JoshuaG1/Code-Training2/assets/76781328/51e7072e-4f2a-43df-90b1-2c3669cc79a1)
>1.4. Subiendo los commits al repositorio de GitHub.

