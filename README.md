# 💻 TALLER: BÚSQUEDA LINEAL APLICADA A TIENDA DE ELECTRÓNICA

**Estudiante:** [Tu Nombre Completo Aquí]  
**Materia:** Algoritmos y Estructuras de Datos  
**Fecha de Entrega:** [Fecha]

---

## 🎯 OBJETIVO DEL PROYECTO

Este proyecto es mi solución al taller práctico de **Búsqueda Lineal (Linear Search)**. Mi objetivo fue aplicar este algoritmo de complejidad O(n) para desarrollar las funciones de gestión de productos y empleados de una tienda de electrónica.

Todo el código de implementación requerido se encuentra en el archivo `ejercicios_practicos.py`.

---

## 📁 ESTRUCTURA Y CONTENIDO DEL PROYECTO

El proyecto se compone de los siguientes archivos principales:

| Archivo | Descripción de mi Trabajo | Estatus |
| :--- | :--- | :--- |
| **`ejercicios_practicos.py`** | Contiene **mi implementación** de las funciones para los Ejercicios 1 al 6 (búsqueda básica, filtros por criterios, estadísticas y contador de comparaciones). | **COMPLETADO** |
| **`sistema_tienda.py`** | Es el sistema completo que funciona como **referencia** para la estructura de la aplicación. No lo modifiqué, ya que mi trabajo era completar las funciones en el archivo de ejercicios. | Referencia |
| **`datos_ejemplo.py`** | Contiene las estructuras de datos (`PRODUCTOS_EXTENDIDOS` y `EMPLEADOS`) utilizadas para probar todas mis funciones. | Sin Modificar |
| **`TALLER_BUSQUEDA_LINEAL.md`** | La guía y las especificaciones originales del taller. | Referencia |

---

## 🚀 CÓMO VERIFICAR MI IMPLEMENTACIÓN

Para verificar que todas las funciones de búsqueda lineal y estadísticas fueron implementadas correctamente, solo es necesario ejecutar el archivo de ejercicios:

1.  Abre la terminal o línea de comandos en la carpeta del proyecto.
2.  Ejecuta el script:

    ```bash
    python ejercicios_practicos.py
    ```

El script está diseñado para ejecutar automáticamente las pruebas (usando `asserts`) para los Ejercicios 1 al 6 y debe mostrar el mensaje **"¡TODOS LOS EJERCICIOS COMPLETADOS EXITOSAMENTE!"** si mi código cumple con todos los requisitos.

---

## 🔑 FUNCIONALIDADES CLAVE IMPLEMENTADAS (BÚSQUEDA LINEAL)

En `ejercicios_practicos.py` resolví los siguientes retos aplicando el recorrido lineal (for/while) a las listas:

1.  **Búsqueda Simple (`busqueda_lineal_simple`):** Retorna el índice del elemento o -1.
2.  **Búsqueda en Diccionarios:** Buscar productos por nombre y empleados por ID.
3.  **Búsqueda con Criterios Múltiples:** Filtrar productos por rango de precio y por doble condición (`stock > 0` AND `disponible == True`).
4.  **Estadísticas por Recorrido:** Calcular el valor total del inventario (`precio * stock`) y contar la frecuencia de las categorías.
5.  **Análisis de Rendimiento:** Implementé el contador de comparaciones en la búsqueda (`busqueda_lineal_con_contador`) para demostrar la complejidad $O(n)$ en el peor caso.
