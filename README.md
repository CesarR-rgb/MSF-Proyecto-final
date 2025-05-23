[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=CesarR-rgb/MSF-Proyecto-final)
# Modelado de Sistemas Fisiológicos. Proyecto final: Sistema Endocrinor [Ramirez21212173]

## Autor
Cesar Andres Ramirez Diaz 

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: L21212173@tectijuana.edu.mx

## Objetivos general
Modelar mediante un circuito eléctrico análogo el comportamiento fisiológico del eje hipotálamo-hipófisis-tiroides (HHT), considerando la patología de hipotiroidismo subclínico. El modelo busca simular la dinámica del sistema endocrino en lazo abierto mediante componentes pasivos (R, L, C), obtener la función de transferencia, analizar la estabilidad del sistema, y plantear una solución mediante control PID.

## Fases
1. Seleccionar el sistema fisiológico a analizar, descripción del sistema mediante una analogía con un circuito RLC; indicar la enfermedad y los valores correspondientes para el caso y para el control; verificar la respuesta en lazo abierto en Multisim.
2. Calcular de forma análitica la función de transferencia, el error en estado estacionario y el modelo de ecuaciones integro-diferenciales; determinar la estabilidad en lazo abierto del caso y del control utilizando los valores numéricos para cada sistema; verificar que la respuesta en lazo abierto obtenida en Spyder (Python) y Simulink coincida con la respuesta de Multisim. 
3. Diseñar el controlador PID en Simulink; sintonizar las ganancias kP, kI y kD que permitan eliminar el error en la respuesta del caso; ilustrar los resultados (respuestas del control, del caso y del tratamiento) en un cuaderno computacional de MATLAB y en Spyder con lenguaje Python.
4. Elaborar el diagrama fisiológico en BioRender, de tal forma que permita visualizar las diferencias entre el caso y el control, identificando los componentes del circuito RLC análogo, las corrientes y diferencias de potencial, particularmente los componentes que cambian su valor en el caso y el control.
5. Construir el repositorio de GitHub con todos los resultados del proyecto.
6. Elaborar un ensayo gráfico que permita visualizar el trabajo realizado desde la descripción del sistema, análisis matemático, simulaciones numéricas, diagrama fisiológico y repositorio de GitHub.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus para la asignatura de Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/scl/fi/4gl55ccrjm9yulvziikxs/Modelado-de-Sistemas-Fisiologicos.pdf

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018.
