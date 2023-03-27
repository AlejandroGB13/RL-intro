# RL-intro
Enlace a la [presentación](https://alejandrogb13.github.io/RL-intro/).
Cabe destacar que simplemente es una prueba de concepto de un proyecto mucho mayor.

# Proyecto Reactor

Este es un proyecto que tiene como objetivo modelar un reactor químico y encontrar las condiciones de operación óptimas para maximizar la producción de un producto deseado.

## Descripción del problema

Se tiene un reactor de volumen V que opera a una tasa de flujo volumétrico q. Se introducen tres reactivos A, B y C con concentraciones iniciales conocidas c0 = [Ca0, Cb0, Cc0]. La reacción que ocurre en el reactor es de segundo orden y se puede representar como:

A + B -> C

La velocidad de reacción está dada por la ecuación de Arrhenius:

k = k0 * exp(-Ea/(R*T))

donde k0 es el factor de pre-exponencial, Ea es la energía de activación, R es la constante de los gases y T es la temperatura.

La reacción es exotérmica y libera una cantidad de calor dada por deltaH.

Se desea encontrar la tasa de flujo volumétrico q óptima y las concentraciones finales de los reactivos que maximicen la producción del producto C.
