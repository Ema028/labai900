# labai900
modelo para previsão de aluguel de bicicletas com azure


1.Criar um azure machine learning workspace
2.Criar um novo trabalho de ML automatizado com as configurações:
  Tarefa: Regressão
  Tipo de dados: Tabular
  Fonte de dados: Web files
  Web URL: https://aka.ms/bike-rentals
3. Selecionar os dados e continuar com as configurações:
  Coluna de dados: rentals (integer)
  Configurações adicionais:
    Métrica primária: NormalizedRootMeanSquaredError
    Explicar melhor modelo: não selecionado
    Modelos Permitidos: RandomForest e LightGBM
  Limites:
    Máximo de avaliações: 3
    Máximo de avaliações simultâneas: 3
    Máximo de nós: 3
    Limite de pontuação métrica: 0,085
    Tempo limite de experimento: 15
    Tempo limite de iteração: 15
4. Enviar trabalho
  
