# Forecast Challenge

## Sumário

- [Projeto](#projeto)
- [Base de dados](#base-de-dados)
- [Descrições dos arquivos](#descrições-dos-arquivos)

## Projeto

O objetivo deste desafio é prever a quantidade de ocorrências de acidentes de trânsito do próximo dia. Desta forma deseja-se utilizar a quantidade de ocorrências
do dia t-1, t-2, t-n para prever o dia t, no qual n é o número máximo de lags (janela temporal). Para o projeto, recomendo a leitura do livro 'Introduction to Time Series Forecasting with Python' de Jason Brownlee. 

## Base de dados:
 - Ocorrências de acidentes de trânsito na cidade de Recife, contendo ocorrências entre os anos de 2015 e 2019;
- Será necessário transformar os dados disponíveis em uma série temporal diária YYYY-MM-DD (iniciando de 2015-06-01 até 31-12-2019), contendo a quantidade de acidentes de trânsito do dia;
- Dica: para criar a série temporal desejada, basta utilizar a coluna “data” para identificar a quantidade de ocorrências do dia;

## Descrições dos arquivos

 - **preProcessingData**: Análise descritiva da série temporal
      - 1.1. Existem lags relevantes?
      - 1.2. A série é estacionária? Baseado em qual análise?
      - 1.3. Quais outras estatísticas podem ajudar no entendimento da distribuição?
 - **modelTraining**: Modelagem, sugerir um modelo para prever a série temporal
      - 2.1. Avaliação de modelos;
      - 2.2. Treinar e ter resultados de diferentes modelos
      - 2.3. Exibir resultados no conjunto de teste do melhor modelo. O conjunto de teste compreende o todo ano de 2019 (os últimos 365 pontos) 
      - 2.4. Métricas
      - 2.5. É possível adicionar outras variáveis para ajudar no processode previsão? Quais? melhoraram os resultados?
      - 2.6. Conclusão
