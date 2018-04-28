# busqueda-binaria-analisis
Se hace el análisis de la búsqueda binaria y el porque la búsqueda binaria es O(logn).


"Divide y venceras", al tener una lista ordenada, buscamos el elemento en la mitad de la lista. Con ello si es el resultado es el buscado ya lo habremos hallado, sino buscamos en la mitad de la lista, logicamente ya tenemos una lista cada vez más pequeña para nuestra búsqueda, si repetimos el proceso, la lista será cada vez más pequeña.

Es decir, tenemos:

Si n = tamaño de lista

Comparaciones	      Número aproximado de ítems restantes
--------------------------------------------------
  1	                n/2
  2	                n/4
  3	                n/8
  ...	 
  i	                n/2^i
  
  Cuando dividimos la lista lo suficiente, tenemos al final solo un elemento, con ello el tamaño de la lista es igual a 1.
  
  Es decir, al final de las comparaciones tenemos:
  
  i al final de las comparaciones = 1      =>     n/2^i =1  
  
  Entonces para hallar el valor de i, matemáticamente tenemos:
  
  =>     i  =   log⁡ n/log 2 
  
  Por lo tanto, la búsqueda binaria es O(log n). 

  
  



