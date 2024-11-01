# 6. Em uma empresa é adotado um método de Aprendizado de Máquina para detectar defeito de fabricação de peças mecânicas, sendo que raramente acontece este tipo de problema na fábrica. Um funcionário anuncia empolgado que o sistema alcançou uma acurácia de 99%, porém seu gerente não achou o resultado tão relevante. Responda:
### a. Por que o gerente não ficou empolgado com o resultado achado?
A acurácia é uma das métricas usadas para avaliar modelos de aprendizado de máquina que consiste na quantidade de acertos do modelo dividido pelo total da amostra. Para conjuntos de dados desbalanceados, em que uma classe aparece muito mais que a outra, a acurácia pode enganar.

Em um caso como esse, onde defeito de fabricação de peças mecânicas raramente acontece, o modelo poderia simplesmente classificar todas as peças como "sem defeito" e ainda assim alcançar uma alta acurácia, mas isso não ajudaria na identificação dos defeitos.

### b. O que o funcionário poderia fazer para confirmar se o método empregado é adequado para o problema?
Para avaliar melhor o desempenho do modelo, o funcionário poderia analisar a matriz de confusão, que mostra a quantidade de classificações corretas e incorretas. Além disso, ele poderia calcular métricas mais relevantes em casos de desbalanceamento, como o recall que mede a quantidade de casos positivos que foram corretamente identificados pelo modelo.

