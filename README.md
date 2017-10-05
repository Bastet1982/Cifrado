#### Cifrado césar y ASCII, encriptar y desencriptar.

__Inicio__ 

+ Crear un nuevo archivo html y otro de javascript.

+ Vincular ambos archivos por medio de script scr, en el index.

 __CODIGO__

 - En mi archivo js generar un prompt() que dirá "Ingrese la frase".

```javascript
    var question = prompt("Ingrese su frase");
```

 - Si frase es == a ( " " || numbers), retornará un error

 Si el prompt(), no me arroja error me pedirá elegir como quiero el encriptamiento de la frase, cipher o decipher.
   

 - Debo crear 2 funciones, una llamada cipher que debe cifrar la frase ingresada ,y la segunda llamada decipher, debe entregar una frase descifrada.

 - La funcion cipher debe permitir que la letra inicial de la frase se mueva una cantidad de espacios determinados y así sucesivamente con el resto

 ```javascript
 (x - 65 + n + 52) %26+ 65 --> para mayusculas
 (x - 65 + n + 78) %26 + 65---> para minusculas





 



