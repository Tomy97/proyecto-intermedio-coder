## Descripci贸n del proyecto 馃搵
<p>Mi proyecto es acerca de una plataforma que se dedica a brindar becas universitarias a quienese se interesen por las mismas, brindando la posibilidad de aplicar a varias instituciones</p>

## Caracter铆sticas y funcionalidades de la aplicaci贸n

<p>El postulante va a poder navegar a trav茅s de la pagina por diferentes rutas que le permitiran ver las universidades disponibles, las propuestas que tenemos para ofrecer y cuales son sus requisitos, como asi tambien postularse y buscar su postulacion a trav茅s de la base de datos</p>
<p>La opcion "Postulantes" permitira a los postulantes cargar sus datos en la base de datos</p>

`Linea de codigo`
```
nombre = CharField(max_length= 100)
```
apellido = CharField(max_length=100)
 ```
contacto = IntegerField()
```
email = EmailField(max_length= 100)

<p>C贸digo para Universidades</p>

`Linea de codigo`

```
nombre = CharField(max_length= 100)
```    
localizacion = CharField(max_length= 100)
```   
direccion = CharField(max_length= 100)
```    
zip_code = IntegerField()
```    
descripcion = CharField(max_length= 2000)
```    
contacto = EmailField(max_length=100)

<p>C贸digo para Becas</p>

`L铆nea de c贸digo`

```
nombre = CharField(max_length= 100)
```    
descripcion = CharField(max_length= 2000)
```
fecha_de_inscripcion = CharField(max_length= 100)
```
promedio = IntegerField()
```
id_universidad = IntegerField()

## Acceso al proyecto

[Plataforma de Becas](http://127.0.0.1:8000/inicio/)

## Lenguajes utilizados

<li>Python</li>
<li>Django Framework</li>
<li>HTML</li>
<li>CSS</li>

## Personas/desarrolladores que realizaron el proyecto

*Tomas Pandullo* 