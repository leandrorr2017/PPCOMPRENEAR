#### Experimento sobre Descida de Gradiente e Taxa de Aprendizado

Esta atividade consiste em alterar o código de Aurélien Géron feito para o livro Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition

O código "In [17]" plota o gradiente (em batch) de uma regressão linear para três taxas de aprendizado (eta = η) diferentes:

Para η=0.002 (valor muito baixo para a base de dados usada), o gradiente desce muito lentamente e não chega em valores que solucionam o problema satisfatoriamente.
Para η=0.5 (valor alto para a base), o gradiente diverge, e a cada iteração se afasta dos valores ótimos.
Para η=0.1 (um bom valor para a base), o gradiente converge para valores bem próximos dos ótimos.
Esta atividade só vai usar o código até esta parte, podendo descartar as entradas de códigos seguintes. Porém, alguns códigos seguintes podem ser usados para implementar as modificações solicitadas.

Alterações a serem feitas:

Mudar o problema de regressão para classificação.
Criar várias bases para classificação binária.
Usar o SGDClassifier do scikit-learn.
Plotar os gráficos da descida de gradiente para cada base gerada, para pelo menos três valores de taxa de aprendizado:
muito pequena, de forma que o gradiente fique tão lento que não chegue próximo aos valores ótimos;
muito grande, de forma que o gradiente divirja;
um bom valor para que o gradiente chegue próximo aos valores ótimos.
Testar com diferentes funções de custo (loss function), e comparar o plot delas.

**Documentos disponibilizados**

  * Jupyther Notebook com o desenvolvimento em Python

  * Impressão PDF dos resultados
