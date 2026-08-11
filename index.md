---
title: Home
layout: home
nav_order: 1
description: "Just the Docs Pages."
permalink: /
has_children: false
---

1. Cursos de computación en física en la UdeA {: .fs-9 }
{:toc}

# Física computacional 1

[Repositorio GitHub.](https://github.com/anferivera/Fisica_Computacional_1/tree/main){:target="_blank"}
Tercer curso computacional en el pregrado de física de la UdeA. 

   1. En este curso abordamos una serie de técnicas numéricas para resolver algunas          Ecuaciones Diferenciales Parciales (EDP) de la física (física matemática) con condiciones de frontera. Por ejemplo:
      
      1. La ecuación de **Laplace**
      
         $$\nabla^2 u(\vec{r})=0$$
      
      2. La ecuación de **Poisson**
     
         $$\nabla^2 u(\vec{r})=-\dfrac{\rho(\vec{r})}{\epsilon}$$
      
      3. La ecuación de **difusión**

         $$\nabla^2 u(\vec{r},t)=\dfrac{1}{\alpha}\dfrac{\partial}{\partial t}u(\vec{r},t)$$
      
      4. La ecuación de **Onda**
      
         $$\nabla^2 u(\vec{r},t)=\dfrac{1}{v^2}\dfrac{\partial^2}{\partial t^2}u(\vec{r},t)$$
   
      5. La ecuación de **Schrödinger**
      
         $$-\dfrac{\hbar^2}{2 m}\nabla^2 \Psi(\vec{r},t) + V\Psi(\vec{r},t) = i\dfrac{\partial}{\partial t}\Psi(\vec{r},t)$$
      
      6. La ecuación de **Navier Stokes**
       
2. Abordamos la Física computacional del Análisis de Fourier

3. Métodos Montecarlo y Cadenas de Marcov

4. Introducción a la computación cuántica

5. Introducción a **c/c++**

## Programa oficial del curso
[Microcurrículo actualizado al 2026-2](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Programa/0302151_Fisica_Computacional_I_20262.pdf){:target="_blank"}

## Clases
Ver [Sesiones de clase](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones){:target="_blank"}
   1. [Pandas](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/pandas){:target="_blank"} Pandas is the premier Python Data Analysis Library, designed for fast, powerful, and flexible manipulation of "relational" or "labeled" data. It is a foundational tool in data science, finance, and machine learning, providing structures that function similarly to Excel spreadsheets or SQL tables.
   2. [Seabor](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/seaborn){:target="_blank"} Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative **statistical graphics**.
   3. [PDE-FDM](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/PDE){:target="_blank"}
      * **Finite difference method (FDM)**: solves partial differential equations (PDEs) by discretizing the continuous domain into a grid and replacing derivatives with algebraic finite difference approximations.
   4. [PDE-FEM](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/PDE){:target="_blank"}
      * **Finite element method (FEM)**: It is a numerical technique for solving complex engineering and physics problems by breaking a large, intricate system into smaller, simpler "finite elements". It solves differential equations (the "weak form") across these elements to predict behavior like stress, heat transfer, or fluid flow. 
   5. [Fourier](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/Fourier){:target="_blank"}
      * The Fourier Transform (**FT**) is a mathematical tool used to convert a signal from the time (or spatial) domain into the frequency domain. It shows what frequencies are present in a signal and how strong they are. Reveals hidden frequency information. Simplifies analysis of signals and systems. Helps filter noise, compress data, and analyze patterns. In this notebook we did an application to signal processing (audio, image, video).
   6. [MC](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/MC){:target="_blank"}
      * Monte Carlo (**MC**)  is computational algorithms based on repeated random sampling for obtaining numerical results. `use randomness to solve deterministic problems`. Monte Carlo methods are mainly used in:
         1. Numerical integration
         2. Optimization (**Markov Chain (MC)**)
         3. Non-uniform random variate generation
   7. [QC](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/QC){:target="_blank"}
      * Quantum computing (**QC**) is a theoretical area based on a computer that exploits quantum phenomena like superposition and entanglement. Its fundamental unit is the `qubit` instead of the classical `bits` units of 0,1. 
      * A simple `quantum circuit` is a collection of `qubits` and a list of instructions that act on those qubits.  In this section we learn `Qiskit` which is a software development kit created by `IBM` for working with quantum computers at the circuit, pulse, and algorithm levels. It provides tools for creating and manipulating quantum programs and **running them on prototype quantum devices in IBM Quantum Experience or on simulators on a local computer**.
   8. [c++](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Sesiones/c++){:target="_blank"}
      * (**c++**) lenguaje is a programming language designed in 1979 by Bjarne Stroustrup. C++ is a compiled, general-purpose programming language designed as an extension of the C language with support for object-oriented programming.It is known for its high performance, speed, and detailed control of hardware and memory, making it ideal for operating systems, video games, and critical software. 

## Laboratorios 
ver: [Labs](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Laboratorios){:target="_blank"}
      * Homework.
   1. [Lab 1: Análisis exploratorio de datos con PANDAS y NUMPY](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_1_pandas.ipynb){:target="_blank"}
   2. [Lab 2: Seaborn](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_2_seaborn.ipynb){:target="_blank"}
   3. [Lab 3: Diferencias finitas: DFM-Laplace](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_3_FDM-Laplace.ipynb){:target="_blank"}
   4. [Lab 4: Diferencias finitas: DFM-Capacitor](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_4_FDM_capacitor.ipynb){:target="_blank"}
   5. [Lab 5: Diferencias finitas: DFM-Diffusion](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_5_FDM_difussion.ipynb){:target="_blank"}
   6. [Lab 6: Elementos finitos: FEM-1D](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_6_FEM_1D.ipynb){:target="_blank"}
   7. [Lab 7: Transformada de Fourier: FFT-sonido](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_7_FFT.ipynb){:target="_blank"}
   8. [Lab 8: Monte Carlo MCMC](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_8_MCMC.ipynb){:target="_blank"}
   9. [Lab 9: Quantum Computing QC](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_9_QC.ipynb){:target="_blank"}
   10. [Lab 10: C++](https://github.com/anferivera/Fisica_Computacional_1/blob/main/Laboratorios/Lab_10_cpp.ipynb){:target="_blank"}

## Referencias
[Libros recomendados](https://github.com/anferivera/Fisica_Computacional_1/tree/main/Referencias){:target="_blank"}

### Asistencia a clases
[Control de asistencia]([https://udeaeduco-my.sharepoint.com/:x:/r/personal/afelipe_rivera_udea_edu_co/_layouts/15/Doc.aspx?sourcedoc=%7BD0EFCCC3-9585-4236-B633-92EF09F6E86E%7D&file=asistencia.xlsx&action=default&mobileredirect=true](https://udeaeduco-my.sharepoint.com/:x:/g/personal/afelipe_rivera_udea_edu_co/IQBtgkKBpHLjQaSM1g7flpOeAdEBaPzl_3SHVCUw9YW40zw?e=nUUbyH)){:target="_blank"}

---
   
# Métodos computacionales

Segundo curso computacional en el pregrado de física de la UdeA.  [Repositorio GitHub en construcción](https://github.com/anferivera/Metodos_Computacionales){:target="_blank"}

## Programa oficial del curso
[Microcurrículo actualizado al 2026-1]
## Clases
Ver [Sesiones de clase](https://github.com/anferivera/Metodos_Computacionales/tree/main){:target="_blank"}
   1. Clase 1: [1_1_overview_python](https://github.com/anferivera/Metodos_Computacionales/blob/main/1_1_overview_python.ipynb){:target="_blank"}
   2. Clase 2
   3. Clase 3
## Referencias

---

