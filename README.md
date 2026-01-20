# Actividad 1: Venta de Vehículos - CLI

Este proyecto es una aplicación de línea de comandos (CLI) desarrollada en Java que simula la venta de vehículos en una concesionaria. Permite al usuario visualizar los vehículos disponibles, seleccionar uno o más vehículos para comprar, y generar un ticket de venta con un resumen de la transacción.

## Funcionalidades

1. **Mostrar inventario de vehículos**: El programa muestra una lista de vehículos con su marca, modelo, año y precio.
2. **Seleccionar vehículos**: El usuario puede elegir uno o más vehículos disponibles para la compra.
3. **Ingresar nombre del cliente**: El programa solicita el nombre del cliente para incluirlo en el ticket.
4. **Generar ticket de venta**: Incluye el total a pagar, la fecha de la transacción y los detalles de los vehículos seleccionados.

## Estructura del programa

El programa se centra en tres partes principales:
1. **Clase `Vehiculo`**: Representa cada vehículo en el inventario. Contiene atributos como `marca`, `modelo`, `año` y `precio`.
2. **Clase `Ticket`**: Gestiona los detalles de la transacción como cliente, lista de vehículos comprados, fecha de la transacción y el total a pagar.
3. **Clase principal**: Contiene el método `main` para interactuar con el usuario mediante la línea de comandos:
   - Muestra los vehículos disponibles.
   - Permite seleccionar vehículos.
   - Solicita el nombre del cliente.
   - Genera y muestra el ticket.

## Ejemplo de ejecución

```
=== Bienvenido a la Concesionaria ===
Lista de Vehículos Disponibles:
1. Toyota Corolla (2023) - $25000.0
2. Honda Civic (2022) - $24000.0
3. Ford Focus (2021) - $20000.0
4. Chevrolet Malibu (2023) - $28000.0
Seleccione el número del vehículo que desea (o escriba 'fin' para terminar): 1
Vehículo añadido: Toyota Corolla (2023) - $25000.0
Seleccione el número del vehículo que desea (o escriba 'fin' para terminar): 3
Vehículo añadido: Ford Focus (2021) - $20000.0
Seleccione el número del vehículo que desea (o escriba 'fin' para terminar): fin
Por favor, ingrese su nombre: Juan Pérez
=== Ticket de Venta ===
Cliente: Juan Pérez
Fecha: 2026-01-18 12:34:56
Vehículos:
- Toyota Corolla (2023) - $25000.0
- Ford Focus (2021) - $20000.0
Total a pagar: $45000.0
```

## Licencia

Este proyecto está bajo la licencia de poder hacer lo que quieras lol.

## Autor

Desarrollado por [dantereach](https://github.com/dantereach).
