[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=GilGarate21212743/sistema-presadepredador-lotkavolterra)

# Gemelos Digitales. Práctica 2: Sistema Presa-Depredador del modelo Lotka-Volterra [GilGarate-21212743]

## Autor
Gil Gárate Carlos Andrés 

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l21212743@tectijuana.edu.mx

## Resumen de la práctica
En esta práctica se analiza el modelo matemático de Lotka-Volterra para sistemas presa-depredador, el cual describe la dinámica poblacional de dos especies en interacción. A través de la implementación en MATLAB, se exploran distintos métodos numéricos para resolver las ecuaciones diferenciales que rigen el comportamiento de las poblaciones, permitiendo analizar su estabilidad y evolución en el tiempo. El modelo de Lotka-Volterra se basa en un sistema de ecuaciones diferenciales ordinarias (EDOs) que describe cómo cambia la población de presas y depredadores en función de ciertos parámetros, como las tasas de crecimiento, la tasa de depredación y la eficiencia de conversión de recursos. La implementación de este modelo en MATLAB permite visualizar la evolución de ambas especies y comprender los factores que influyen en su equilibrio o extinción.

Para la solución numérica del sistema, se emplean distintos métodos de integración. El método de Euler, una aproximación explícita de primer orden, proporciona una solución básica pero propensa a errores numéricos. Para mejorar la precisión, se utiliza el método de Heun, una variante de segundo orden que refina la estimación de la trayectoria de las poblaciones. Asimismo, se emplea el método de Runge-Kutta de cuarto orden, el cual ofrece una solución más precisa y estable, ampliamente utilizado en la simulación de sistemas dinámicos. A partir de las simulaciones realizadas, se analizan los ciclos poblacionales característicos del modelo, observando cómo la población de presas crece en ausencia de depredadores, mientras que la de depredadores disminuye sin una fuente de alimento. Se identifican puntos de equilibrio y se examina la estabilidad del sistema mediante distintas condiciones iniciales. Finalmente, se discute la aplicabilidad del modelo en escenarios ecológicos reales y sus limitaciones frente a factores no considerados, como la competencia inter-específica y la variabilidad ambiental.

## Objetivos específicos
1. Desarrollar un código en MATLAB para la simulación del modelo Lotka-Volterra.
2. Comparar la precisión y estabilidad de distintos métodos de integración numérica.
3. Analizar la dinámica poblacional y los puntos de equilibrio del modelo.
4. Discutir la aplicabilidad y limitaciones del modelo de Lotka-Volterra.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus de Biomatemáticas para la asignatura de Gemelos Digitales, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/s/6yf9afxzih9y458/Biomatematicas.pdf
[2] Levin, S. A., Hallam, T. G., & Gross, L. J. (Eds.). Applied mathematical ecology (Vol. 18). Springer Science & Business Media. (2012).

