# repo_markdown
<!Aquí usamos la opción de incluir un enlace en un texto-->
Repositoro para la practica de [Markdown](https://github.com/Litosx/repo_markdown).
<!Aquí usamos la opción de cita, y la de negrita-->
> Citamos que el enlace al *repositorio* está en la linea anterior, en **Markdown**.

<!Aquí vemos los distintos tipos de encabezados-->
Añadimos los distintos tipos de `encabezados` resaltando la palabra encabezados:
# Esto es un ecabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6
  
<!Ahora vamos al bloque de códigos>  
## También podemos crear bloques de códigos, ya que se puedan usar, y copiar facilmente al renderizarlos.

```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```
```bash
#!/bin/bash
echo "Hola mundo"
```
## Otra forma de realizar enlaces.
<!Vamos a ver otra forma de realizar enlaces-->
Enlaces a la página web del [Práctica Markdown][1], a [GitHub][2] y a [Posada en producció][3].

[1]: https://github.com/Litosx/repo_markdown
[2]: https://github.com
[3]: https://aules.edu.gva.es/fp/course/view.php?id=122413

| Encabezado 1 | Encabezado 2 | Encabezado 3
| --- | --- | --- | ---
| Fila 1.1 | Fila 1.2 | Fila 1.3
| Fila 2.1 | Fila 2.2 | Fila 2.3
| Fila 3.1 | Fila 3.2 | Fila 3.3
<!Vamos a poner una imagen directamente en el documento.-->
>Imagen de lago de internet.

![](https://cdn-cbail.nitrocdn.com/KrwRdRBXEBaHZzSwTIkeckWVGSihZtWH/assets/images/optimized/rev-722b565/www.viaurbis.com/wp-content/uploads/2020/04/El-Lago-Salado.png)


## Seguimos con las listas.
<!Podemos realizar listas, tanto ordenadas como desordenadas.-->
> Lista desordenada.
* Inicio.
* Preparación laboratorio.
* Ejercicios.
* Entrega.
  
> Lista desordenada anidada.
* Ordenadores
  * Sobremesa
  * Portatil
* Pantallas
  * 17"
  * 18"
  * 24"
* Disco duro SSD

> Lista ordenada
1. inicio
2. Preparación
3. Ejercicios
4. Entrega

> Lista ordenada anidada.

1. ROUTING.  
  1.1 OSPF  
  1.2 BGP  
2. ACL  
  2.1 ESTANDAR  
  2.2 EXTENDIDA  
3. NAT  
4. HSRP


## Ahora vemos como introducir tablass.
<!Vamos a ver la sintaxis de la tabla.-->
| Nombre | Apellidos | Telefono
| --- | --- | ---
| Carlos | Talens | 655441554
| Cristina | Quiles | 676767676
| Alba | Bernabeu | 636363636

## Salto de linea
<!Si queremos forzar un salto de lijnea, hay que poner doble espacio y enter.-->
Por ejemplo, en esta frase  
hemos forzado un salto de línea.

