Sergi Aragall
Victor Rojas
Alberto Camacho

Para empezar:
El makefile se encuentra ubicado en la carpeta src del proyecto. Dispone de las siguientes opciones
    make: Compila los archivos necesarios para su ejecución.
    make run: Ejecuta la aplicación.
    make clean: Elimina todos los .class generados. 

Funcionamiento de la aplicación
Generador de horarios 2.0.1 dispone de un menu superior con 2 opciones principales:
    *Cargar escenario: Con esta opción actualizas la ventana donde aparecerán las funciones básicas de nuestra aplicación:
        -Crear nuevo escenario: Creara un escenario vacio y lo cargará en memoria, es decir, nose guardará hasta que se genere un horario.


        -Cargar escenario: Abrira una ventana donde podrás seleccionar un escenario para modificarlo o generar horario.


        -Modificar escenario: Este boton no funcionará hasta que hayas cargado un escenario o cargado uno nuevo. Este boton abrirá una ventana donde podrás editar las  distintas caracteristicas del escenario. Cada Caracteristica cuenta con un boton para añadir o eliminar las distinta spartes del escenario. Tener en cuenta que el escenario se guardará al generar un horario que haga uso de el.


        -Generar horario: Este boton no funcionará hasta que se haya creado o cargado un escenario.
    
    *Cargar horario: Con esta opcion se abrirá una ventana donde podrás escoger algún horario guardado para cargar en memoria. Tener en cuenta que también cargará el escenario al que esta vinculado.
