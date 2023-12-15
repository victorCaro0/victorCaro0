# Legal Advisor (LEAD) 

## Descripción
"Legal Advisor" es un sistema informático jurídico diseñado para la individualización y acuerdos sobre la pena. Esta aplicación en Java proporciona herramientas y recursos útiles para abogados y jueces ,tiene como objetivo determinar la recomendación de la pena a partir de circunstancias objetivas y subjetivas consideradas relevantes dentro de un caso proporcionado.


UMl de mi parte del proyecto: 

![image](https://github.com/victorCaro0/victorCaro0/assets/126029696/19e579ae-e1e5-4c54-be44-ebdfac60ba53)


Victima: 

Representa a una persona que ha sufrido algún tipo de daño. La clase tiene los siguientes atributos:

- nombre: es una variable de tipo String que almacena el nombre de la víctima.
- edad: es una variable de tipo int que almacena la edad de la víctima.
- numExp: es una variable de tipo String que almacena el número de expediente de la víctima.
- dano_fisicos: es una variable de tipo String que almacena el tipo de daño físico que ha sufrido la víctima.
- dano_morales: es una variable de tipo String que almacena el tipo de daño moral que ha sufrido la víctima.
- dano_psiquicos: es una variable de tipo String que almacena el tipo de daño psíquico que ha sufrido la víctima.
- dano_materiales: es una variable de tipo String que almacena el tipo de daño material que ha sufrido la víctima.

Los atributos se declaran con el signo - al principio, lo que indica que son privados, es decir, que solo se pueden acceder desde la propia clase o desde otras clases que hereden de ella.

La clase también tiene los siguientes métodos:

- Victima: es el constructor de la clase, que se encarga de inicializar los atributos con los valores que se pasan como parámetros. El constructor se declara con el signo + al principio, lo que indica que es público, es decir, que se puede llamar desde cualquier parte del programa. El constructor tiene el mismo nombre que la clase y no devuelve ningún valor.
- setNombre: es un método que permite cambiar el valor del atributo nombre. El método se declara con el signo + al principio, lo que indica que es público. El método recibe un parámetro de tipo String que representa el nuevo nombre de la víctima y no devuelve ningún valor. El método se llama setNombre siguiendo la convención de Java para los métodos que modifican los atributos, que empiezan por set seguido del nombre del atributo con la primera letra en mayúscula.
- getNombre: es un método que permite obtener el valor del atributo nombre. El método se declara con el signo + al principio, lo que indica que es público. El método no recibe ningún parámetro y devuelve un valor de tipo String que representa el nombre de la víctima. El método se llama getNombre siguiendo la convención de Java para los métodos que acceden a los atributos, que empiezan por get seguido del nombre del atributo con la primera letra en mayúscula.
- getNumExp: es un método que permite obtener el valor del atributo numExp. El método se declara con el signo + al principio, lo que indica que es público. El método no recibe ningún parámetro y devuelve un valor de tipo String que representa el número de expediente de la víctima. El método se llama getNumExp siguiendo la convención de Java para los métodos que acceden a los atributos, que empiezan por get seguido del nombre del atributo con la primera letra en mayúscula.


Hecho: 

Representa a un suceso que ha causado algún tipo de daño. La clase tiene los siguientes atributos:

- horario: es una variable de tipo String que almacena el horario en el que ocurrió el hecho.
- influencia_drogas: es una variable de tipo String que almacena si el autor del hecho estaba bajo la influencia de drogas o no.
- lugar: es una variable de tipo String que almacena el lugar en el que ocurrió el hecho.
- medios_empleados: es una variable de tipo String que almacena los medios que se utilizaron para causar el daño.
- planificacion: es una variable de tipo String que almacena si el hecho fue planificado o no.
- numExp: es una variable de tipo String que almacena el número de expediente del hecho.

Los atributos se declaran con el signo - al principio, lo que indica que son privados, es decir, que solo se pueden acceder desde la propia clase o desde otras clases que hereden de ella.

La clase también tiene los siguientes métodos:

- Hecho: es el constructor de la clase, que se encarga de inicializar los atributos con los valores que se pasan como parámetros. El constructor se declara con el signo + al principio, lo que indica que es público, es decir, que se puede llamar desde cualquier parte del programa. El constructor tiene el mismo nombre que la clase y no devuelve ningún valor.
- getNumExp: es un método que permite obtener el valor del atributo numExp. El método se declara con el signo + al principio, lo que indica que es público. El método no recibe ningún parámetro y devuelve un valor de tipo String que representa el número de expediente del hecho. El método se llama getNumExp siguiendo la convención de Java para los métodos que acceden a los atributos, que empiezan por get seguido del nombre del atributo con la primera letra en mayúscula.

![image](https://github.com/victorCaro0/victorCaro0/assets/126029696/319776fb-38eb-4324-b184-ff0e22c89770)

![image](https://github.com/victorCaro0/victorCaro0/assets/126029696/f1ca0a27-3027-49a2-b5c6-687c67f39c99)


