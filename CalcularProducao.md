Pense em um jogo estilo Civilization. No jogo, precisamos calcular a produção de cada território, que depende de sua população, tecnologia e status (ocupado ou não). Para isso, criamos uma função `CaularProducao`, que retorna um `int` representando a produção de um território. A função recebe 2 parâmetros: um `int` populacao e um `int` tecnologia. A produção será igual a população x tecnologia.

### Parte 2

Acrecente um parâmetro  `string` status. Se o status for "ocupado", a produção será 0. Senão, o retorno é o mesmo que antes.
