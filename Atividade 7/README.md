# Atividade 7

Faça o pseudocódigo para dois algoritmos que resolvem o problema da  Mochila Limitado 0/1, utilizando as técnicas de memorização e tabulação da Programação Dinâmica. Você deve enviar um arquivo no formato pdf, contendo o pseudocódigo dos dois algoritmos.

Implemente três algoritmos para resolver o problema da Mochila Limitado 0/1. O primeiro algoritmo deve ser um algoritmo básico, enquanto que os outros dois algoritmos devem utilizar as técnicas de memorização e tabulação da Programação Dinâmica. Todos os algoritmos devem ser implementados em python. Utilize o código fornecido pelo professor (em anexo) para testar os algoritmos e gerar um gráfico de desempenho. Você deve enviar o código dos algoritmos em um arquivo .TXT e a imagem do gráfico em um arquivo separado. Vocês devem adicionar no arquivo com o gráfico, os valores utilizados para WEIGHT_DOMAIN, PROFIT_DOMAIN e CAPACITY_PROBABILITY.

## Comentários

### Pseudocódigos:

knapSackMem: 
  - input: não é um peso W e sim uma lista de pesos! O mesmo para preço. Deveria falar mais sobre i e H
  - ouput: the maximum o que? The maximum sum of values of the items that can be loaded in the backpack
  - Linha 10 tá errada, porque não armazenou em H!
knapSacTab: 
  - input e output tem os mesmos problemas do anterior
  - Como tab não é recursiva, ela não precisa da função interna
  - Quais os valores de n e m na linha do algoritmo ksTab?
  - Nunca usar range em pseudocódigo!
  - Linha 11: n e m só existem dentro do loop e não deveriam ser acessadas fora dele!

### Códigos:

- knapSackNaive: ok
- knapSackMem: deveria escolher um nome melhor que hashTab para a memoria
- knapSacTab: ok
- Gráfico com 3 algoritmos: ok 
- Gráfico com 2 algoritmos: deveria ter feito com mais rounds para diminuir aquela barriga entre 200 e 300

## Nota

9.7/10
