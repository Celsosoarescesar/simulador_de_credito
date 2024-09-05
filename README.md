# Web_Finance_Simulator
Para executar a app:

1- Abra o terminal, navegue até a pasta com os arquivos e execute:

pipenv requirements > requirements.txt

2- Execute a app:

streamlit run app.py

Previsão do status do empréstimo
Preveja que o empréstimo será aprovado ou rejeitado para um solicitante.

Sobre o conjunto de dados
Neste conjunto de dados de Previsão de Status de Empréstimo, temos os dados de solicitantes que solicitaram o empréstimo anteriormente com base na propriedade, que é um Empréstimo Imobiliário.
O banco decidirá se concederá um empréstimo ao solicitante com base em alguns fatores, como renda do solicitante, valor do empréstimo, histórico de crédito anterior, renda do co-solicitante, etc.
Nosso objetivo é construir um modelo de aprendizado de máquina para prever se o empréstimo será aprovado ou rejeitado para um solicitante.
Sobre o arquivo loan_data.csv:
Loan_ID : Um ID de empréstimo exclusivo.
Gênero : Masculino ou feminino.
Casado : Casado (sim) ou Não Casado (Não).
Dependentes : Número de pessoas que dependem do cliente.
Educação : Educação do candidato (graduação ou pós-graduação).
Self_Employed : Autônomo (Sim/Não).
ApplicantIncome : Renda do requerente.
CoapplicantIncome : Renda do co-requerente.
LoanAmount : Valor do empréstimo em milhares.
Loan_Amount_Term : Termos do empréstimo em meses.
Histórico de crédito : o histórico de crédito atende às diretrizes.
Área_da_Propriedade : Os candidatos residem em áreas urbanas, semi-urbanas ou rurais.
Status do empréstimo : Empréstimo aprovado (S/N).
Meta:
Neste projeto, vamos classificar um indivíduo se ele/ela pode obter o valor do empréstimo com base em sua renda, educação, experiência de trabalho, empréstimo tomado anteriormente e muitos outros fatores.
Vamos nos aprofundar mais nisso, observando os dados.