# Presentacion 
## Problemas resueltos en clase con DFD
### Ejercicio 1 Contar del 1 hasta el 10 y sumar los valores. (FOR)
#### 1.1 Analisis. 
contar del 1 al 10 en una condicion de termino y sumarlos en un proceso.
#### 1.2 DFD
![1 (for)](https://user-images.githubusercontent.com/113395327/197660653-0f384b1e-6c99-4a26-8613-03f91649be32.png)
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
    
### Ejercicio 1 Contar del 1 hasta el 10 y sumar los valores. (WHILE)
#### 1.1 Analisis. 
Utilizar un proceso para las variables de suma y contados, despues con una condicion validar la suma de los valores del 1 al 10.
#### 1.2 DFD
![1 (While)](https://user-images.githubusercontent.com/113395327/197660681-49bfc8f7-5ed8-49f0-988d-490046d78f77.png)
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

### Ejercicio 1 Contar del 1 hasta el 10 y sumar los valores. (DO-WHILE)
#### 1.1 Analisis. 
En Utilizar un proceso para las varibles de contador y suma, despues con otro proceso hacer la suma, y luego el contador para validar las veces 
#### 1.2 DFD
![1 (Do-While)](https://user-images.githubusercontent.com/113395327/197660698-c39d7d57-68ec-4d22-b9dc-0f7546518bfd.png)
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

### Ejercicio 2 Obtenga la suma de los primeros 5 numeros pares. (FOR)
#### 1.1 Analisis. 
Sumar los numeros pares del 1 al 10.
#### 1.2 DFD
![2 (for)](https://user-images.githubusercontent.com/113395327/197660736-9a97e4f3-b28f-404a-9f6d-fd035279e3b0.png)
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

### Ejercicio 2 Obtenga la suma de los primeros 5 numeros pares. (WHILE)
#### 1.1 Analisis.
Sumar los numeros pares del 1 al 10.
#### 1.2 DFD
![2 (While)](https://user-images.githubusercontent.com/113395327/197660764-11511194-e0b1-4a00-aae3-68b54143865d.png)
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

### Ejercicio 2 Obtenga la suma de los primeros 5 numeros pares. (DO-WHILE)
#### 1.1 Analisis.
Sumar los numeros pares del 1 al 10.
#### 1.2 DFD
![2 (Do-While)](https://user-images.githubusercontent.com/113395327/197660837-9c64bda6-9519-44c1-b2ae-735a8ee688c1.png)
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

### Ejercicio 3 Almacene en un array el numero n leido del teclado, el tamaño del array es de 10. (FOR)
#### 1.1 Analisis. 
Debemos almacenar en 10 espacios el numero n.
#### 1.2 DFD
![3 (for)](https://user-images.githubusercontent.com/113395327/197660869-62d12335-0cbe-471c-87e0-1b17ae9c1cf6.png)
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

### Ejercicio 3 Almacene en un array el numero n leido del teclado, el tamaño del array es de 10. (WHILE)
#### 1.1 Analisis. 
Debemos almacenar en 10 espacios el numero n.
#### 1.2 DFD
![3 (While)](https://user-images.githubusercontent.com/113395327/197660901-d4ae6f43-b708-4ab3-9157-f1160f8b80af.png)
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

### Ejercicio 3 Almacene en un array el numero n leido del teclado, el tamaño del array es de 10. (DO-WHILE)
#### 1.1 Analisis. 
Debemos almacenar en 10 espacios el numero n.
#### 1.2 DFD
![3 (Do-While)](https://user-images.githubusercontent.com/113395327/197660916-b013d497-3144-4e52-a095-cefebc079a15.png)
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

### Ejercicio 4 Almacene los n numeros leidos del teclado en un vector de 10 elementos. (FOR)
#### 1.1 Analisis. 
Almacenar en 10 espacios diferentes numeros leidos del teclado.
#### 1.2 DFD
![4 (for)](https://user-images.githubusercontent.com/113395327/197660974-b31154a6-6d29-4622-815a-8f9d47ea0af1.png)
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

### Ejercicio 4 Almacene los n numeros leidos del teclado en un vector de 10 elementos. (WHILE)
#### 1.1 Analisis. 
Almacenar en 10 espacios diferentes numeros leidos del teclado.
#### 1.2 DFD
![4 (While)](https://user-images.githubusercontent.com/113395327/197661015-dfd2ed45-979d-4fe4-a6bb-a96e2114497e.png)
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

### Ejercicio 4 Almacene los n numeros leidos del teclado en un vector de 10 elementos. (DO-WHILE)
#### 1.1 Analisis. 
Almacenar en 10 espacios diferentes numeros leidos del teclado.
#### 1.2 DFD
![4 (Do-While)](https://user-images.githubusercontent.com/113395327/197661041-c8b0f699-fc49-4158-aa3a-0135523b7921.png)
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

### Ejercicio 5 Almacene un contador negativo en un vector, el conteo es de 10 a 0. (FOR)
#### 1.1 Analisis. 
Almacenar en 10 espacios un conteo regresivo del 10 al 0.
#### 1.2 DFD
![5 (for)](https://user-images.githubusercontent.com/113395327/197661066-18a0fe4e-25fa-49df-bd17-369867a17e66.png)
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

### Ejercicio 5 Almacene un contador negativo en un vector, el conteo es de 10 a 0. (WHILE)
#### 1.1 Analisis. 
Almacenar en 10 espacios un conteo regresivo del 10 al 0.
#### 1.2 DFD
![5 (While)](https://user-images.githubusercontent.com/113395327/197661093-1e30accc-8788-4e69-99fa-6ae602d16809.png)
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

### Ejercicio 5 Almacene un contador negativo en un vector, el conteo es de 10 a 0. (DO-WHILE)
#### 1.1 Analisis. Almacenar en 10 espacios un conteo regresivo del 10 al 0.
#### 1.2 DFD
![5 (Do-While)](https://user-images.githubusercontent.com/113395327/197661111-4c8e2d90-88c6-4952-a8f8-ebe2f856e4ad.png)

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

### Ejercicio 6 Almacene en un vector de tamaño 10, todos los numeros pares capturados hasta completar todos. (FOR)
#### 1.1 Analisis. 
Tenemos que insertar numero pares y almacenarlos en 10 espacios.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197382216-7f05339c-b12f-4d84-9978-8caa04a7534f.png)
#### 1.3 Prueba de escritorio 
|i|i<=9|n|n%2==0|A[i]=n|i+1|
|-|-|-|-|-|-|
|0|0<=9|8|8%2==0|A[0]=8|0+1|
|1|1<=9|4|4%2==0|A[1]=4|1+1|
|2|2<=9|2|2%2==0|A[2]=2|2+1|
|3|3<=9|8|8%2==0|A[3]=8|3+1|
|4|4<=9|2|4%2==0|A[4]=2|4+1|
|5|5<=9|6|6%2==0|A[5]=6|5+1|
|6|6<=9|6|6%2==0|A[6]=6|6+1|
|7|7<=9|2|2%2==0|A[7]=2|7+1|
|8|8<=9|4|4%2==0|A[8]=4|8+1|
|9|9<=9|4|4%2==0|A[9]=4|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 6 Almacene en un vector de tamaño 10, todos los numeros pares capturados hasta completar todos. (WHILE)
#### 1.1 Analisis. 
Tenemos que insertar numero pares y almacenarlos en 10 espacios.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197382230-a9f1f438-30d8-44c4-9d04-78c41acc7111.png)
#### 1.3 Prueba de escritorio 
|c|c<=9|n|n%2==0|A[c]=n|c+1|
|-|-|-|-|-|-|
|0|0<=9|2|8%2==0|A[0]=2|0+1|
|1|1<=9|4|4%2==0|A[1]=4|1+1|
|2|2<=9|6|2%2==0|A[2]=6|2+1|
|3|3<=9|8|8%2==0|A[3]=8|3+1|
|4|4<=9|2|4%2==0|A[4]=2|4+1|
|5|5<=9|4|6%2==0|A[5]=4|5+1|
|6|6<=9|6|6%2==0|A[6]=6|6+1|
|7|7<=9|8|2%2==0|A[7]=8|7+1|
|8|8<=9|2|4%2==0|A[8]=2|8+1|
|9|9<=9|4|4%2==0|A[9]=4|9+1|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 6 Almacene en un vector de tamaño 10, todos los numeros pares capturados hasta completar todos. (DO-WHILE)
#### 1.1 Analisis. 
Tenemos que insertar numero pares y almacenarlos en 10 espacios.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197382249-ea63e694-11ef-47fc-bf5b-5f4173ad7766.png)
#### 1.3 Prueba de escritorio 
|c|n|n%2==0|A[c]=n|c+1|c<=9|
|-|-|-|-|-|-|
|0|2|8%2==0|A[0]=2|0+1|0<=9|
|1|2|4%2==0|A[1]=2|1+1|1<=9|
|2|4|2%2==0|A[2]=4|2+1|2<=9|
|3|4|8%2==0|A[3]=4|3+1|3<=9|
|4|6|4%2==0|A[4]=6|4+1|4<=9|
|5|6|6%2==0|A[5]=6|5+1|5<=9|
|6|8|6%2==0|A[6]=8|6+1|6<=9|
|7|8|2%2==0|A[7]=8|7+1|7<=9|
|8|2|4%2==0|A[8]=2|8+1|8<=9|
|9|2|4%2==0|A[9]=2|9+1|9<=9|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
#### 1.6 Codigo.

### Ejercicio 7 Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación entre 0 y 10 y el maximo de alumnos es de 15. (FOR)
#### 1.1 Analisis.
Sumar las calificaiones de los alumnos aprobados y sacarles el promedio, despues contar la cantidad de reprobados mayores a 5.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197411505-2a259b71-368e-4ae0-8399-d6c445b9b111.png)
#### 1.3 Prueba de escritorio 
|i|i<=14|Cal|Cal>=LI|Cal<=LS|A[i]=Cal|i+1|Cal<5|S_A=S_A+Cal|C_A=C_A+1|C_R++|P_A=S_A/C_A|P_A|C_R|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|0|0<=14|7|7>=0|7<=10|A[0]=7|0+1|7<5|0+7|0+1|||||
|1|1<=14|6|6>=0|6<=10|A[1]=6|1+1|6<5|7+6|1+1|||||
|2|2<=14|3|3>=0|3<=10|A[2]=3|2+1||||0+1||||
|3|3<=14|9|9>=0|9<=10|A[3]=9|3+1|9<5|13+9|2+1|||||
|4|4<=14|9|9>=0|9<=10|A[4]=9|4+1|9<5|22+9|3+1|||||
|5|5<=14|10|10>=0|10<=10|A[5]=10|5+1|10<5|31+10|4+1|||||
|6|6<=14|5|5>=0|5<=10|A[6]=5|6+1||||1+1||||
|7|7<=14|10|10>=0|10<=10|A[7]=10|7+1|10<5|41+10|5+1|||||
|8|8<=14|8|8>=0|8<=10|A[8]=8|8+1|8<5|51+8|6+1|||||
|9|9<=14|7|7>=0|7<=10|A[9]=7|9+1|7<5|59+7|7+1|||||
|10|10<=14|9|9>=0|9<=10|A[10]=9|10+1|9<5|66+9|8+1|||||
|11|11<=14|4|4>=0|4<=10|A[11]=4|11+1||||2+1||||
|12|12<=14|10|10>=0|10<=10|A[12]=10|12+1|10<5|75+10|9+1|||||
|13|13<=14|9|9>=0|9<=10|A[13]=9|13+1|9<5|85+9|10+1|||||
|14|14<=14|8|8>=0|8<=10|A[14]=8|14+1|8<5|94+8|11+1||P_A=102/12|8.5|3|
#### 1.4 Entradas.
Cal.
#### 1.5 Salidas.
P_A; C_R.
#### 1.6 Codigo.

### Ejercicio 7 Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación entre 0 y 10 y el maximo de alumnos es de 15. (WHILE)
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197417109-b6f776ed-9408-4a55-ab89-fb0fe7bf07c2.png)
#### 1.3 Prueba de escritorio 
|C_Almn|C_Almn<=14|Cal|Cal>=LI|Cal<=LS|A[i]=Cal|i+1|Cal<5|S_A=S_A+Cal|C_A=C_A+1|C_R++|P_A=S_A/C_A|P_A|C_R|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|0|0<=14|6|6>=0|6<=10|A[0]=6|0+1|6<5|0+6|0+1|||||
|1|1<=14|6|6>=0|6<=10|A[1]=6|1+1|6<5|7+6|1+1|||||
|2|2<=14|2|2>=0|2<=10|A[2]=2|2+1||||0+1||||
|3|3<=14|4|4>=0|4<=10|A[3]=4|3+1||||1+1||||
|4|4<=14|9|9>=0|9<=10|A[4]=9|4+1|9<5|22+9|3+1|||||
|5|5<=14|10|10>=0|10<=10|A[5]=10|5+1|10<5|31+10|4+1|||||
|6|6<=14|5|5>=0|5<=10|A[6]=5|6+1||||1+1||||
|7|7<=14|3|3>=0|3<=10|A[7]=3|7+1||||2+1||||
|8|8<=14|8|8>=0|8<=10|A[8]=8|8+1|8<5|51+8|6+1|||||
|9|9<=14|7|7>=0|7<=10|A[9]=7|9+1|7<5|59+7|7+1|||||
|10|10<=14|9|9>=0|9<=10|A[10]=9|10+1|9<5|66+9|8+1|||||
|11|11<=14|4|4>=0|4<=10|A[11]=4|11+1||||2+1||||
|12|12<=14|10|10>=0|10<=10|A[12]=10|12+1|10<5|75+10|9+1|||||
|13|13<=14|9|9>=0|9<=10|A[13]=9|13+1|9<5|85+9|10+1|||||
|14|14<=14|8|8>=0|8<=10|A[14]=8|14+1|8<5|94+8|11+1||P_A=102/12|8.5|3|
#### 1.4 Entradas.
Cal.
#### 1.5 Salidas.
P_A; C_R.
#### 1.6 Codigo.

### Ejercicio 7 Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación entre 0 y 10 y el maximo de alumnos es de 15. (DO-WHILE)
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197417134-8b3fa286-832c-4ac4-a678-80d6132d225d.png)
#### 1.3 Prueba de escritorio 
|C_Almn|Cal|Cal>=LI|Cal<=LS|A[i]=Cal|i++|Cal<5|S_A=S_A+Cal|C_A=C_A+1|C_R++|C_Almn<=14|P_A=S_A/C_A|P_A|C_R|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|0|6|6>=0|6<=10|A[0]=6|0+1|6<5|0+6|0+1||1<=14||||
|1|4|4>=0|4<=10|A[1]=4|1+1||||0+1|2<=14||||
|2|9|9>=0|9<=10|A[2]=9|2+1|9<5|6+9|1+1||3<=14||||
|3|5|5>=0|5<=10|A[3]=5|3+1||||1+1|4<=14||||
|4|8|8>=0|8<=10|A[4]=8|4+1|8<5|15+8|2+1||5<=14||||
|5|4|4>=0|4<=10|A[5]=4|5+1||||2+1|6<=14||||
|6|7|7>=0|7<=10|A[6]=7|6+1|7<5|23+7|3+1||7<=14||||
|7|2|2>=0|2<=10|A[7]=2|7+1||||3+1|8<=14||||
|8|9|9>=0|9<=10|A[8]=9|8+1|9<5|30+9|4+1||9<=14||||
|9|1|1>=0|1<=10|A[9]=1|9+1||||4+1|10<=14||||
|10|10|10>=0|10<=10|A[10]=10|10+1|10<5|39+10|5+1||11<=14||||
|11|4|4>=0|4<=10|A[11]=4|11+1||||5+1|12<=14||||
|12|9|9>=0|9<=10|A[12]=9|12+1|9<5|49+9|6+1||13<=14||||
|13|5|5>=0|5<=10|A[13]=5|13+1||||6+1|14<=14||||
|14|9|9>=0|9<=10|A[14]=9|14+1|9<5|58+9|7+1|||P_A=67/8|8.3|7|
#### 1.4 Entradas.
Cal.
#### 1.5 Salidas.
P_A; C_R.
#### 1.6 Codigo.

### Ejercicio 8. 
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197482355-9109f57f-e07a-47fa-9097-ef04e9e0a386.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 8. 
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197482559-3f9d511c-a368-4b92-8f2b-b4ff3bd22178.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 8. 
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197482488-8151b935-fc88-4412-bd5f-091a6f20aa66.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 9.
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197482672-6eed242b-d874-4e2c-8799-0594adfa0c0f.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 9. 
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197482760-4bd30e29-9b13-4fe5-9390-3aa8e01f6411.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 9.
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197482934-840febba-0be4-4fe0-9c27-281d562999aa.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 10. 
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197483050-199efa86-cc20-4e8c-ab87-c507e6c93426.png)
#### 1.3 Prueba de escritorio 
|n1|n2|n1>n2|salida|
|-|-|-|-|
|2|4||n2 es mayor|
|9|6|9>6|n1 es mayor|
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 11. 
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197483146-55c5bd23-3545-4372-b004-843558fc1981.png)
#### 1.3 Prueba de escritorio 

#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 12.
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197483758-f4ea6e26-8ab1-4dd7-8bc4-37658cb6fc93.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 13.
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197483811-31f1c1c8-3223-41b1-a71a-02bd0ecb54dc.png)
#### 1.3 Prueba de escritorio 
#### 1.4 Entradas.
|n|n>0|i|i<=9|A[i]=n * i|i+1|salida|
|-|-|-|-|-|-|-|
|6|6>0|0|0<9|A[0]=6 * 0|0+1||
|||1|1<9|A[1]=6 * 0|0+1||
#### 1.5 Salidas.
#### 1.6 Codigo.

### Ejercicio 14.
#### 1.1 Analisis. 
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/197483869-000b9f97-54a5-4fa8-b514-fc84528984c0.png)
#### 1.3 Prueba de escritorio 
|i|i<=5|i++|j|j<=i|j++|salida|
|-|-|-|-|-|-|-|
|1|1<=5|1+1|1|1<=1|1+1| * |
|2|2<=5|2+1|1|1<=2|2+1| * |
|||||2<=2|2<=2| * |
|3|3<=5|3+1|1|1<=2|3+1| * |
|||||2<=2|2<=2| * |
|||||3<=2|3<=2| * |
|3|4<=5|3+1|1|1<=2|3+1| * |
|||||2<=2|2<=2| * |
|||||3<=2|3<=2| * |
|||||3<=2|3<=2| * |
|3|5<=5|3+1|1|1<=2|3+1| * |
|||||2<=2|2<=2| * |
|||||3<=2|3<=2| * |
|||||3<=2|3<=2| * |
|||||3<=2|3<=2| * |
#### 1.4 Entradas.
#### 1.5 Salidas.
#### 1.6 Codigo.
