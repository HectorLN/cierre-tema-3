# Cierre Tema 3: Corra los programas de ARM Assembly entregados a su revisión.

Se creo un archibo makefile para facilitar la ejecucion de los programas

```make
compile_file:
	echo "Compiling $(input_file) ..."
	as -o $(input_file).o $(input_file).s
	gcc -o $(input_file) $(input_file).o
	./$(input_file)
  gdb $(input_file)
```

###Programa 1: Delay Example 1
![](./images/delayExample.png)
