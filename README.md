# SMART CITIES LINKED DATA
## CENTROS DE SALUD
## Integrantes
* Dayana Chamba
* Jhuliana Encalada
### Indice de contenidos
* Modelo ontológico para centros de salud - smart cities
* 

### Modelo en protege
![protege](https://user-images.githubusercontent.com/19150432/54550774-b13e5200-497a-11e9-954e-b97e127d0485.jpeg)


### Clases creadas en protege

![clases](https://user-images.githubusercontent.com/19150432/54551576-5ad21300-497c-11e9-994d-be71280c69fd.jpeg)

### Propiedades de objetos


### Propiedades de datos

![propiedadesDatos](https://user-images.githubusercontent.com/19150432/54551817-c74d1200-497c-11e9-91c4-a07561b5c71d.jpeg)



### Tripletas de Jena
Para la generación de las tripletas se uso la librería Jena con el lenguaje de programación JAVA; para lo cual se creo clases referentes a los centros de salud las cuales se detallan a continuación con sus respectivos atributos.
* Bloque.java
    String codigo;
    String descripcion;
* CentroSalud.java
    String id ;
    String nombCentro;
    String parroquia;
    String canton;    
    String ciudad;
    String provincia;
    String pais;
    String area;
    String departamento;    
    ArrayList<String> cantEspecialistas;
    ArrayList<String> cantBloque;
    ArrayList<String> cantResiduos;
    String sector;
    String categoria;
    String tipo;
    ArrayList<String> especialidad;
    String anio;
    String fuente1;
    String fuente2;
    String codigo;
    String detalle;
    String residuos;
    String bloqueNombre;
  
* Especialidad.java

  String nombre;
  int cantidad;
 


### Modelo
