# Hello world javascript action

Esta acción escribe "Hola Mundo" o "Hola" + el nombre de una persona para que salude al registro.

## Entradas

### `who-to-greet`

**Requerido:** El nombre de la persona a saludar. Por defecto: `"World"`.

## Salidas

### `time`

La hora en la que te saludamos

## Ejemplo de uso
```js
uses: ULL-ESIT-PL-2021/hello-js-action-EduardoEB3@v1

with:
  who-to-greet: 'Mona the Octocat'
```