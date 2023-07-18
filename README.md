Tarea AyP;

Informe:

- Se define la función my_stack que recibe un arreglo arr.
- Se define una lista vacía s que servirá como pila.
- Se recorre cada elemento num del arreglo arr.
- Si la pila está vacía, se inserta el primer elemento.
- Si el elemento num es menor o igual que el último elemento
  de la pila, se inserta en la pila.
- Si el elemento num es mayor que el último elemento de la pila,
  se sacan los elementos de la pila mayores que num y se guardan
  en una lista temporal temp_s. Luego se inserta num en la pila y
  se vuelven a insertar los elementos de temp_s en la pila original
  en orden descendente.
- Al final del ciclo, la función retorna la pila s.
- Se define el arreglo arr y se llama a la función my_stack con este
  arreglo como argumento. El resultado se guarda en la variable stack.
- Finalmente se imprime el contenido de la variable stack.
