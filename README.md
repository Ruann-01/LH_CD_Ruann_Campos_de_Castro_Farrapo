# LH_CD_Ruann_Campos_de_Castro_Farrapo
## Desafio Indicium - Ciência de Dados

Nesse repositório foi realizada uma análise exploratória de uma base de dados, além de treinar e testar modelos para a classificação das amostras em 2 grupos. 

## Como rodar o projeto? 
A forma mais simples de rodar o projeto é utilizando o serviço Google Colab. 

É necessário ter uma conta google e entrar no site: https://colab.research.google.com/

Depois desse passo, deve-se ir na aba Upload, e escolher o arquivo que você deseja executar ( Entrega_1_Data_Explorer.ipynb, Entrega_2_EDA.ipynb, Entrega_3_Predicted_Car_Tests.ipynb)

Ao abrir o arquivo no ambiente do Colab, vá na aba Arquivos na lateral esquerda e faça o upload das bases de dados wage_test.csv e wage_train.csv. 

As bibliotecas utilizadas já estão instaladas por padrão no ambiente do Colab.

Outra forma de rodar o projeto é utilizar o programa Jupyter, que vai ler os notebooks do projeto. Para executar nesse ambiente, você deve instalar as bibliotecas no ambiente que será executado os notebooks. Para instalar use: pip install -r requirements.txt

## Requirements   
As bibliotecas utilizadas foram: 
- pandas: Para manipulação das bases de dados
- matplotlib e seaborn: Para plotar os gráficos e histogramas
- scikit-learn: para utilizar os modelos de aprendizagem de máquina, além dos pré-processamentos e métricas de performance
- numpy: Para manipulação dos dados

## Arquivos
- Desafio.ipynb: Arquivo notebook com todo o desafio implementado
- Entrega_1_Data_Explorer.ipynb: Arquivo notebook da primeira entrega, sobre a exploração dos dados da base
- Entrega_2_EDA.ipynb: Arquivo notebook da segunda entrega, sobre a construção da EDA e as respostas das regras de negócio
- Entrega_3_Predicted_Car_Tests.ipynb: Arquivo notebook da terceira entrega, sobre a previsão dos preços dos carros
- predicted.csv: Arquivo csv com os rótulos previstos da base de teste
- requirements.txt: Bibliotecas necessárias para rodar o projeto
- cars_test.csv: Base de dados de teste
- cars_train.csv: Base de dados de treino