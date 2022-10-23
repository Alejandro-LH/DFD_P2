# Presentacion 
## Problemas resueltos en clase con DFD
### Ejercicio 1. Contar del 1 hasta el 10 y sumar los valores. (FOR)
#### 1.1 Analisis. 
Sumar los valores del 1 al 10.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197370994-6bed5c67-531c-4b90-b360-dcf3b6189313.png)
#### 1.3 Prueba de escritorio
|s|i|i<=10|s=s+i|i++|Salida|
|-|-|-|-|-|-|
|0|1|1<=10|0+1|1+1||
|1|2|2<=10|1+2|2+1||
|3|3|3<=10|3+3|3+1||
|6|4|4<=10|6+4|4+1||
|10|5|5<=10|10+5|5+1||
|15|6|6<=10|15+6|6+1||
|21|7|7<=10|21+7|7+1||
|28|8|8<=10|28+8|8+1||
|36|9|9<=10|36+9|9+1||
|45|10|10<=10|45+10|10+1|55|
#### 1.4 Entradas.
No tiene ninguna entrada.
#### 1.5 Salidas.
55.
#### 1.6 Codigo.

### Ejercicio 2. Contar del 1 hasta el 10 y sumar los valores. (WHILE)
#### 1.1 Analisis. 
Sumar los valores del 1 al 10.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197401601-6bc0d83e-df63-4273-ad29-1fccf8e1cf54.png)
#### 1.3 Prueba de escritorio 
|s|c|c<=10|s=s+c|c=c++|Salida|
|-|-|-|-|-|-|
|0|1|1<=10|0+1|1+1||
|1|2|2<=10|1+2|2+1||
|3|3|3<=10|3+3|3+1||
|6|4|4<=10|6+4|4+1||
|10|5|5<=10|10+5|5+1||
|15|6|6<=10|15+6|6+1||
|21|7|7<=10|21+7|7+1||
|28|8|8<=10|28+8|8+1||
|36|9|9<=10|36+9|9+1||
|45|10|10<=10|45+10|10+1|55|
#### 1.4 Entradas.
No tiene ninguna entrada.
#### 1.5 Salidas.
55.
#### 1.6 Codigo.

### Ejercicio 3. Contar del 1 hasta el 10 y sumar los valores. (DO-WHILE)
#### 1.1 Analisis. 
Sumar los valores del 1 al 10.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197401840-390bcb1a-f2cb-4799-8c83-3978dd0ee754.png)
#### 1.3 Prueba de escritorio 
|s|c|s=s+c|c=c++|c<=10|Salida|
|-|-|-|-|-|-|
|0|1|0+1|1+1|2<=10||
|1|2|1+2|2+1|3<=10||
|3|3|3+3|3+1|4<=10||
|6|4|6+4|4+1|5<=10||
|10|5|10+5|5+1|6<=10||
|15|6|15+6|6+1|7<=10||
|21|7|21+7|7+1|8<=10||
|28|8|28+8|8+1|9<=10||
|36|9|36+9|9+1|10<=10||
|45|10|45+10|10+1||55|
#### 1.4 Entradas.
No tiene ninguna entrada.
#### 1.5 Salidas.
55.
#### 1.6 Codigo.

### Ejercicio 4. Obtenga la suma de los primeros 5 numeros pares. (FOR)
#### 1.1 Analisis. 
Sumar los numeros pares del 1 al 10.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197371049-0a3fe20e-11ef-4136-94b4-0d2ad7275bc2.png)
#### 1.3 Prueba de escritorio 
|s|i|i<=5|s=s+ i * 2|i++|salida|
|-|-|-|-|-|-|
|0|1|1<=5|0+ 1 * 2|1+1||
|2|2|2<=5|2+ 2 * 2|2+1||
|6|3|3<=5|6+ 3 * 2|3+1||
|12|4|4<=5|12+ 4 * 2|4+1||
|20|5|5<=5|20+ 5 * 2|5+1|30|
#### 1.4 Entradas.
No tiene ninguna entrada.
#### 1.5 Salidas.
30.
#### 1.6 Codigo.

