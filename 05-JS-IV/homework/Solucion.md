1. Los objetos son un conjuto de propiedades que se caracterizan por tener una clave y un valor, las claves en los objetos son únicas pero
   varias claves pueden tener valores iguales. Clave: valor. Un objeto puede tener cualquier tipo de valor, desde un string hasta un array
   hasta un mismo objeto o una función.

2. una propiedad es un conjunto de Clave: valor para definir en los objetos.
   Ej: Nombre(clave): Jose(valor).

3. Los metodos son funciones que hemos guardado dentro de los objetos como un valor y que llamamos por medio del . (como hacemos por ejemplo
   con el metodo array.length).
   Ej: nombreObjeto.metodo()

4. Un bucle es repetir o recorer varias veces lo mismo, en este caso, con el bucle for...in recoreremos cada clave del objeto hasta acabar de
   recorrer todas las claves que tenga el objeto.
   Ej: for(let clave in usuario){}

5. Tenemos varias formas de llamar o acceder a los valores que tenga nuestro objeto, usando la notación de puntos o la de corchetes.
   Ej: nombreObjeto.Clave (notación de punto) ó nombreObjeto['Clave'] (notación de corchete). Al usar la notación de corchete debemos poner
   o una cadena por lo cual debemos usar comillas '' o un número o una variable en la cual esté guardado la clave
   Ej2: var nuevaClave = 'Clave'; .......... nombreObjeto[nuevaClave];
