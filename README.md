<header>
<img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Logo_UTFSM.png" width=200 alt="UTFSM" align="left"/>
<img src="./imagenes/dmat.png" alt="DMAT" align="right"/>
</header>
</br></br></br></br></br>

# Conservación e interacción dinámica de especies nativas y exóticas en una reserva ecológica

[![MAT281 Badge](https://img.shields.io/badge/Proyecto-Memoria-green)](#)

Repositorio de la memoria ‘Conservación e interacción dinámica de especies nativas y exóticas en una reserva ecológica’, que incluye modelos matemáticos y simulaciones numéricas para estudiar la interacción y conservación de las especies

---

## Problemática

En muchas reservas ecológicas, la introducción de especies exóticas puede alterar el equilibrio natural, afectando la supervivencia de especies nativas y la dinámica de los ecosistemas. La correcta gestión de estas especies requiere herramientas que permitan predecir cómo distintas estrategias de manejo afectan la coexistencia de especies.

![Esquema ecológico](./imagenes/esquema_ecosistema.png)  

*Figura: Esquema ilustrativo de interacción entre especies nativas y exóticas.*

---

## Objetivos

- Analizar la dinámica poblacional de especies nativas y exóticas mediante modelos matemáticos.  
- Evaluar el efecto de distintas estrategias de manejo (replantación, tala) sobre la supervivencia de las especies.  
- Desarrollar herramientas de simulación numérica en MATLAB para explorar distintos escenarios de conservación.

---

## Metodología

1. **Modelación Matemática**  
   Se desarrollaron sistemas de ecuaciones diferenciales no lineales para modelar la dinámica de tres especies.

2. **Análisis de Puntos Críticos y Estabilidad**  
   Se determinaron los puntos de equilibrio y su estabilidad según distintas condiciones y estrategias.

3. **Simulación Numérica en MATLAB**  
   Se realizaron simulaciones temporales y espaciales para estudiar la evolución de las poblaciones.

4. **Estudio de Estrategias de Manejo**  
   Se evaluaron estrategias como tala constante, tala periódica y replantación proporcional.

![Simulación ejemplo](./imagenes/simulacion_ejemplo.png)  

*Figura: Ejemplo de simulación de dinámica poblacional.*

---

## Contenido del Repositorio

- **memoria_y_presentacion/**  
  Contiene el PDF de la memoria completa y la presentación utilizada para la defensa.  

- **codigos_matlab/**  
  Contiene todos los códigos MATLAB organizados por estrategia de manejo:
  - `estrategia1/`: análisis de estabilidad de puntos de equilibrio.
  - `estrategia2/`: simulaciones con replantación proporcional.
  - `estrategia3/`: estudios de tala periódica y trayectorias 3D.

- **imagenes/**  
  Carpeta con imágenes usadas en el README (logos, diagramas, resultados).

---

## Resultados principales

- Identificación de regiones de supervivencia para cada especie según estrategia de manejo.  
- Gráficos 3D de trayectorias de poblaciones bajo distintos escenarios.  
- Comparación de estrategias de conservación y sus efectos sobre la coexistencia de especies.

![Resultados ejemplo](./imagenes/resultados.png)  

---

## Requisitos

- MATLAB (versión recomendada: R2023a o superior)  
- Toolboxes: Symbolic Math, MATLAB Graphics  

---

## Uso

Cada subcarpeta en `codigos_matlab` contiene scripts independientes que permiten reproducir los análisis y gráficos presentados en la memoria. Ejecutar los scripts según la estrategia de interés para explorar los resultados.

---

## Referencias

1. Acosta-Arreola, et al. (2023). *Modelo II-B y estrategias de manejo de especies.*  
2. Aguirre, P. (2020). *Ecuaciones diferenciales y sistemas dinámicos.*  
3. Aguirre, P. (2021). *Modelos biomatemáticos y bifurcaciones.*

---

