
# ZentroRestaurant
## Introduccion 

**Propósito:**

La aplicación AppZentral tiene como objetivo principal digitalizar y optimizar la experiencia de gestión para el restaurante Zentral. Este sistema, desarrollado en Django, busca ofrecer funcionalidades clave como administración de pedidos, gestión de inventarios, reservas de mesas y reportes de ventas, mejorando tanto la experiencia de los usuarios como la eficiencia operativa del restaurante.

## Objetivos:

1.Proveer una interfaz intuitiva para el personal del restaurante y los clientes.

2.Automatizar tareas administrativas, reduciendo errores humanos y tiempos de ejecución.

3.Implementar un sistema de reservas online para maximizar la ocupación de mesas.

4.Generar reportes detallados sobre ventas, inventarios y rendimiento del personal.

## Contexto del problema
El restaurante Zentral enfrenta desafíos relacionados con la gestión manual de sus operaciones diarias, lo que provoca:

°Errores frecuentes en la toma de pedidos: La confusión entre pedidos escritos manualmente afecta la precisión y la satisfacción del cliente.

°Ineficiencia en la gestión de inventarios: La falta de un sistema automatizado resulta en desabastecimientos o sobrestock de productos.

°Dificultades para las reservas: Los clientes enfrentan problemas para reservar mesas, especialmente en horarios pico,
lo que puede derivar en una experiencia insatisfactoria.

°Falta de análisis de datos: La ausencia de herramientas para analizar ventas y tendencias limita la capacidad de tomar decisiones informadas.

Un ejemplo revelador es que, durante los fines de semana, el restaurante experimenta retrasos de hasta 
30 minutos en la entrega de pedidos debido al aumento en la demanda y la falta de organización en la cocina.

# Análisis de requerimientos
## Requerimientos funcionales:

**Gestión de pedidos:**
Registro de pedidos por mesa y cliente.
Integración con la cocina para actualizaciones en tiempo real

**Sistema de reservas:**
Reservas de mesas a través de una interfaz web.
Confirmación y cancelación automática por correo electrónico o SMS.

**Gestión de inventarios:**
Control de productos en tiempo real.
Alertas automáticas para reabastecimiento.

**Reportes y análisis:**
Generación de reportes diarios, semanales y mensuales.
Visualización de métricas clave como ventas por plato o por horario.

## Requerimientos no funcionales:

1.Escalabilidad: La app debe soportar al menos 500 usuarios simultáneamente.

2.Seguridad: Implementación de autenticación segura para empleados y clientes.

3.Compatibilidad: La aplicación debe ser accesible desde navegadores modernos y dispositivos móviles.
## Requerimientos técnicos:

1.Framework: Django (Python 3.9 o superior).

2.Base de datos: PostgreSQL para el almacenamiento de datos estructurados.

3.Frontend: HTML5, CSS3 y JavaScript con Bootstrap para un diseño responsivo.

4.Implementación: Despliegue en un servidor web compatible, como Nginx o Apache.

## Modelo
![MODELO DJANGO](https://github.com/user-attachments/assets/9fb6ee32-9df8-4a38-b218-87d8edfc0b6e)

