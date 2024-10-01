# Simulated Annealing (Recozimento)
## Algoritmos de Otimização Estocásticos

### Descrição
O Simulated Annealing é um algoritmo de otimização inspirado no processo físico de recozimento, que envolve a adição de calor para modificar as propriedades de materiais. A ideia central é encontrar a melhor solução possível para um problema complexo, explorando um espaço de soluções de maneira eficiente.

### Funcionamento
O algoritmo começa com uma solução inicial e, a cada iteração, tenta aprimorar essa solução. Durante o processo, duas possibilidades podem ocorrer:
- **Aceitação de uma nova solução**: Se a nova solução for melhor do que a solução atual, ela é aceita imediatamente.
- **Aceitação de uma solução inferior**: Mesmo que a nova solução seja pior, há uma probabilidade de aceitação, que diminui ao longo do tempo. Isso permite que o algoritmo escape de mínimos locais e explore soluções mais amplas.

### Processo
1. **Início**: Começamos com uma solução inicial e uma temperatura elevada.
2. **Iterações**: Em cada iteração:
   - Uma nova solução é gerada.
   - A diferença de custo entre a nova solução e a solução atual é calculada.
   - Dependendo da diferença de custo e da temperatura atual, a nova solução pode ser aceita.
3. **Resfriamento**: A temperatura é gradualmente reduzida ao longo do tempo, diminuindo a probabilidade de aceitar soluções piores, até que uma solução satisfatória seja encontrada.

### Exemplo de Aplicação
O Simulated Annealing pode ser aplicado em diversos problemas, como:
- O problema do caixeiro viajante (TSP)
- Otimização de funções complexas
- Problemas de alocação de recursos

### Conclusão
O Simulated Annealing é uma técnica poderosa para resolver problemas de otimização, combinando a exploração estocástica com a aceitação controlada de soluções. Isso permite que ele encontre soluções eficazes mesmo em espaços de busca desafiadores.
