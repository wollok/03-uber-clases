
# Ejercicio Uber - Colecciones con Clases

## Planteo general
Queremos hacer la aplicación para una agencia de choferes de Uber.
La agencia tiene clientes y choferes.

## Punto 1)
Cada chofer tiene su estrategia para tomar un viaje o no

* algunos toman viaje siempre (como Daniel)
* otros como Nicolás solo toman viajes si son de 5 a 10 kilómetros, o si van por autopista 
* por último están los choferes que solo quieren llevar pasajeros que sean altos (que midan más de 1,80)

Resolver el requerimiento de saber si un chofer puede tomar o no un viaje.

## Punto 2) 
Queremos ver qué choferes pueden tomar el viaje que quiere hacer dodain.

Hablar de polimorfismo.
¿Cómo testearlo?

## Punto 3)
Queremos agregar que para tomar un viaje

* ningún chofer puede tomar más de 10 viajes
* y tampoco puede hacer un viaje de más de 100 kilómetros

Pensar dos maneras de resolverlo.

## Punto 4) 
Cada chofer tiene su propio criterio para establecer la tarifa

* por defecto todos cobran 10 $ por kilómetro
* pero algunos cobran un extra de $ 50 por "tasa de embarque" (?) para distribuir al sindicato de taxis
* por último algunos 10 $ por kilómetro pero se aseguran un mínimo de $ 100 (es decir, si el viaje es menor a 10 kilómetros cobran igualmente $ 100)

Implementar esta estrategia sabiendo que cualquier chofer puede elegir una u otra opción, o querer cambiarla a futuro.

## Punto 5) 
Hacer que un cliente viaje, de manera de 

* generar un viaje
* seleccionar los choferes están que en condiciones de tomar ese viaje 
* elegir el que cobra menos (cualquiera)
* efectuar el viaje (la persona se dirige al destino)

## Punto 6)
Hacer un segundo viaje para el mismo cliente.
Saber cuánto gastó en total ese cliente en viajes.

## Punto 7)
Cada chofer tiene un auto, queremos saber cuáles son los autos en los que viajó un cliente.


