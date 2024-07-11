# Resumo do Projeto

Este projeto explora a capacidade de tirar conclusões a partir de amostras utilizando diferentes conjuntos de dados. O foco está em entender distribuições, realizar reamostragens, aplicar o Teorema do Limite Central (TLC) e executar testes de hipóteses. Abaixo está o resumo dos principais tópicos abordados:

## 1. Conhecendo as Possibilidades

**Distribuições Analisadas:**
- Idade de Aposentadoria
- Tempo de Vida de uma Lâmpada
- Altura dos Funcionários

**Visualização:**
- Histograma das distribuições para entender a forma dos dados.

## 2. Reamostragens

**Processo:**
- Reamostragem de dados para calcular médias a partir de 100.000 amostras.
- Comparação entre médias populacionais e médias amostrais.

**Conclusão:**
- As médias amostrais são próximas das médias populacionais, demonstrando que amostras podem ser representativas da população.

## 3. Teorema do Limite Central (TLC)

**Experimento:**
- Distribuição das médias amostrais formando um padrão de sino, independentemente da distribuição original dos dados.

**Aplicação:**
- Estabelecimento de intervalos de confiança e entendimento da variabilidade dos dados.

## 4. Teste de Hipóteses

**Exemplo 1: Duração de Lâmpadas de Natal**
- **Hipótese:**
  - Testar se a duração média é diferente de 1570 horas.
- **Resultado:**
  - Rejeição da hipótese nula com um nível de confiança de 95%.

**Exemplo 2: Tempo de Resposta de Suporte Técnico**
- **Hipótese:**
  - Testar se o tempo médio de resposta é menor que 30 minutos.
- **Resultado:**
  - Não rejeição da hipótese nula.

**Exemplo 3: Impacto da Propaganda nas Vendas**
- **Hipótese:**
  - Verificar se a propaganda aumenta as vendas.
- **Resultado:**
  - Comparação das vendas com e sem propaganda utilizando teste t para duas amostras independentes.

## Conclusões

O projeto demonstra a importância de amostras para tirar conclusões sobre populações maiores, a aplicação do TLC para entender a distribuição das médias amostrais, e a utilização de testes de hipóteses para validar suposições com base em dados reais.

## Bibliotecas Utilizadas
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `statsmodels`

Este projeto mostra como a análise estatística pode ser aplicada em diferentes contextos para obter insights significativos e apoiar a tomada de decisões.
