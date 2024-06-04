Esto es una pequeña prueba para ver cómo se pueden subir módulos Dagger a Daggerverse.

1. Primero debemos crear un módulo Dagger con "dagger init --sdk=typescript potato".
2. En este módulo añadiremos al menos una función dagger.
3. Después publicamos el módulo en GitHub.
4. A continuación vamos a Daggerverse e introducimos la url de nuestro repositorio. Es muy importante que la introduzcamos sin "https://".
5. Y ya lo tenemos subido. Ahora cualquier persona lo puede descargar o utilizar desde Shell, Go, Python o TypeScript. 

Puedes probarlo tú mismo introduciendo este comando en el shell: "dagger -m github.com/JuanValeraDev/potato@b65461ac7de76c9ff95742ab7be87f80a9dfebc4 call hello-world --count={NÚMERO} --mashed={BOOLEAN} message/from".
*Aclaración*: Puedes poner o no el parámetro de entrada mashed ya que si no lo pones por defecto es false. En cuanto a message y from, son los campos del objeto resultante que queremos solicitar, solo se puede poner uno.

