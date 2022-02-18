# `147.3` ObjectToArray

## 📝 Instrucciones:

1. Escribe una función llamada `convertObjectToList` la cual convierte un objeto literal en una matriz (array de arrays), como este: 

## Ejemplo de entrada 1:

```Js
{
  name: 'Holly',
  age: 35,
  role: 'producer'
}
```

## Ejemplo de salida 1:

```Js
[['name', 'Holly'], ['age', 35], ['role', 'producer']]
```

## 💡 Pistas:

+ Ten en cuenta que tu función debería poder manejar CUALQUIER objeto como este, no solo la muestra exacta proporcionada anteriormente.
Por ejemplo, también debería poder manejar este, o cualquier otro objeto que contenga simples pares key-value (llave-valor):

## Ejemplo entrada 2:

```Js
{
  species: 'canine',
  name: 'Bowser',
  weight: 45
}
```
