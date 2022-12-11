# Semantix_Academy_Projeto_Final
Projeto  realizado utilizando dados do Enem para conclusão do curso de Big Data Science da Semantix Academy .
<br>
<br>
Para a execução desse projeto foi utilizada a base de dados do Enem de 2021 disponibilizada pelo INEP
disponível no endereço <https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem>
<br>
 - Previsao_nota_redacao.ipynb<br>
 Neste arquivo foi realizada a modelagem dos dados da nota da redação do Enem para prever a nota final da redação sem ter acesso de todas as notas dos componentes que integram a nota final.<br>
 Para modelagem foi utilizada regressão multipla com o pacote sklearn.
 <br>
 <br>
 - Analise_Exploratoria_Dados_EDA.ipynb<br>
As análises desse arquivo ainda estão em construção, o objetivo principal é a criação de um dashboard com dados relevantes sobre o perfil dos participantes do Enem.
<br>
- Dados_enem_2021_limpeza.ipynb
Como a base de dados é muito grande esse notebook foi criado para limpeza e separação dos dados para serem utilizadas nas análises do projeto.
<br>
<br>
### Próximos passos:
    - Finalização da análise exploratória e criação do dashboard<br>
    - Construção de um crawler para o site do INEP onnde os dados são disponibilizados e utilizar os dados para fazer modelagem de séries temporais e previsões sobre aumento ou diminuição de participantes, acompanhamento das notas por estado em cada ano etc.<br>
    - Realizar um ETL em nuvem para armazenar e utilizar esses dados, uma vez que é um volume muito grande e exige uma capacidade de armazenamento e processamento relativamente grandes. O uso da biblioteca pandas também não é o mais adequado para este contexto, sendo que dentro dos próximos passos está planejada a utilização de pyspark para trabalhar com os Data Frames.
