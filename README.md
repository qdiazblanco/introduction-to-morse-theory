# Introducción a la Teoría de Morse

Trabajo de Fin de Grado entregado para la obtención del Grado en Matematicas por la Universidad Complutense de Madrid (UCM).

El trabajo se estructura entorno al libro de John Milnor "Morse Theory" y busca presentar de manera lo más autocontenida posible los fundamentos de la *teoría de Morse*; desde el lema de Morse hasta las desigualdades de Morse. Con este fin, se incluye un tercer capítulo de introducción a la teoría de homología desde los puntos de vista simplicial y celular. 

Como objetivo secundario se intenta que el trabajo tenga valor didáctico y sirva como fuente sólida para el aprendizaje de la teoría de Morse.


### Resumen
La teoría de Morse permite extraer de una variedad información sobre sus invariantes topológicos mediante el estudio de los puntos críticos de funciones diferenciables con valores reales.

Dada una función diferenciable $f:M\to \mathbb{R}$ sobre una variedad $M$, el lema de Morse establece que alrededor de todo punto crítico no degenerado existe un sistema local de coordenadas respecto del cual $f$ se expresa como una forma cuadrática. Esto tiene como consecuencia que los puntos críticos no degenerados son aislados y constituye el primer pilar de la teoría de Morse, encargada de estudiar precisamente las funciones cuyos puntos críticos son todos no degenerados. Estas funciones se conoces como funciones de Morse. 

La importancia de la teoría de Morse radica en que permite determinar la topología de una variedad a partir de los puntos críticos de una función de Morse. Concretamente, si los conjuntos subnivel de una función $f$ de Morse son compactos, se puede relacionar el tipo de homotopía de la variedad con el de un CW-complejo con tantas celdas de dimensión $\lambda$ como puntos críticos de índice $\lambda$ tenga $f$. Por otro lado, las desigualdades de Morse determinan cotas para los números de Betti de una variedad y permiten computar su característica de Euler-Poincaré en función únicamente del número de puntos críticos de cada índice posible de una función de Morse.

### Índice general de la memoria

1. Funciones de Morse. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5

    1.1. Preliminares y notación . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
    1.2. El Lema de Morse. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
    
2. La estructura de CW-complejo de una variedad . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15

    2.1. CW-Complejos y tipo de homotopía . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
    2.2. Sobre el pegado de λ-celdas. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
    2.2.1. Aplicaciones de los teoremas sobre el pegado de λ-celdas . . . . . . . . . . . . . . . . . . . 33

3. Introducción a la homología. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37

    3.1. Homología simplicial . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37
    3.1.1. Triangulaciones. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38
    3.1.2. Construcción de la homología simplicial. . . . . . . . . . . . . . . . . . . . . . . . . . . . 40
    3.2. Homología celular. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
    3.3. Homología relativa . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 47
    3.4. Otros invariantes relacionados con la homología. . . . . . . . . . . . . . . . . . . . . . . . . 49

4. Desigualdades de Morse . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51

    4.1. Subaditividad. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51
    4.2. Las desigualdades. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 54

Bibliografía . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  57






# Introduction to Morse Theory

### Abstract
Morse theory allows us to extract from a manifold information about its topological invariants by studying the critical points of real-valued differentiable functions.

Given a differentiable function $f:M\to \mathbb{R}$ over a manifold $M$, Morse's lemma establishes that around every non-degenerate critical point there exists a local coordinate system with respect to which $f$ is expressed as a quadratic form. This, in turn, implies that non degenerate critical points are isolated and constitutes the foundation of Morse Theory, which studies functions whose critical points are all non-degenerats. These functions are called Morse functions.

The importance of Morse theory lies in the fact that it allows one to determine the topology of a manifold from the critical points of a Morse function. In particular, if all sublevel sets of a Morse function $f$ are compact, it is possible to relate the homotopy type of a manifold with that of a CW-complex with as many cells of dimension $\lambda$ as critical points of index $\lambda$ $f$ has. In addition, Morse inequalities determine bounds for the Betti numbers of a manifold and let us compute its Euler-Poincaré characteristic relying only on the number of critical points of each possible index of a Morse function.