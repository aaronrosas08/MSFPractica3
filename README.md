[![Open in MATLAB Online]

# Práctica: Sistema musculoesquelético 

## Información del estudiante

Aaron Raul Rosas Montoya \[23210716]; l23210716@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Transformar el modelo mecánico a un circuito eléctrico usando la analogía fuerza-voltaje: F(t) ↔ V(t), x(t) ↔ I(t), amortiguadores(R), complianzas(C), masas(L).
2. Determinar el modelo de ecuaciones integro-diferenciales.
3. Determinar el error en estado estacionario y la estabilidad del sistema.
4. Construir el diagrama de bloques del sistema en Simulink.
5. Diseñar y sintonizar las ganancias kP, kI y kD con el bloque *PID Controller* y la herramienta *Tune* de Simulink.
6. Obtener la respuesta de t en lazo abierto y cerrado usando Python y Simulink 
7. Elaborar el diagrama del sistema con BioRender.com.

## Descripción detallada del sistema

El modelo musculoesquelético considera los siguientes elementos y supuestos:

La configuración paralela impone restricciones mecánicas entre los componentes:
si **Cₚ** se extiende una longitud incremental **x(t)**, la combinación serie de **R** y **Cs**
se extiende la misma longitud. La fuerza total **F(t)** es la suma de las fuerzas en ambas ramas,
mientras que las extensiones individuales de **Cs** y **R** no necesitan ser iguales.

- *F₀* — Fuerza del elemento contráctil activo del músculo, donde F₀ = αF(t), con 0 < α < 1.
- *R* — Amortiguamiento viscoso inherente al tejido muscular.
- *Cₚ* — Elemento elástico en paralelo; refleja las propiedades de almacenamiento del sarcolema.
- *Cs* — Elemento elástico en serie; refleja las propiedades elásticas de los tendones.

*Palabras clave:* Modelo musculoesquelético; Fuerza-voltaje; Sarcolema; Amortiguamiento viscoso; Superposición.

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB \[.mlx].
2. Modelo de Simulink \[.slx].
3. Archivos de Spyder \[.py].
4. Imagen con los parámetros del controlador.
5. Imágenes de las simulaciones \[.pdf].
6. Evidencia del análisis matemático: función de transferencia, modelo de ecuaciones integro-diferenciales, error en estado estacionario y estabilidad en lazo abierto.
7. Modelo fisiológico en Biorender o BioArt.

## Referencias

[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.

[4] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 2, Page 26.

