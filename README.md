# My-First-Shopping-Cart
Sistema POS Inteligente (Point of Sale)
Un sistema de gestión de pedidos de alto rendimiento diseñado para entornos minoristas, que integra lógica de negocio avanzada, motores de promociones dinámicas y cálculo de puntos en tiempo real.

🚀 Características Principales
Motor de Promociones Dinámicas: Evalúa requisitos de inventario en tiempo real para aplicar descuentos o sugerencias de compra.

Algoritmo de Sugerencias: Basado en brechas de puntos (gap analysis) para maximizar el ticket promedio mediante productos sugeridos.

UI/UX de Dashboard: Interfaz moderna y responsiva con feedback visual instantáneo.

Persistencia de Datos: Integración con localStorage para garantizar la continuidad del flujo de trabajo.

Exportación de Datos: Generación rápida de tablas SKU con funcionalidad de portapapeles.

🛠 Arquitectura del Proyecto
El sistema está construido bajo principios de separación de responsabilidades:

Capa de Estado: Gestión centralizada del carrito y preferencias del cliente.

Motor de Reglas (Service Layer): Lógica pura independiente del DOM para cálculos matemáticos y validaciones.

Capa de Presentación (UI Layer): Funciones de renderizado reactivo que reflejan el estado del sistema.

💻 Tecnologías
Core: JavaScript (ES6+), HTML5, CSS3.

Diseño: CSS Grid & Flexbox para un layout de tipo Dashboard.

Lógica: Manipulación del DOM orientada a eventos y estado.

📈 Roadmap de Desarrollo (Siguientes Pasos)
[ ] Implementar persistencia con una base de datos externa (Firebase/Supabase).

[ ] Integrar un modelo básico de Machine Learning para sugerir productos basados en el historial.

[ ] Añadir reportes de ventas descargables en formato .csv o .pdf.
