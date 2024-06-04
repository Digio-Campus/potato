Esto es una pequeña prueba para ver cómo se pueden subir módulos Dagger a Daggerverse.

1. Primero debemos crear un módulo Dagger con "dagger init --sdk=typescript potato".
2. En este módulo añadiremos al menos una función dagger.
3. Después publicamos el módulo en GitHub.
4. A continuación vamos a Daggerverse e introducimos la url de nuestro repositorio. Es muy importante que la introduzcamos sin "https://".
5. Y ya lo tenemos subido. Ahora cualquier persona lo puede descargar o utilizar desde Shell, Go, Python o TypeScript. 

Puedes probarlo tú mismo introduciendo este comando en el shell: "dagger -m github.com/Digio-Campus/potato@d63946b2d8c13d10382b17737069049e6b084b88 call hello-world --count={NÚMERO} --mashed={BOOLEAN} message/from".
*Aclaraciones*: 
1. Puedes poner o no el parámetro de entrada mashed ya que si no lo pones por defecto es false. En cuanto a message y from, son los campos del objeto resultante que queremos solicitar, solo se puede poner uno.
2. En el shell llamamos a la función hello-world en lugar de helloWorld porque cuando llamamos a "dagger call ..." las funciones utilizan nombrado de tipo kebab-case.