### Ejercicio 5. Obtenga la suma de los primeros 5 numeros pares. (WHILE)
#### 1.1 Analisis.
Sumar los numeros pares del 1 al 10.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197402064-570cad02-fbe8-4d55-bdfc-3c025b1e2286.png)
#### 1.3 Prueba de escritorio 
|s|c|c<=5|s=s+ i * 2|c++|salida|
|-|-|-|-|-|-|
|0|1|1<=5|0+ 1 * 2|1+1||
|2|2|2<=5|2+ 2 * 2|2+1||
|6|3|3<=5|6+ 3 * 2|3+1||
|12|4|4<=5|12+ 4 * 2|4+1||
|20|5|5<=5|20+ 5 * 2|5+1|30|
#### 1.4 Entradas.
No tiene ninguna entrada.
#### 1.5 Salidas.
30.
#### 1.6 Codigo.

### Ejercicio 6. Obtenga la suma de los primeros 5 numeros pares. (DO-WHILE)
#### 1.1 Analisis.
Sumar los numeros pares del 1 al 10.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197402096-75bf182b-69be-40bc-b2b7-95e5d353861c.png)
#### 1.3 Prueba de escritorio 
|s|c|s=s+ i * 2|c++|c<=5|salida|
|-|-|-|-|-|-|
|0|1|0+ 1 * 2|1+1|1<=5||
|2|2|2+ 2 * 2|2+1|2<=5||
|6|3|6+ 3 * 2|3+1|3<=5||
|12|4|12+ 4 * 2|4+1|4<=5||
|20|5|20+ 5 * 2|5+1|5<=5|30|
#### 1.4 Entradas.
No tiene ninguna entrada.
#### 1.5 Salidas.
30.
#### 1.6 Codigo.

