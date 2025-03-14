#Sistema de Gestión de Pedidos de un Restaurante

## Descripción
Este proyecto es un sistema backend para gestionar pedidos en un restaurante. Permite a los meseros tomar pedidos, a la cocina procesarlos y a los clientes recibir notificaciones cuando su pedido esté siendo preparado o listo. El sistema está diseñado utilizando estructuras de datos eficientes, algoritmos de ordenamiento y patrones de diseño para garantizar un flujo de trabajo óptimo.

## Consigna 🎯
Implementar un sistema backend que cumpla con los siguientes requisitos:

### Estructuras de datos
- **Cola (Queue)**: Para gestionar el orden en que los pedidos llegan a la cocina.
- **Diccionario (Dictionary)**: Para almacenar los detalles de cada pedido (ID del pedido, platos, estado, etc.).

### Algoritmos
- **Tiempo estimado de preparación**: Calcular el tiempo estimado de preparación de un pedido basado en la complejidad de los platos.
- **Ordenamiento por prioridad**: Ordenar los pedidos en la cola de la cocina por prioridad (pedidos urgentes primero).

### Patrones de diseño
- **Observer**: Para notificar a los clientes cuando su pedido esté listo.
- **Singleton**: Para garantizar que solo exista una instancia del sistema de gestión de pedidos.

### Lógica de programación
- **Validación de platos**: Validar que los platos solicitados estén disponibles en el menú antes de agregarlos a un pedido.
- **Cancelación de pedidos**: Implementar una función para cancelar pedidos y liberar los recursos asociados.

## Tecnologías utilizadas 🛠️
- **Lenguaje de programación**: C#
- **Framework**: .NET Core
- **Estructuras de datos**: Colas, diccionarios, listas.
- **Patrones de diseño**: Observer, Singleton.
- **Herramientas**: Git