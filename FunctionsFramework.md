# Functions Framework

## Crear un nuevo directorio
```bash
mkdir testff ; cd testff
```

## Crear un nuevo proyecto
```bash
npm init
```

## Agregar Modulo "Functions Framework"
```bash
npm install @google-cloud/functions-framework
```

## Copiar ejemplo de servidor web en "Functions Framework"
```bash
cp ../index.js .
```

## Abrir index.js
<walkthrough-editor-open-file filePath="./FunctionsFramework/testff/index.js"
                              text="Abrir index.js">
</walkthrough-editor-open-file>


## Modificar package.json

Debemos agregar el comando para arrancar "Functions Framework" (el equivalente "node index.js" en el ejercicio anterior)

<walkthrough-editor-open-file filePath="./FunctionsFramework/testff/package.json"
                              text="Abrir package.json">
</walkthrough-editor-open-file>

Esto lo podemos hacer modificando directamente el package.json para que quede asi:

  "scripts": {
    "start": "functions-framework --target=helloWorld"
  }

Puedes mirar el "package.json" que viene con este ejercicio.
<walkthrough-editor-open-file filePath="./FunctionsFramework/package.json"
                              text="Abrir package.json">
</walkthrough-editor-open-file>

ATENCION: Respetar la sintaxis de JSON, la estructura anterior se encuentra despues de una coma y finaliza con una coma.

Tambien puedes copiar el package.json que viene con este ejercicio, ejecutando el siguiente comando.

```bash
cp ../package.json .
```
