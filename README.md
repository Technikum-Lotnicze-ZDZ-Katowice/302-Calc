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
5. Instrukcje warunikowe

```js

        if(c == 30) {
            console.log('jest równe 30')
        } else {
            console.log('nie jest równe 30')
        }

// ternary operator

        c == 30 ? console.log('rowne w ternary') : console.log('nie jest rowne 30')
```

6. Instrukcja switch
```js
      let wiek = 25;

        switch(wiek){
            case 18:
                console.log('nie możesz głosować');
            break;
            case 19:
            case 20:
            case 21:
            case 22:
                console.log('możesz głosować');
            break;
            default:
                console.log('inny wiek niż wymienione');
        }
```

7.Tablice

```js
         const tablica = [];

         const tablica2 = ['pierwszy','drugi',3,4,['a','b','c']]

        console.log(tablica2[2]) // odwołanie do 2 elementu (liczone od 0)

        console.log('ile elementów',tablica2.length)

        tablica.push('dodany'); // dodawanie elementów

        console.log(tablica2.length)
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

