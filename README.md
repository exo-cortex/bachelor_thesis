# Chimera states in ensembles of fractally coupled oscillators

This is my bachelor thesis from 2016. It is an investigation of "chimera states" in networks with unusual "fractal" coupling schemes.
In networks of coupled oscillators two phenomena are typical: complete synchrony and complete asynchrony. When southeast-asian fireflies blink
in sync their collective state is one of synchrony. In some systems a hybrid state can exist where parts of the connected elements are oscillating in synchrony while the rest is oscillating uncorrelated. These hybrid states are called "chimera states".

In this work a process of creating [Cantor sets](https://en.wikipedia.org/wiki/Cantor_set) was used to derive a coupling scheme - "which oscillator is directly influencing which". In this work chimera states were identified and investigated closely as they also exhibit fractal properties like self-similarity. But also the the nonlocality of the connections which makes embedding the network difficult was discussed.

The simulations were made in python with numpy, scipy and [graph-tool](https://github.com/antmd/graph-tool) for integrating the large numbers of coupled differential equations. All plots and graphics were made procedurally in mathematica.
