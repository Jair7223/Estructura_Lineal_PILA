# Estructura_Lineal_PILA

Programa básico de la función de una pila en estructura de datos creado en el lenguaje C++ 

Iniciamos nuestro programa escribiendo las librerias que ocuparemos para cada función. La primera estructura nos permite hacer uso de lafunción gotoxy para poder presentar en pantalla los letreros que se hayan puesto en el programa desde un punto de la consola. La segunda estructura que es la tipo nodo es necesaria para hacer uso de ella en la pila. La tercera estrcutura es para crear un puntero y poder usarlo al momento de agregar datos a la pila.

![1](https://user-images.githubusercontent.com/72058362/97488108-6856c980-1923-11eb-9710-95c7eaf9a4d2.png)

Creamos una estructura tipo void que nos permite ir agregando los valores que deseamos a la pila. La estructura denominada QUITAR_NUM efectua la acción de ir eliminando el ultimo valor ingresado a nuestra pila. La tercera estructura nos permite mostrar en pantalla los datos ingresado a la pila en orden LIFO.

![2](https://user-images.githubusercontent.com/72058362/97488138-71479b00-1923-11eb-9e35-1d54e86ea635.png)

Para poder hacer uso de las estructuras anteriormente mencionadas se creo un menu de opciones para que el usuario pueda navegar por el programa a su gusto. En la linea 073 se hace mención de una función que nos permité mostrar en pantalla caracteres especiales, tambien se hace uso de la función gotoxy para impirmir en un punto de la consola.

![3](https://user-images.githubusercontent.com/72058362/97488158-7ad10300-1923-11eb-89d1-6c2ae733ddb3.png)

Iniciamos en la funcion principal main creando la pila y declarando algunas variables. Se hace uso de un ciclo repetitivo do-while para poder ir eligiendo las diferentes opciones del menu y en caso de que el usuario desee salir se hace la comparativa para que el programa termine. Se manda a llamar la estructura del menu y se guarda la opción que se desee en la variable op la cual se utiliza para comparar en un ciclo condicional switch dependiendo de la opción que se elija. 

![4](https://user-images.githubusercontent.com/72058362/97488224-8e7c6980-1923-11eb-945e-90b41ede1fdb.png)
![5](https://user-images.githubusercontent.com/72058362/97492227-dd78cd80-1928-11eb-9e61-af45f8fee7c0.png)

----------------------------------------------------------Pruebas en consola---------------------------------------------------------------------

Se presenta el menú de opciones en un punto centrico de la pantalla y se escribe el número de opción que se desee.

![6](https://user-images.githubusercontent.com/72058362/97492520-46f8dc00-1929-11eb-8243-00deb686c56d.png)

Se elige la opcion de insertar número a la pila [1] y te pide la cantidad de números que desea agregar a la pila. 

![7](https://user-images.githubusercontent.com/72058362/97492524-482a0900-1929-11eb-9f8b-98a595f5d4b9.png)

El primer número es el 1

![8](https://user-images.githubusercontent.com/72058362/97492527-48c29f80-1929-11eb-932f-48acd2899625.png)

EL ultimo número añadido es el 5

![9](https://user-images.githubusercontent.com/72058362/97492532-4a8c6300-1929-11eb-84f9-2464be7e2157.png)

Despues de haber añadido 5 números a la pila, el 1 como primer número y el 5 como ultimo hacemos uso de la opcion número [3] que nos permitira presentar la pila en orden LIFO.

![10](https://user-images.githubusercontent.com/72058362/97492489-3e080a80-1929-11eb-8656-2e404a4e90dc.png)
![11](https://user-images.githubusercontent.com/72058362/97492493-4102fb00-1929-11eb-8859-049e0b2d6a4d.png)

Ahora elegimos la opción [2] que nos permitira borrar el ultimo número añadido a la pila, en este caso es el número 5.

![12](https://user-images.githubusercontent.com/72058362/97492497-42342800-1929-11eb-8012-a8e9473aa69f.png)
![13](https://user-images.githubusercontent.com/72058362/97492507-43fdeb80-1929-11eb-8e19-bce9fccbe07f.png)

Como ultima opción, elegimos el número [4] que indica salir el cual sale del ciclo repetitivo do-while y finaliza el programa.

![14](https://user-images.githubusercontent.com/72058362/97492515-452f1880-1929-11eb-90ce-3a3f779b542e.png)
![15](https://user-images.githubusercontent.com/72058362/97492517-45c7af00-1929-11eb-9391-d1ec810a6e08.png)
