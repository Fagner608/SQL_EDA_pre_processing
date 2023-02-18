# SQL_EDA_pre_processing

# Pré-processamento em python, e análise exploratória de dados em SQL, de influências sobre notas de estudantes [kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
Projeto autônomo, visando demonstrar conhecimento teórico e prático nos tópicos descritos abaixo.



- Pré-processamento, análise, visualização, geração de insights em SQL usando AWS Athena e S3. O projeto visa demonstrar como tratar e realizar o split de uma base de dados, após, realizando o carregamento no AWS S3. A análise exploratória é direcionada para, para responder às questões de negócio levantadas.

  
Objetivo: em um primeiro momento, aplicar o pré-processamento aos dados, para que possam ser objeto de querys em linguagem SQL. Em um segundo momento, será realizada análise para validar as hipóteses levantadas no início da pesquisa.


Fonte dos dados: 


1 - Dados foram obtidos no [kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).

## Tecnologias Utilizadas


- Python para:

  * Pré-processamento.
  
- AWS S3 para:

  * Armazenar os dados.

- AWS Athena para:

  * Criar as tabelas e executar os comandos SQL.

- SQL:

  * Realizar a análise exploratória.

  

- Conceitos aplicados:

  * Programação orientada à objetos

  * Pré-processamento de dados

  * Data-wrangling com SQL
    
  * Visualização de dados com python
  
  * Engenharia de atributos com SQL
  
    
## Funcionalidades


- A analise foi conduzida para, ao final, compreender a influência dos antecedentes dos pais, preparação para testes, etc., no desempenho dos alunos.

## Visualizar


1 - Acesse clicando no arquivo acima com extensão '.ipynb', neste repositório, ou


2 - Faça o clone do repositório para participar deste projeto.

## Resultados


Como resultado da análise, ficou caracterizada a influência de dois fatores nas notas dos alunos:

    I - a formação acadêmica dos pais.


![image](https://user-images.githubusercontent.com/96034581/219838063-3c7991ea-e73b-4adf-929b-30bffc96c5e3.png)

  # Visualizando:
  
  ![image](https://user-images.githubusercontent.com/96034581/219838178-54e6836b-f879-4ada-8545-f0ee88890fb0.png)

    II - a conclusão dos cursos preparatórios.:

![image](https://user-images.githubusercontent.com/96034581/219838338-04cc30d0-8ad2-474d-8315-df9a84adee1f.png)

    # Visualizando:

![image](https://user-images.githubusercontent.com/96034581/219838432-c3bee639-99bc-4314-8e8c-668ea32931bc.png)


## Conclusão


Ficou caracterizada a influência de dois fatores nas notas dos alunos:

    I - a formação acadêmica dos pais,
    II - a conclusão dos cursos preparatórios.
Explicando:

Em relação à formação acadêmica dos pais, ficou bastante caracterizado, no primeiro gráfico que há influência na nota obtida pelo aluno, sendo que, a maior média obtida é, justamente, do grupo de alunos cujos pais possuem educação acadêmica, e, a menor média é a dos alunos cujos pais frequentaram apenas o ensino médio.

Em relação ao segundo fator, já no segundo gráfico, percebe-se que, realizando novo split no grupo_e, a média das notas sobe ainda mais. Os alunos do group_e, cujos pais tem formação universitária, e, os alunos finalizaram os cursos preparatórios, a média foi superior a 80.

Portanto, validada a hipótese de que, a formação acadêmica dos pais, e a realização de cursos preparatórios ajudam no desempenho dos alunos.


## Referências


Fonte dos dados: 


1 - [kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
