# Rotação de Itens em 360 Graus

Este projeto demonstra a rotação de itens em um layout circular, distribuindo-os uniformemente em um círculo com base na sua posição. A rotação é calculada utilizando a seguinte fórmula:

\[
\text{Rotação em graus} = (\text{Posição} - 1) \times \left(\frac{360^\circ}{\text{Quantidade de itens}}\right)
\]

## Exemplo de Cálculo

Para um layout com 4 itens, a rotação de cada item é calculada da seguinte forma:

1. **Posição 1:**
(1-1)*(360deg/4) = 0 * 90deg = 0 deg
   
2. **Posição 2:**
  (2-1)*(360/4)= 1 * 90deg = 90 deg

3. **Posição 3:**
   (3-1)*(360/4)= 2 * 90 deg = 180 deg

4. **Posição 4:**
 (4-1)*(360/4)= 3 * 90deg = 270 deg


## Como Funciona

O código distribui os itens em um layout circular, atribuindo a cada um deles um valor de rotação baseado em sua posição na lista.

### Tecnologias Utilizadas

- **HTML**: Estrutura básica da página.
- **CSS**: Estilização dos itens e aplicação das transformações de rotação.