### Ejercicio 7. Almacene en un array el numero n leido del teclado, el tamaño del array es de 10. (FOR)
#### 1.1 Analisis. 
Debemos almacenar en 10 espacios el numero n.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197402229-8076c2bc-525f-445e-8f57-468b827f1eeb.png)
#### 1.3 Prueba de escritorio 
|n|i|i<=9|A[i]=n|i++|
|-|-|-|-|-|
|4|0|0<=9|A[0]=4|0+1|
|4|1|1<=9|A[1]=4|1+1|
|4|2|2<=9|A[2]=4|2+1|
|4|3|3<=9|A[3]=4|3+1|
|4|4|4<=9|A[4]=4|4+1|
|4|5|5<=9|A[5]=4|5+1|
|4|6|6<=9|A[6]=4|6+1|
|4|7|7<=9|A[7]=4|7+1|
|4|8|8<=9|A[8]=4|8+1|
|4|9|9<=9|A[9]=4|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 8. Almacene en un array el numero n leido del teclado, el tamaño del array es de 10. (WHILE)
#### 1.1 Analisis. 
Debemos almacenar en 10 espacios el numero n.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197402293-bd4cc849-581f-4e8c-8638-5a9776826320.png)
#### 1.3 Prueba de escritorio 
|n|c|c<=9|A[c]=n|c++|
|-|-|-|-|-|
|7|0|0<=9|A[0]=7|0+1|
|7|1|1<=9|A[1]=7|1+1|
|7|2|2<=9|A[2]=7|2+1|
|7|3|3<=9|A[3]=7|3+1|
|7|4|4<=9|A[4]=7|4+1|
|7|5|5<=9|A[5]=7|5+1|
|7|6|6<=9|A[6]=7|6+1|
|7|7|7<=9|A[7]=7|7+1|
|7|8|8<=9|A[8]=7|8+1|
|7|9|9<=9|A[9]=7|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 9. Almacene en un array el numero n leido del teclado, el tamaño del array es de 10. (DO-WHILE)
#### 1.1 Analisis. 
Debemos almacenar en 10 espacios el numero n.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197402325-1e3f53a4-fba0-4296-9012-44f6f9550e39.png)
#### 1.3 Prueba de escritorio 
|n|c|A[c]=n|c++|c<=9|
|-|-|-|-|-|
|5|0|0<=9|0+1|A[0]=5|
|5|1|1<=9|1+1|A[1]=5|
|5|2|2<=9|2+1|A[2]=5|
|5|3|3<=9|3+1|A[3]=5|
|5|4|4<=9|4+1|A[4]=5|
|5|5|5<=9|5+1|A[5]=5|
|5|6|6<=9|6+1|A[6]=5|
|5|7|7<=9|7+1|A[7]=5|
|5|8|8<=9|8+1|A[8]=5|
|5|9|9<=9|9+1|A[9]=5|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 10. Almacene los n numeros leidos del teclado en un vector de 10 elementos. (FOR)
#### 1.1 Analisis. 
Almacenar en 10 espacios diferentes numeros leidos del teclado.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197371156-4295ab1d-e995-4f38-8338-0bdcdac36c00.png)
#### 1.3 Prueba de escritorio 
|i|i<=9|n|A[i]=n|i+1|
|-|-|-|-|-|
|0|0<=9|6|A[0]=6|0+1|
|1|1<=9|4|A[1]=4|1+1|
|2|2<=9|8|A[2]=8|2+1|
|3|3<=9|1|A[3]=1|3+1|
|4|4<=9|4|A[4]=4|4+1|
|5|5<=9|9|A[5]=9|5+1|
|6|6<=9|2|A[6]=2|6+1|
|7|7<=9|4|A[7]=4|7+1|
|8|8<=9|3|A[8]=3|8+1|
|9|9<=9|5|A[9]=5|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 11. Almacene los n numeros leidos del teclado en un vector de 10 elementos. (WHILE)
#### 1.1 Analisis. 
Almacenar en 10 espacios diferentes numeros leidos del teclado.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197402477-524b88d2-dcec-414e-8015-489a0de963db.png)
#### 1.3 Prueba de escritorio 
|c|c<=9|n|A[c]=n|c+1|
|-|-|-|-|-|
|0|0<=9|4|A[0]=4|0+1|
|1|1<=9|8|A[1]=8|1+1|
|2|2<=9|9|A[2]=9|2+1|
|3|3<=9|2|A[3]=2|3+1|
|4|4<=9|4|A[4]=4|4+1|
|5|5<=9|6|A[5]=6|5+1|
|6|6<=9|1|A[6]=1|6+1|
|7|7<=9|8|A[7]=8|7+1|
|8|8<=9|7|A[8]=7|8+1|
|9|9<=9|9|A[9]=9|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 12. Almacene los n numeros leidos del teclado en un vector de 10 elementos. (DO-WHILE)
#### 1.1 Analisis. 
Almacenar en 10 espacios diferentes numeros leidos del teclado.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197371175-558b3ef9-2356-4e74-a604-807d2867d513.png)
#### 1.3 Prueba de escritorio 
|c|n|A[c]=n|c+1|c<=9|
|-|-|-|-|-|
|0|4|A[0]=4|0+1|0<=9|
|1|8|A[1]=8|1+1|1<=9|
|2|9|A[2]=9|2+1|2<=9|
|3|2|A[3]=2|3+1|3<=9|
|4|4|A[4]=4|4+1|4<=9|
|5|6|A[5]=6|5+1|5<=9|
|6|1|A[6]=1|6+1|6<=9|
|7|8|A[7]=8|7+1|7<=9|
|8|7|A[8]=7|8+1|8<=9|
|9|9|A[9]=9|9+1||
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 13. Almacene un contador negativo en un vector, el conteo es de 10 a 0. (FOR)
#### 1.1 Analisis. 
Almacenar en 10 espacios un conteo regresivo del 10 al 0.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197371211-333c3251-eb1f-40f0-b149-1e12870d3be7.png)
#### 1.3 Prueba de escritorio 
|i|i>=0|A[10-i]=i|i--|
|-|-|-|-|
|10|10>=0|A[10-10]=0|10-1|
|9|9>=0|A[10-9]=1|9-1|
|8|8>=0|A[10-8]=2|8-1|
|7|7>=0|A[10-7]=3|7-1|
|6|6>=0|A[10-6]=4|6-1|
|5|5>=0|A[10-5]=5|5-1|
|4|4>=0|A[10-4]=6|4-1|
|3|3>=0|A[10-3]=7|3-1|
|2|2>=0|A[10-2]=8|2-1|
|1|1>=0|A[10-1]=9|1-1|
|0|0>=0|A[10-0]=10||
#### 1.4 Entradas.
No tiene entradas.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 14. Almacene un contador negativo en un vector, el conteo es de 10 a 0. (WHILE)
#### 1.1 Analisis. 
Almacenar en 10 espacios un conteo regresivo del 10 al 0.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197371228-81f5620c-c430-441a-914d-b95e89cc8838.png)
#### 1.3 Prueba de escritorio 
|c|c>=0|A[10-c]=c|c--|
|-|-|-|-|
|10|10>=0|A[10-10]=0|10-1|
|9|9>=0|A[10-9]=1|9-1|
|8|8>=0|A[10-8]=2|8-1|
|7|7>=0|A[10-7]=3|7-1|
|6|6>=0|A[10-6]=4|6-1|
|5|5>=0|A[10-5]=5|5-1|
|4|4>=0|A[10-4]=6|4-1|
|3|3>=0|A[10-3]=7|3-1|
|2|2>=0|A[10-2]=8|2-1|
|1|1>=0|A[10-1]=9|1-1|
|0|0>=0|A[10-0]=10||
#### 1.4 Entradas.
No tiene entradas.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 15. Almacene un contador negativo en un vector, el conteo es de 10 a 0. (DO-WHILE)
#### 1.1 Analisis. Almacenar en 10 espacios un conteo regresivo del 10 al 0.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197371239-9fe9c118-5a89-4bca-bb07-d322d9e11e9b.png)
#### 1.3 Prueba de escritorio 
|c|A[10-c]=c|c--|c>=0|
|-|-|-|-|
|10|A[10-10]=0|10-1|10>=0|
|9|A[10-9]=1|9-1|9>=0|
|8|A[10-8]=2|8-1|8>=0|
|7|A[10-7]=3|7-1|7>=0|
|6|A[10-6]=4|6-1|6>=0|
|5|A[10-5]=5|5-1|5>=0|
|4|A[10-4]=6|4-1|4>=0|
|3|A[10-3]=7|3-1|3>=0|
|2|A[10-2]=8|2-1|2>=0|
|1|A[10-1]=9|1-1|1>=0|
|0|A[10-0]=10||0>=0|
#### 1.4 Entradas.
No tiene entradas.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 16. Almacene en un vector de tamaño 10, todos los numeros pares capturados hasta completar todos. (FOR)
#### 1.1 Analisis. 
Tenemos que insertar numero pares y almacenarlos en 10 espacios.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197382216-7f05339c-b12f-4d84-9978-8caa04a7534f.png)
#### 1.3 Prueba de escritorio 
|i|i<=9|n|n%2==0|A[i]=n|i+1|
|0|0<=9|8|8%2==0|A[0]=8|0+1|
|1|1<=9|4|4%2==0|A[1]=n|1+1|
|2|2<=9|2|2%2==0|A[2]=n|2+1|
|3|3<=9|8|8%2==0|A[3]=n|3+1|
|4|4<=9|2|4%2==0|A[4]=n|4+1|
|5|5<=9|6|6%2==0|A[5]=n|5+1|
|6|6<=9|6|6%2==0|A[6]=n|6+1|
|7|7<=9|2|2%2==0|A[7]=n|7+1|
|8|8<=9|4|4%2==0|A[8]=n|8+1|
|9|9<=9|4|4%2==0|A[9]=n|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 17. Almacene en un vector de tamaño 10, todos los numeros pares capturados hasta completar todos. (WHILE)
#### 1.1 Analisis. 
Tenemos que insertar numero pares y almacenarlos en 10 espacios.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197382230-a9f1f438-30d8-44c4-9d04-78c41acc7111.png)
#### 1.3 Prueba de escritorio 
|c|c<=9|n|n%2==0|A[c]=n|c+1|
|0|0<=9|8|8%2==0|A[0]=8|0+1|
|1|1<=9|4|4%2==0|A[1]=n|1+1|
|2|2<=9|2|2%2==0|A[2]=n|2+1|
|3|3<=9|8|8%2==0|A[3]=n|3+1|
|4|4<=9|2|4%2==0|A[4]=n|4+1|
|5|5<=9|6|6%2==0|A[5]=n|5+1|
|6|6<=9|6|6%2==0|A[6]=n|6+1|
|7|7<=9|2|2%2==0|A[7]=n|7+1|
|8|8<=9|4|4%2==0|A[8]=n|8+1|
|9|9<=9|4|4%2==0|A[9]=n|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 18. Almacene en un vector de tamaño 10, todos los numeros pares capturados hasta completar todos. (DO-WHILE)
#### 1.1 Analisis. 
Tenemos que insertar numero pares y almacenarlos en 10 espacios.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197382249-ea63e694-11ef-47fc-bf5b-5f4173ad7766.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 19. Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación entre 0 y 10 y el maximo de alumnos es de 15. (FOR)
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 20. Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación entre 0 y 10 y el maximo de alumnos es de 15. (WHILE)
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 21. Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación entre 0 y 10 y el maximo de alumnos es de 15. (DO-WHILE)
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 22. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 23. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 24. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 25. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 26. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 27. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 28. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 29. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 30. 
#### 1.1 Analisis. 
#### 1.2 DFD
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.
