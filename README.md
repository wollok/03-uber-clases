
 
[![Build Status](https://travis-ci.org/wollok/uberClases.svg?branch=master)](https://travis-ci.org/wollok/uberClases)

# Ejercicio Uber - Colecciones con Clases

## Planteo general
Queremos hacer la aplicación para una agencia de choferes de Uber.
La agencia tiene clientes y choferes.

## Punto 1)
Cada chofer tiene su estrategia para tomar un viaje o no

* algunos toman viaje siempre
* otros solo toman viajes si son de 5 a 10 kilómetros, o si van por autopista 
* por último están los choferes que solo quieren llevar pasajeros que sean altos (que midan más de 1,80)
 * Daniel es un chofer particular, es uno de los que toman pasajeros altos, pero no quiere hacer un viaje de más de 100 kilómetros

Resolver el requerimiento de saber si un chofer puede tomar o no un viaje.

### Preguntas

* ¿Cómo lo encaramos? ¿Partimos del cliente, del chofer? 
* ¿Cómo lo testeamos?


## Punto 2) 
Queremos ver qué choferes pueden tomar el viaje que quiere hacer el cliente Dodain, que mide 1,88 metros, de Liniers a Quilmes, el sábado 01/10, que insume 15 kilómetros.

### Preguntas
* ¿Cómo se testea?
* ¿Qué tiene que ver el polimorfismo en este punto? ¿A quién ayuda?

## Punto 3)
Queremos agregar que para tomar un viaje

* ningún chofer puede tomar más de 10 viajes

Pensar dos maneras de resolverlo **sin repetir código**.

### Tips

* super
* template method

## Punto 4) 
Cada chofer tiene su propio criterio para establecer la tarifa

* por defecto todos cobran 10 $ por kilómetro
* pero algunos cobran un extra de $ 50 por "tasa de embarque" (?) para distribuir al sindicato de taxis
* por último algunos 10 $ por kilómetro pero se aseguran un mínimo de $ 100 (es decir, si el viaje es menor a 10 kilómetros cobran igualmente $ 100)

Implementar esta estrategia sabiendo que cualquier chofer puede elegir una u otra opción, o querer cambiarla a futuro.

### Tip: la herencia no es la única solución

## Punto 5) 
Hacer que un cliente viaje, de manera de 

* generar un viaje
* seleccionar los choferes están que en condiciones de tomar ese viaje 
* elegir el que cobra menos (cualquiera)
* efectuar el viaje (la persona se dirige al destino)

### Preguntas

* ¿Cuándo hay efecto?

## Punto 6)
Hacer un segundo viaje para el mismo cliente.
Saber cuánto gastó en total ese cliente en viajes.

## Punto 7)
Cada chofer tiene un auto, queremos saber cuáles son los autos en los que viajó un cliente.

### Pregunta: ¿para qué me ayudan los bloques?
