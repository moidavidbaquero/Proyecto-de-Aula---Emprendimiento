
# Proyecto Final — Métodos Numéricos

## Descripción
Este proyecto implementa y compara los métodos numéricos abiertos **Newton-Raphson** y **Müller** para la búsqueda de raíces de polinomios.  
La aplicación permite visualizar el proceso iterativo, el comportamiento de convergencia y las raíces reales y complejas obtenidas.

## Objetivo
Desarrollar una herramienta educativa en Python que permita:
- Resolver polinomios mediante Newton-Raphson y Müller.
- Comparar velocidad de convergencia y estabilidad.
- Visualizar iteraciones y errores relativos.
- Analizar raíces reales y complejas.

---

# Métodos Implementados

## Método de Newton-Raphson
Método iterativo basado en la derivada de la función.

### Características
- Convergencia cuadrática.
- Alta velocidad de convergencia.
- Requiere derivadas.
- Funciona mejor con funciones suaves y continuas.

### Fórmula
x_(n+1) = x_n - f(x_n) / f'(x_n)

### Aplicación en el proyecto
Se utiliza para detectar el punto de saturación del sistema y analizar estabilidad en funciones regulares.

---

## Método de Müller
Método iterativo basado en interpolación parabólica usando tres puntos.

### Características
- No requiere derivadas.
- Puede encontrar raíces complejas.
- Convergencia superlineal (~1.84).
- Funciona bien con funciones irregulares.

### Aplicación en el proyecto
Se utiliza para detectar oscilaciones e inestabilidades en el comportamiento del sistema.

---

# Tecnologías Utilizadas

- Python 3.11
- NumPy
- SymPy
- Matplotlib
- Tkinter
- Git y GitHub

---

# Funcionalidades

- Ingreso de polinomios mediante coeficientes.
- Ejecución de Newton-Raphson y Müller.
- Visualización de iteraciones.
- Cálculo de error relativo.
- Diagramas de polos en el plano complejo.
- Comparación entre ambos métodos.

---

# Estructura del Proyecto

- Representación del polinomio.
- Métodos numéricos.
- Interfaz gráfica.
- Visualización y análisis.

---

# Comparación de Métodos

| Newton-Raphson | Método de Müller |
|---|---|
| Convergencia cuadrática | Convergencia superlineal |
| Requiere derivadas | No requiere derivadas |
| Solo raíces reales | Puede hallar raíces complejas |
| Más rápido | Más robusto |
| Funciones suaves | Funciones irregulares |

---

# Conclusión
Ambos métodos son complementarios.  
Newton-Raphson permite encontrar rápidamente puntos críticos del sistema, mientras que Müller aporta flexibilidad y capacidad para detectar comportamientos oscilatorios e inestables.

La combinación de ambos métodos proporciona un análisis más completo y preciso del comportamiento del sistema.

---

# Autores
- David Santiago Vargas Parra
- Moises David Baquero Daza
- Jose Daniel Nova Muñoz

Universidad de Santander — Métodos Numéricos
