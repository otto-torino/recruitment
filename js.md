# Javascript

1.  Che differenza c'è tra `var`, `let` e `const`?
2.  Cos'è il DOM?
3.  Cosa cambia invocando la funzione `myFunction` in questi modi?

    ```
    myFunction(++i);
    myFunction(i++);
    ```

4. Esistono modificatori di accesso alle proprietà di un oggetto in javascript? Si possono creare proprietà private in un oggetto javascript?
5. Cos'è una closure? Sai fare un esempio?
6. A cosa può servire la seguente funzione?

    ```
    var myfunc = function (fn, context) {
      return function () {
          return fn.apply(context, arguments);
      }
    }
    ```

7. Cos'è una `Promise`? Quali problemi permette di risolvere? Quali altri modi mette a disposizione javascript per risolvere problemi analoghi?
8. Scrivi una funzione che si comporti in modo da rispettare gli output seguenti:

    ```
    console.log(multiply(2,3));	// Outputs 6
    console.log(multiply(2)(3));	// Outputs 6
    ```
