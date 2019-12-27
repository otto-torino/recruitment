# Javascript

## Che differenza c'è tra `var`, `let` e `const`?
## Cos'è il DOM?
## Qual è la differenza tra queste due espressioni?

    myFunction(++i);
    myFunction(i++);

## Esistono modificatori di accesso alle proprietà di un oggetto in javascript? Si possono creare proprietà private in un oggetto javascript?
## Cos'è una closure? Sai fare un esempio?
## A cosa può servire la seguente funzione?

    var myfunc = function (fn, context) {
      return function () {
          return fn.apply(context, arguments);
      }
    }

## Cos'è una `Promise`? Quali problemi permette di risolvere? Quali altri modi mette a disposizione javascript per risolvere problemi analoghi?
## Scrivi una funzione che si comporti in modo da rispettare gli output seguenti:

    console.log(multiply(2,3));	// Outputs 6
    console.log(multiply(2)(3));	// Outputs 6
