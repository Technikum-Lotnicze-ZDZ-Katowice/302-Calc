# 302-Calc

1. ZMIENNE
```js
   let a = "Ala";
```
2. STAŁE
```js
   const b = 3;
   const c = 2;
```
3. FUNKCJE
```js
   function oblicz(){
      let wynik = b + c;
      console.log(wynik)
   }
```
4. SCRIPT
   ```html
   ...
   
      <body>
         <input id="wejscie">
         <button onClick="wypisz()">Wyświetl</button>
         ...
         <script>
            ...
            const wejscie = document.querySelector('#wejscie');

            ...
   
            function wypisz(){
               console.log(wejscie.value)
            }
         <script>
      </body>
   ```

   
ZADANIE 30201

Przygotuj kalkulator.

- pierwszy etap - wybierz liczbę a po kliknięciu "=" wyświetl podwojoną wartość

```html
    <style>
        #rowne{width:80px}
        button{margin:2px;}
        input{width:80px}
    </style>

.....

    <input><br>
    <button>1</button>
    <button>2</button>
    <button>3</button><br>
    <button>4</button>
    <button>5</button>
    <button>6</button><br>
    <button>7</button>
    <button>8</button>
    <button>9</button><br>
    <button>0</button>
    <button>+</button>
    <button>-</button><br>
    <button id="rowne">=</button>

```
