# trabajo-practico-01--2026
¿Qué diferencia existe entre JavaScript, V8 y el runtime de Node.js?

 JavaScript es un lenguaje de programacion que se ejecuta en un entorno de navegador web, nacio 
 lenguaje para ejecutarse en aplicacion cliente- servidor del lado del cliente. Nos permite interactuar con paginas web.
 node:Se creo como una alternativa para ejecutar codigo de javaScript desde otro entorno.
 son dos entornos diferentes.
 v8: es ell motor de interpretacion de javaScript que permite la ejecucion del lenguaje en el navegador.
 (LA DEFINICION V8 LA ACABO DE GOOGLEAR NO LO SABIA, LAS OTRAS EN CLASE)

  ¿Cuál es la diferencia general entre I/O bloqueante y no bloqueante
  Bloqueante: Describe lo que va a hacer el hilo principal durante la espera mientras se realiza la E/S.
  Indica que mientras se este trabajando en una E/S no se puede hacer otra cosa, te lo bloquea.

  No bloqueante:se puede hacer la operacion pero en paralelo al que se realiza esa operacion E/S, lo liero al hilo para que siga ejecutando as sentencias que sigan en la cola.
   
   Dos forma de leer archivo:
   Bloqueante: readFilesync
   No bloqueando: readFile

   ¿Qué responsabilidades cumplen node:path y node:fs en index.js ?
   node:fs - File System (Sistema de archivos) Sirve para crear,leer, modificar y eliminar o carpetas.
   mkdirSync: para crear una operacion bloqueante.

   path - Rutas:
   Sirve para trabajar con las rutas de archivos y carpetas.
   writeFileSync: para crear el archivo donde va a estar la ficha de los videojuego y tambien como una operacion bloqueante.
