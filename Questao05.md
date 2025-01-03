# 5. Comente sobre a veracidade das afirmações:
### a. “Quanto mais variáveis de entrada forem usadas em um modelo de aprendizado de máquina, melhor será a qualidade do modelo”.
Quando adicionamos variáveis de entrada sem nenhum controle, o modelo pode acabar aprendendo com “ruídos”, ou seja, variações aleatórias e imprevisíveis nos dados que impactam a capacidade do modelo.

Além disso, nem todas as variáveis são úteis. Algumas não trazem informações relevantes e só aumentam a complexidade do modelo. Por exemplo, a cor de um objeto não é importante para se determinar a sua forma.

O uso de variáveis irrelevantes pode causar overfitting, onde o modelo funciona bem nos dados de treinamento, mas não consegue ter bons resultados em novos dados.

Portanto, a afirmação de que adicionar mais variáveis de entrada melhora a qualidade do modelo de aprendizado de máquina não é necessariamente verdade. O ideal é selecionar apenas as variáveis que realmente ajudam o modelo na tarefa para torná-lo mais preciso e confiável.

### b. “Independente da qualidade, quanto mais amostras forem obtidas para uma base de dados, maior a tendência de se obter modelos mais adequados”.
Ter mais dados geralmente melhora o modelo, pois quando treinados com grandes volumes de dados, eles tendem a ser mais precisos e menos tendenciosos. Com mais dados, o modelo aprende a generalizar melhor e evita o overfitting, que ocorre quando o modelo “memoriza” os dados de treinamento.

Mas a qualidade dos dados  também é importante. Dados limpos e precisos são fundamentais para o treinamento de modelos, pois se utilizarmos dados imprecisos ou não confiáveis, a precisão dos modelos pode ser afetada, levando a previsões incorretas.

Por isso, mais dados podem trazer benefícios, mas é importante garantir que eles sejam de boa qualidade.

### c. “Às vezes com simples manipulações na base de dados (limpeza, conversão de valores, etc.) pode-se conseguir melhoras significativas nos resultados, sem fazer nenhuma alteração na técnica de aprendizado de máquina usada”.
Como dito anteriormente, a qualidade dos dados é essencial para o sucesso do modelo de aprendizado de máquina. Sendo assim, para garantir essa qualidade é necessário aplicar um conjunto de técnicas para prepará-los de forma adequada. As principais técnicas para tratamento de dados em Machine Learning, são:

- Limpeza de dados

- Transformação dos dados

- Normalização dos dados

- Seleção de variáveis

Essas técnicas melhoram a qualidade dos dados, eliminando erros e inconsistências; aumentam a capacidade do modelo de fazer previsões corretas e tornam o treinamento do modelo mais rápido.
