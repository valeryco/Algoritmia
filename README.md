# Repositorio de Algoritmia

Este repositorio reúne una colección integral de algoritmos desarrollados en PseInt, diseñados para abarcar desde la lógica básica y secuencial hasta estructuras de control avanzadas, bucles, validaciones y modularización mediante subprocesos, complementados con guías prácticas.

## Contenido del Repositorio

### 1. Algoritmos Básicos y Utilidades

* **Edad en Días**: Calcula la edad aproximada de una persona en días a partir de los años ingresados (multiplicando por $365$).
* **Programa de Propinas**: Calcula el total de una cuenta con propina personalizable y divide el costo equitativamente entre un número de personas.
* **Promedio de Notas**: Recibe tres calificaciones reales, calcula su promedio aritmético y muestra el resultado final.
* **Saludo**: Solicita el nombre del usuario por teclado y muestra un mensaje de bienvenida personalizado.
* **Preparación de Tinto**: Guía paso a paso en formato de texto para la correcta preparación de una taza de café soluble.

### 2. Estructuras Condicionales y Bucles Avanzados

* **Bisiesto**: Determina si un año ingresado cumple con las condiciones del calendario gregoriano para ser considerado bisiesto.
* **Parqueadero**: Sistema completo de cobro para vehículos (carros y motos) con cálculo por horas, aplicación de tarifas máximas de $\$30,000$ y descuento del $50\%$ si se presenta factura de compra.
* **Semáforo (Inventario)**: Control de inventario basado en stock disponible, generando alertas de color Rojo (agotado), Amarillo (reordenar) y Verde (todo en orden).
* **Validar Edad**: Verifica rangos lógicos de edad ($0$ a $120$ años) y clasifica automáticamente si el usuario es mayor o menor de edad.
* **Validar Registro**: Comprueba la validez de los datos de registro asegurando que el usuario no esté vacío y que la contraseña tenga un mínimo de $8$ caracteres.

### 3. Bucles Complejos, Funciones y Modularización

* **Cajero Parqueadero**: Bucle iterativo para el cierre de caja que acumula los pagos sucesivos hasta recibir un valor de $0$, mostrando los carros atendidos y el total recaudado.
* **Calificaciones**: Procesa un lote de $5$ notas obteniendo el promedio, cantidad de aprobados, nota más alta, más baja y detección de alumnos que requieren refuerzo.
* **Factura Restaurante**: Programa modularizado mediante **SubProcesos** para leer pedidos, calcular impuestos ($8\%$) y propinas ($10\%$), e imprimir una factura desglosada.
* **Pirámide**: Generador de patrones gráficos utilizando bucles anidados para dibujar una pirámide simétrica de asteriscos de acuerdo con la altura ingresada.
* **Validar PIN**: Sistema de acceso interactivo que permite un máximo de $3$ intentos para validar un PIN numérico de seguridad ($2580$).

## Instrucciones de Uso

1. Instala e inicia **PseInt** en tu equipo.
2. Abre el archivo `.psc` correspondiente al ejercicio que deseas probar.
3. Ejecuta el algoritmo (modo normal o paso a paso) e interactúa con la consola ingresando los datos solicitados según las instrucciones en pantalla.
