# Practicando-Funciones-Gutierrez-Gayosso-Jose-Alejandro-1185-3W

Gutierrez Gayosso Jose  Alejandro 1185 3W

1- En Python una funcion es definida usando la palabra def como palabra clave

![image](https://github.com/user-attachments/assets/3fe4731e-9581-4c3e-8257-00cbc58cc9c3)

![image](https://github.com/user-attachments/assets/f6d2e924-a193-4bc1-ac90-43c055ad744a)

2- Para llamar a una funcion, use la funcion nombrada y seguida de parentesis:

![image](https://github.com/user-attachments/assets/bf21a542-a79b-4328-8c68-e47661a944c8)

![image](https://github.com/user-attachments/assets/9df3033c-0d9e-4fda-84c2-27e1771a10a9)

3- El siguiente ejemplo tiene una función con un argumento (fname). Cuando se llama a la función, pasamos un nombre, que se usa dentro de la función para imprimir el nombre completo:

![image](https://github.com/user-attachments/assets/7d1ba774-6083-4f17-9291-a9c85816c335)

![image](https://github.com/user-attachments/assets/0c9fecad-7398-4838-b499-2f75281cbef4)

4- De forma predeterminada, se debe llamar a una función con la cantidad correcta de argumentos. Lo que significa que si su función espera 2 argumentos, debe llamar a la función con 2 argumentos, ni más ni menos.

![image](https://github.com/user-attachments/assets/f912d5ab-4fa4-40f2-b0da-6376e57315cd)

![image](https://github.com/user-attachments/assets/4aa6cc58-4e6d-45ab-92d3-7048b9147ea3)

5- Esta función espera 2 argumentos, pero solo obtiene 1:

![image](https://github.com/user-attachments/assets/22b223d7-27c0-48a8-912a-58951b0fd5f4)

![image](https://github.com/user-attachments/assets/32f18967-7fdf-42c5-bb58-cd81f9f460c4)

6- Si no sabe cuántos argumentos se pasarán a su función, agregue un * antes del nombre del parámetro en la definición de la función.
De esta manera, la función recibirá una tupla de argumentos y podrá acceder a los elementos en consecuencia:
Si se desconoce el número de argumentos, agregue un * antes del nombre del parámetro:

![image](https://github.com/user-attachments/assets/b88f0125-02ec-4180-8fb0-a44c2d7b5287)

![image](https://github.com/user-attachments/assets/49905518-ec07-42ba-b594-5b72a5d61bea)

7- También puede enviar argumentos con la sintaxis clave = valor.

![image](https://github.com/user-attachments/assets/ecf6602c-abd5-4727-b3dc-ec6bd1448035)

![image](https://github.com/user-attachments/assets/412720d0-8638-4c3f-9719-3b87fd00c7e2)

8- Argumentos arbitrarios de palabras clave, **kwargs
Si no sabe cuántos argumentos de palabras clave se pasarán a su función, agregue dos asteriscos: ** antes del nombre del parámetro en la definición de la función.
De esta manera, la función recibirá un diccionario de argumentos y podrá acceder a los elementos en consecuencia:
Si se desconoce el número de argumentos de palabras clave, agregue un doble ** antes del nombre del parámetro:

![image](https://github.com/user-attachments/assets/92b56742-8481-4fbd-a391-5eabb87a7726)

![image](https://github.com/user-attachments/assets/cf48e180-893a-4fcd-a2fe-134a22c61c8e)

9- Valor de parámetro predeterminado
El siguiente ejemplo muestra cómo utilizar un valor de parámetro predeterminado.

![image](https://github.com/user-attachments/assets/161b918b-61bd-4aea-9159-04247d2051fc)

![image](https://github.com/user-attachments/assets/8243124c-90c4-45c1-be1e-0318e868394d)

10- Pasar una lista como argumento
Puede enviar cualquier tipo de argumento de datos a una función (cadena, número, lista, diccionario, etc.) y será tratado como el mismo tipo de datos dentro de la función.

![image](https://github.com/user-attachments/assets/305c49a5-1211-4123-a0da-efe17d59cdb0)

![image](https://github.com/user-attachments/assets/df4aeda3-d363-4621-b1c4-e29af046cb37)

11- Regresa Valores
Para permitir que una función devuelva un valor, utilice la declaración de retorno:
def my_function(x):

![image](https://github.com/user-attachments/assets/77090f90-76a9-4054-8cd5-449bd75dcb9e)

![image](https://github.com/user-attachments/assets/40eb42f4-bcf7-4401-b5c8-6cc2a642198e)

12- La declaración del pass
Las definiciones de función no pueden estar vacías, pero si por alguna razón tiene una definición de función sin contenido, ingrese la instrucción pass para evitar recibir un error.

![image](https://github.com/user-attachments/assets/9f61dd80-7b8b-4576-9ebc-9911e576880a)

![image](https://github.com/user-attachments/assets/7a27b9dd-5f0d-4648-8b8e-b1f965577ec6)

13- Argumentos sólo posicionales 
Puede especificar que una función pueda tener SÓLO argumentos posicionales o SÓLO argumentos de palabras clave.
Para especificar que una función solo puede tener argumentos posicionales, agregue , / después de los argumentos:
Ícono de validado por la comunidad

![image](https://github.com/user-attachments/assets/fb29d7a2-a510-4f40-9c61-1324b9a28019)

![image](https://github.com/user-attachments/assets/3de523a8-d060-4aa2-8197-2766994117b6)


14- Sin , / en realidad se le permite usar argumentos de palabras clave incluso si la función espera argumentos posicionales:

![image](https://github.com/user-attachments/assets/994e5d0d-ef4b-4a50-a428-eeb034fb7103)

![image](https://github.com/user-attachments/assets/2ff93d4f-8e6b-4ba5-9259-c806c702af4c)

15- Pero al agregar , / obtendrá un error si intenta enviar un argumento de palabra clave:

![image](https://github.com/user-attachments/assets/3b7a50df-e474-4c22-b7d5-a3afc5807992)

![image](https://github.com/user-attachments/assets/ef348683-195b-46d6-a1c2-e7048a34581c)




