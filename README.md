# CONTROLES DE FLUJO
Los controles de flujo nos permiten tomar 
desiciones y ejecutar diferentes acciones segun ciertas condiciones.
## DECISIONES 
**-ESTRUCTURA IF** 

La estructura `if` nos permite ejecutar un bloque de codigo
si se cumple una condicion determinada.
> ejemplo:
```python
if (condicion)  {
    // codigo a ejecutar si la
 condicion es verdadera
}
```

**-ESTRUCTURA IF-ELSE**

La estructura `if-else` nos permite un bloque de codigo si se cumple una condicion y otro bloque de codigo si no se cumple.
> ejemplo:
```python
if (condicion) {
    //codigo a ejecutar si la condiucion es verdadera 
} else {
    // codigo a ejecutar si la condicion es falsa
}
```

**-ESTRUSTURA IF-ELSE IF**

La estructura nos permite evaluar multiples condiciones y ejecutar diferentes bloques de codigo segun el resultado de cada una.
>ejemplo:
```python
if (condicion) {
    // codigo a ejecutar si la condicion1 es verdadera
} else if (condicion2) {
    //codigo a ejecutar si la condicion1 es falsa y la condicion2 es veradera
} else {
    // codigo a ejecutar si ninguna de las condiciones anteriores es verdadera
}
```

**-ESTRUCTURA SWITCH**

La estructura nos permite evaluar una exoresion y ejecutar diferentes bloques de codigo segun el valor de la expresion.
> ejemplo:
``` python
switch (expresion) {
    case valor1:
        // codigo a ejecutar si la expresion es igual a valor1
        break;
        case valor2:
        // codigo a ejecutar si la expresion es igual a valor2
        break;
     default :
            // codigo a ejecutar si la expresion no coincide con ninguno de los valores anteriores
            break;
}
```


