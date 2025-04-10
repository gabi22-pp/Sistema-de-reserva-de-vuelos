# Sistema-de-reserva-de-vuelos
Diseño e implementación de un sistema para gestionar la reserva de asientos en una aerolínea con dos destinos internacionales, cumpliendo con una serie de especificaciones de programación orientada a objetos y buenas prácticas de desarrollo.

Objetivo General: Desarrollar una aplicación funcional y fácil de usar que permita a los usuarios reservar, consultar, cancelar vuelos y visualizar la disponibilidad de asientos, utilizando el paradigma de programación orientada a objetos y siguiendo las pautas establecidas.

Definición de Destinos:
- Se requiere definir dos destinos internacionales para los vuelos de la aerolínea. Estos destinos deben ser claramente identificables dentro del sistema.
Consideraciones:
- Nombres de los destinos (ej. Nueva York, París).
  
Tipos de Asientos y Capacidades:
- Cada vuelo debe ofrecer tres tipos de asientos: económico, ejecutivo y primera clase. Se debe definir la cantidad de asientos disponibles por cada categoría y el costo asociado a cada uno.
Consideraciones:
- Número de asientos por categoría (ej. Económico: 100, Ejecutivo: 20, Primera Clase: 10).
- Precios base para cada categoría. Estos precios podrían variar según el vuelo o la demanda.
  
Información del Viajero para la Reserva:
- Al realizar una reserva, se deben recopilar datos relevantes del viajero. La información específica a solicitar queda a discreción del equipo de desarrollo.
Consideraciones:
- Información básica esencial: Nombre completo, número de identificación/pasaporte.
  
Implementación Orientada a Objetos:
- La aplicación esta estructurado utilizando el paradigma de programación orientada a objetos. Esto implica la creación de clases, objetos, la definición de atributos (públicos y privados) y la implementación de métodos.
Requisitos Específicos:
- Herencia: Al menos una relación de herencia debe ser implementada entre las clases del sistema.
- Atributos: La aplicación debe utilizar tanto atributos públicos como privados para encapsular la información de los objetos.


Funcionalidades de la Aplicación:
La aplicación debe ofrecer las siguientes funcionalidades básicas:
- Reservar asiento: Permitir a los usuarios seleccionar un vuelo, tipo de asiento y proporcionar la información del viajero para realizar una reserva.
- Mostrar todas las reservas: Listar todas las reservas realizadas en el sistema, mostrando la información relevante (viajero, vuelo, asiento).
- Cancelar reserva: Permitir a los usuarios cancelar una reserva existente, identificándola de alguna manera (ej. número de reserva, nombre del viajero y vuelo).
- Mostrar asientos disponibles: Mostrar la disponibilidad de asientos por vuelo y por tipo de asiento.
