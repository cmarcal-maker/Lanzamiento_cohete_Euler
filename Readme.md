# 🚀 Simulación del Lanzamiento de un Cohete mediante el Método de Euler

## 1. Descripción del proyecto

Este proyecto consiste en el desarrollo de una página web que simula el movimiento vertical de un cohete mediante el método numérico de Euler explícito.

La simulación permite calcular y visualizar cómo cambia la altura y la velocidad del cohete durante su lanzamiento, considerando la aceleración constante de la gravedad.

## 2. Objetivo general

Aplicar el método numérico de Euler para aproximar la posición y velocidad de un cohete durante un intervalo de 20 segundos.

## 3. Datos iniciales

| Parámetro | Valor |
|---|---:|
| Altura inicial (y₀) | 0 m |
| Velocidad inicial (v₀) | 100 m/s |
| Gravedad (g) | 9.8 m/s² |
| Tiempo inicial | 0 s |
| Tiempo final | 20 s |
| Paso de integración (h) | 1 s |

## 4. Fundamento matemático

Se utilizan las siguientes ecuaciones:

**Velocidad:**

v(n+1) = v(n) - g × h

**Altura:**

y(n+1) = y(n) + v(n) × h

Donde:

- y: altura del cohete.
- v: velocidad del cohete.
- g: aceleración de la gravedad.
- h: tamaño del paso de tiempo.

## 5. Método numérico utilizado

Se utiliza el método de Euler explícito, que permite aproximar la solución de ecuaciones diferenciales mediante pequeños incrementos de tiempo.

En cada iteración se calcula primero la nueva velocidad y posteriormente la nueva altura utilizando la velocidad anterior.

## 6. Resultados de la simulación

Para los datos establecidos se obtienen los siguientes resultados:

- Tiempo de simulación: 20 segundos.
- Altura máxima aproximada: 561 metros.
- Tiempo en alcanzar la altura máxima: 11 segundos.
- Velocidad a los 20 segundos: -96 m/s.
- Altura a los 20 segundos: 138 metros.

La velocidad negativa indica que el cohete se encuentra descendiendo.

## 7. Funcionalidades de la página web

- Ingreso de los datos iniciales.
- Configuración del tiempo de simulación.
- Aplicación del método de Euler.
- Cálculo de la velocidad en cada segundo.
- Cálculo de la altura en cada segundo.
- Presentación de resultados mediante una tabla.
- Visualización del comportamiento del cohete durante el lanzamiento.

## 8. Tecnologías utilizadas

- HTML5: estructura de la página web.
- CSS3: diseño y presentación visual.
- JavaScript: cálculos matemáticos y aplicación del método de Euler.

## 9. Cómo ejecutar el proyecto

1. Descargar o copiar los archivos del proyecto.
2. Abrir la carpeta donde se encuentran los archivos.
3. Buscar el archivo `index.html`.
4. Abrirlo utilizando Google Chrome, Microsoft Edge u otro navegador.
5. Introducir los datos de la simulación y ejecutar el cálculo.

## 10. Conclusión

El desarrollo de este proyecto permite comprender la aplicación del método numérico de Euler en un problema físico real, como el lanzamiento vertical de un cohete.

Mediante la simulación se observa cómo la gravedad afecta progresivamente la velocidad y la altura del cohete, permitiendo analizar su ascenso y descenso a través de resultados numéricos.

---

**Proyecto académico – Métodos Numéricos**

**Tema:** Simulación del lanzamiento vertical de un cohete mediante el método de Euler.