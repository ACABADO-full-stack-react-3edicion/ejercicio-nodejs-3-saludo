## Ejercicio 3 Node.js - Saludo

1. Clona el directorio base para hacer una nueva aplicación. La nueva aplicación recogerá un parámetro llamado nombre desde la línea de comandos, y guardará un saludo en un archivo de texto. En los siguientes puntos tienes el funcionamiento detallado. El uso de esta aplicación será así:
   `node index --nombre=Marius`
2. Crea un archivo index.js y dos carpetas. La primera llámala utilidades y crea dentro un archivo llamado archivos.js; la segunda llámala textos y déjala vacía.
3. En utilidades/archivos.js crea una función guardarSaludo que reciba un string con un nombre y no devuelva nada. Esta función debe guardar un string "Hola, nombre. Encantado de saludarte." dentro de un archivo llamado saludo.txt dentro de la carpeta textos. Si el archivo no existe, debe crearse, y si existe, se machacará su contenido por el nuevo.
4. Si la operación da error, hay que comunicarlo por consola en un mensaje rojo y en negrita, y abortar el programa.
5. Exporta la función guardarSaludo.
6. En index.js comprueba si se ha enviado un parámetro --nombre por la consola. Si no se ha enviado, debe comunicarlo por consola en amarillo y abortar la ejecución del programa.
7. Si se ha enviado un parámetro --nombre con su valor correspondiente, entonces llama (desde index.js) a la función guardarSaludo pasándole el nombre recibido.
8. Comprueba que el archivo se ha creado y que el saludo se ha guardado correctamente en su interior.
