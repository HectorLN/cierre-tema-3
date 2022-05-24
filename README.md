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

![delayExample](https://user-images.githubusercontent.com/95378364/169946909-a0d1b584-1d05-4efe-a27a-cd826eb4720f.png)

###Programa 2: Div9entre3

![dib9entre3](https://user-images.githubusercontent.com/95378364/169947017-02b704d4-1f72-4603-9a73-83d5a37d9b7c.png)

###Programa 3: hanoi

![hanoi](https://user-images.githubusercontent.com/95378364/169947059-2beac699-4c21-4b88-91bf-e6f632c5755e.png)

###Programa 4: primero

![primero](https://user-images.githubusercontent.com/95378364/169947085-222bb2e2-4416-4057-b11f-a604bd23f0aa.png)

###Programa 5: ScanFexample1

![sacnFexample1](https://user-images.githubusercontent.com/95378364/169947517-faa4e4e4-83b8-4b71-ad5c-cffac9a9e4a7.png)

###Programa 6: Stack

![stack](https://user-images.githubusercontent.com/95378364/169947552-c91ab681-de4d-4c88-b1b9-83c509916886.png)

###Programa 7: Sum2

![sum2](https://user-images.githubusercontent.com/95378364/169947583-4a83b559-a3b7-4d1b-8220-e4ee22138057.png)

###Programa 8: Sum3

![sum3](https://user-images.githubusercontent.com/95378364/169947624-28bf5acb-9cbf-45e0-a0fc-90733f61b92d.png)


###Conclusion
La practica en si fue muy sencilla, solo teniamos que hacer el make file y correr todos los programas, cabe destacar que no todos los programas corrieron correctamente en el gdb y solo se mostraron los que si se pusieron correr



