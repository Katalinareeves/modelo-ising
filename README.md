# Modelo de Ising (1D y 2D) con algoritmo de Metropolis

Proyecto para el curso Progra 2 (PCFI 261), Solemne II.

Simulación del modelo de Ising mediante el algoritmo de Metropolis-Hastings:

1. **Ising 1D**: energía por espín, equilibración del sistema a distintas
   temperaturas, energía media y magnetización media en función de la
   temperatura, y calor específico a partir de la varianza de la energía.
2. **Ising 2D**: mismo algoritmo extendido a una grilla `L x L`, con
   visualización de configuraciones de espines a distintas temperaturas
   (incluyendo la transición de fase cerca de la temperatura crítica) y su
   energía en función de la temperatura.
3. Cada resultado se compara contra varias semillas (`seed`) para evaluar la
   variabilidad estadística de la simulación.

## Cómo correrlo

```
pip install numpy matplotlib
jupyter notebook ising.ipynb
```

El notebook está pensado para correrse de principio a fin sin datos externos.
