# Entrega 4

Si $\mathbf{A} \sim W_p(\Sigma, a)$ y $\mathbf{B} \sim W_p(\Sigma, b)$ son independientes, $\Sigma$ es
regular y $a \ge p$, la variable aleatoria
$$\Lambda = \frac{|\mathbf{A}|}{|\mathbf{A} + \mathbf{B}|}$$
tiene una ley Lambda de Wilks, $\Lambda(p, a, b)$, con parámetros $p$, $a$ y $b$.

La ley $\Lambda$ no depende del parámetro $\Sigma$ de $A$ y $B$, por lo que es suficiente considerarla
para $\Sigma = \mathbf{I}$. Tiene la misma distribución que un producto de $b$ v.a. independientes con
distribución Beta, es decir, si $L \sim \Lambda(p, a, b)$, entonces
$$L = \prod_{i=1}^b u_i, \text{ donde } u_i \sim \beta \left( \frac{a + i - p}{2}, \frac{p}{2} \right).$$

Genérese una muestra de tamaño $N$ de una ley $\Lambda$ de Wilks. Represéntese los resultados mediante
un histograma.

Link del repositorio de GitHub: https://github.com/Necrohades/entrega4