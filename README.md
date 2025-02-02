# Análise de Acidentes Rodoviários

Este projeto analisa um conjunto de dados de acidentes rodoviários para identificar tendências e padrões relacionados a fatalidades.  O projeto utiliza visualizações para comunicar as descobertas de forma clara e concisa.

## Conjunto de Dados

O projeto utiliza o conjunto de dados "road_accident_dataset.csv", que contém informações sobre acidentes rodoviários em diferentes países e ao longo dos anos. As informações incluem data e hora do acidente, condições climáticas, tipo de estrada, número de veículos envolvidos, número de feridos e fatalidades, entre outros.

![image](https://github.com/user-attachments/assets/e5dd6ac4-751d-47aa-b960-161eb172025f)


## Pré-processamento de Dados

* **Tradução:** Os nomes das colunas foram traduzidos para o português para facilitar a compreensão.
* **Mapeamento de Países:** Os nomes de alguns países foram mapeados para suas respectivas traduções em português (ex: "USA" para "EUA").
* **Mapeamento de Meses:** Os nomes dos meses foram mapeados para suas respectivas traduções em português (ex: "January" para "Janeiro").
* **Agregação de Dados:** Os dados foram agregados para criar novas tabelas, como o número total de fatalidades por ano, por mês e por país.

![image](https://github.com/user-attachments/assets/a3552dbd-f350-423a-8822-3798a1b8933c)


## Visualizações

O projeto inclui os seguintes gráficos:

* **Gráfico de Linha - Número de Fatalidades por Ano (Seaborn):**  Este gráfico mostra a tendência do número total de fatalidades ao longo dos anos.

![image](https://github.com/user-attachments/assets/06151318-e7d3-496e-a894-b1450642b4af)



* **Gráfico de Barras Horizontal - Número de Fatalidades por Ano (Matplotlib):** Este gráfico apresenta o número de fatalidades para cada ano em um formato de barras horizontais.

![image](https://github.com/user-attachments/assets/dbac312e-74f2-427a-b1dd-901d525341b7)


* **Gráfico de Barras Vertical - Número de Fatalidades por Ano (Plotly):**  Este gráfico exibe o número de fatalidades por ano usando barras verticais e cores para representar a magnitude das fatalidades.

![image](https://github.com/user-attachments/assets/90a58df9-ddb3-4d47-b95c-bdf93c47c9ba)


* **Gráfico de Barras Vertical - Número de Fatalidades por Mês (Plotly):** Este gráfico mostra a distribuição das fatalidades ao longo dos meses do ano.

O objetivo deste gráfico é analisar em quais meses ocorrem mais acidentes, considerando todos os anos disponíveis.

Para ilustrar, imagine que em 2000, no mês de janeiro, ocorreram 3000 acidentes. Já em 2001, no mesmo mês de janeiro, foram registrados 4500 acidentes. Nesse caso, a soma total de acidentes em janeiro, considerando os dois anos, seria de 7500 acidentes. Esse é apenas um exemplo para explicar como a soma é feita.

A partir dessa análise, podemos concluir que, ao longo de todos os anos analisados, o mês de setembro foi o que apresentou o maior número de acidentes nas estradas.

![image](https://github.com/user-attachments/assets/5bb45200-ba80-47bb-b289-24abc2b3039f)


* **Gráfico de Barras Vertical - Número de Fatalidades por País (Plotly):**  Este gráfico compara o número total de fatalidades em diferentes países.

![image](https://github.com/user-attachments/assets/0a4e826a-8951-4c1a-9491-a18fb3f18c0f)

* **Gráfico de Pizza - Fatalidades ao Longo do Dia - Número de Fatalidades ao Longo do Dia (Plotly) 

![image](https://github.com/user-attachments/assets/0c92f0a0-0256-4643-bd19-b56c26f4227a)

* **Gráfico de Barras Vertical - Número de Fatalidades (Causas de Acidentes) (Plotly)

![image](https://github.com/user-attachments/assets/0cae35f5-cf06-45bf-af1d-b9b589a980ff)


