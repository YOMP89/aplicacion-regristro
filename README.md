# Proyecto: Sistema de Registro de Datos en Tiempo Real

## Descripción General

Este proyecto consiste en una aplicación web que permite registrar y visualizar datos personales en tiempo real. La aplicación está construida utilizando tecnologías web estándar (HTML, CSS y JavaScript) sin dependencias externas, lo que la hace ligera y fácil de implementar.

## Características Principales

- **Registro de datos personales**: Nombres, apellidos y número telefónico
- **Visualización en tiempo real**: Los datos ingresados se muestran automáticamente en un panel separado
- **Capacidad limitada**: Máximo 5 registros por sesión
- **Interfaz de usuario intuitiva**: Diseño moderno con fondos degradados en tonos azules
- **Validación de datos**: Control de campos vacíos y formato correcto para el número telefónico
- **Diseño responsivo**: Se adapta a diferentes tamaños de pantalla

## Estructura del Proyecto

La aplicación está desarrollada como una página web única (SPA - Single Page Application) que contiene dos secciones principales:

1. **Panel de Registro**: Formulario para la entrada de datos
2. **Panel de Visualización**: Área donde se muestran los registros en tiempo real

### Tecnologías Utilizadas

- **HTML5**: Estructura básica del documento
- **CSS3**: Estilos y diseño visual, incluyendo:
  - Flexbox para la disposición de elementos
  - Degradados para el fondo
  - Media queries para la responsividad
- **JavaScript (ES6+)**: Lógica de la aplicación, incluyendo:
  - Manipulación del DOM
  - Validación de formularios
  - Actualización en tiempo real
