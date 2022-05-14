# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

### Programa que pida un número y diga si es positivo o negativo

* 1.- inicio
* 2.- declarar(numero)float
* 3.- mostrar ("Ingresa un numero")
* 4.-asignar (numero)
* 5.- si numero>0 entonces 
              mostrar ("es positivo")
              
  sino 
  mostrar ("es negativo")
  finsi
 * 6.- fin

![image](https://user-images.githubusercontent.com/104279725/167274663-d36fd3d3-cd7e-4eb6-b1cf-af5089648550.png)
![image](https://user-images.githubusercontent.com/104279725/167274706-72259c0e-991c-4dbe-8315-f6176e513354.png)



              
### Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

* 1.-inicio
* 2.-declarar(letra)char
* 3.-mostrar ("ingresa una letra")
* 4.-asignar (letra)
* 5.-si letra==s or letra==n entonces 
                            mostrar "correcto"
  sino 
  mostrar "ERROR"
  finsi
* 6.-fin

![image](https://user-images.githubusercontent.com/104279725/167275313-e20718c9-8f9a-4082-9c14-fa19005eea13.png)
![image](https://user-images.githubusercontent.com/104279725/167275680-24ef8bc6-d1db-4eac-b686-45ef15fed98a.png)


### Un programa que pida una letra y detecte si es una vocal. 

* 1.-INICIO
* 2.-Declarar (letra)char
* 3.-Mostrar ("Ingresa una letra")
* 4.-Asignar (letra)
* 5.-Si letra==a or letra==e or letra==i or letra==o or letra==u or letra==A or letra==E or letra==I or letra==O or letra==U 
* Entonces 
* Mostrar ("Haz ingresado una vocal") 
* sino 
* mostrar ("Haz ingresado una consonante")
* finsi
* 6.-FIN

![image](https://user-images.githubusercontent.com/104279725/168411576-9d69a768-3303-4297-8292-740c1fed0ecc.png)
![image](https://user-images.githubusercontent.com/104279725/168411584-885fc97a-a079-4ffc-bd72-210f1674feba.png)

### Programa que pida 3 números y los muestre en pantalla de menor a mayor. 

* 1.-INICIO
* 2.-Declarar(num1,num2,num3)
* 3.-Mostrar("Ingresar primer numero")
* 4.-Asignar (num1)
* 5.-Mostrar("Ingresa segundo numero")
* 6.-Asignar (num2)
* 7.-Mostrar("Ingresa tercer numero")
* 8.-Asignar (num3)
* 9.-Si num1>num2 entonces
      * Si num2>num3 entonces
      Mostrar("El orden de menor a mayor es: ", num3,",",         num2,",",num1"," )
sino
      Si num1>num3 entonces
            Mostrar ("El orden de menor a mayor es: ",num2,",", num3,",",num1",")
sino
      Mostrar("El orden de menor a mayor es: ",num2,",", num1,",",num3",")
      finsi
finsi
Sino
      Si num1>num3 Entonces
      Mostrar ("El orden de menor a mayor es: ",num3,", ",num1,", ",num2,", ")
SiNo
	Si num2>num3 Entonces
	 Mostrar("El orden de menor a mayor es: ",num1,", ",num3,", ",num2,", ")
SiNo
	 Mostrar("El orden de menor a mayor es: ",num1,", ",num2,", ",num3,",")
			FinSi
		FinSi
	FinSi
* 10.-FIN

![image](https://user-images.githubusercontent.com/104279725/168412091-716885bb-ab76-4737-876d-92070ebf5246.png)
![image](https://user-images.githubusercontent.com/104279725/168412107-d43890c6-515d-4475-ab10-83444690efa2.png)

### De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

* 1.-INICIO
* 2.-Declarar(num)
* 3.-Mostrar("Ingresa un numero")
* 4.-Asignar(num)
* 5.-Si num>0 y num<13 entonces
Si num=1 entonces mostrar("Es Enero ") finsi
Si num=2 entonces mostrar("Es Febrero ") finsi
Si num=3 entonces mostrar("Es Marzo ") finsi
Si num=4 entonces mostrar("Es Abril ") finsi
Si num=5 entonces mostrar("Es Mayo ") finsi
Si num=6 entonces mostrar("Es Junio ") finsi
Si num=7 entonces mostrar("Es Julio ") finsi
Si num=8 entonces mostrar("Es Agosto ") finsi
Si num=9 entonces mostrar("Es Septiembre ") finsi
Si num=10 entonces mostrar("Es Octubre ") finsi
Si num=11 entonces mostrar("Es Noviembre ") finsi
Si num=12 entonces mostrar("Es Diciembre ") finsi
finsi
* 6.-FIN

![image](https://user-images.githubusercontent.com/104279722/168410632-75632e31-ba07-4977-9e44-725efa245dea.png)
![image](https://user-images.githubusercontent.com/104279722/168410644-5a4825f4-bcd6-4174-8ed6-a8b151507840.png)
![image](https://user-images.githubusercontent.com/104279722/168410664-6249715e-b026-45f6-acf5-8490f43edbd8.png)
![image](https://user-images.githubusercontent.com/104279722/168410684-f19f4fe9-acb8-4bd8-bddf-9dc140904609.png)

### De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.

* inicio
* 
### Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.

* 1.-INICIO
* 2.Declarar(registro_usu,registro_contra,usuario,contraseña)char
* 3.-Mostrar("Registra un usuario")
* 4.-Asignar(registro_usu)
* 5.-Mostrar("Registra una contraseña")
* 6.-Asignar(registro_contra)
* 7.-Mostrar("REGISTRO COMPLETO")
* 8.-Mostrar("Ingresar usuario")
* 9.-Asignar(usuario)
* 10.-Si usuario=registro_usu entonces
* Mostrar("Usuario correcto")
* Sino 
* Mostrar("Usuario incorrecto")
* finsi
* Mostrar("Ingresa contraseña")
* 11.-Asignar(contra)
* 12.- Si registro_contra=contraseña entonces
* Mostrar("Contraseña Correcta")
* sino
* Mostrar("Contraseña incorrecta")
* finsi
* 13.-FIN

![image](https://user-images.githubusercontent.com/104279725/168412227-18ded401-3ab6-4b00-a727-3853bd24df00.png)
![image](https://user-images.githubusercontent.com/104279725/168412238-cbaf4955-de94-48a1-9039-7e67e33a7cf1.png)
