## Projeto credit card holder

### Problem:
The total annual loans in Brazil is around R$ 5.3 trillion making this modality one of the most active in the financial sector. On this amount, the interest rate applies which represents the part of the profitability of the business. Thus, for success in this operation, it is necessary, logically, for the lender to receive faithfully the due interest and the borrowed amount. The certainty of receiving the profits and the loan amount must be ensured before the deal is closed..

O agrupamento de titulares de cartões de crédito é uma prática essencial para empresas administradoras de cartão de crédito. Essa estratégia traz a possibilidade de verificar em que grupo, cluster, o titular do cartão está inserido, podendo tanto receber algumas vantagens a mais no uso do cartão, como também sofrer alguma restrição conforme o grupo a que pertença.

### Motivation:
The need to know whether a loan will be duly received in full, with interest and adjustments, leads companies that work with lending money to look for ways to anticipate whether the borrower has the conditions and profile capable of faithfully repaying the amount borrowed. To this end, the company granting the loan needs to be aware of two fundamental issues for its security: knowing the percentage level of the borrower's risk and knowing, based on the level of this risk, whether or not to lend the negotiated amount.

- Gestão do Crédito
Um sistema de agrupamento bem estruturado ajuda a otimizar o crédito disponível para o titular, permitindo estender seu crédito, podendo comprar mais, ao mesmo tempo em que pode ter seu crédito restrito conforme o grupo que possa estar pertencente.

### Solution:
Using the company's own financial loan data, we will conduct an in-depth study and adaptation of this data. Several machine learning models, such as deep learning, will be trained, defining and choosing the model that best generalizes in the definition of defaulters and reveals the percentage level of risk of making a certain loan to a specific person. This will enable and support the financial loan team to make the best decision regarding the security percentage of that loan, reducing default events against the company.

Através de dados de utilização do cartão de crédito será utilizado algoritmos de machine learning para definir clusters de classificação do titular do cartão de crédito, agrupando os que são semelhantes em grupos que refletem a dinâmica do uso do cartão que revelará o nível de compromisso tanto no consumo quanto na cobertura desse consumo, revelando sua responsabilidade frente ao uso mais adequado no equilíbrio entre crédito e débito.

### Objective:
- This project aims to create clusters defined according to the characteristics of credit card holders, grouping these holders and characterizing the clusters based on the percentage occurring in the variables used.

- Esse projeto tem como objetivo criar clusters definidos conforme as características dos titulares de cartão de crédito, agrupando esses titulares e caracterizando os clusters a partir do percentual ocorrido nas variáveis de utilização do cartão de crédito.

### Data Origin:
- Dataset: https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

- The sample dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

- O Dataset de amostra resume o comportamento de uso de cerca de 9000 titulares de cartão de crédito ativos durante os últimos 6 meses. O arquivo está em um nível de cliente com 18 variáveis ​​comportamentais.

- A seguir está o Dicionário de Dados para o conjunto de dados de Cartão de Crédito:-

    CUST_ID : Identificação do titular do cartão de crédito (categórico)

    BALANCE : Valor do saldo restante na conta para fazer compras

    BALANCE_FREQUENCY : Com que frequência o saldo é atualizado, pontuação entre 0 e 1 (1 = atualizado com frequência, 0 = não atualizado com frequência)

    PURCHASES : Quantidade de compras feitas na conta

    ONEOFF_PURCHASES : Valor máximo de compra feita de uma só vez

    INSTALLMENTS_PURCHASES : Valor da compra feita em parcelas

    CASH_ADVANCE : Dinheiro adiantado dado pelo usuário

    PURCHASES_FREQUENCY : Com que frequência as compras estão sendo feitas, pontuação entre 0 e 1 (1 = compradas com frequência, 0 = não compradas com frequência)

    ONEOFFPURCHASESFREQUENCY : Com que frequência as compras estão acontecendo de uma só vez (1 = compradas com frequência, 0 = não compradas com frequência)

    PURCHASESINSTALLMENTSFREQUENCY : Com que frequência as compras em parcelas estão sendo feitas (1 = feitas com frequência, 0 = não feito com frequência)

    CASHADVANCEFREQUENCY : Com que frequência o dinheiro adiantado é pago

    CASHADVANCETRX : Número de transações feitas com "Dinheiro adiantado"

    PURCHASES_TRX : Número de transações de compra feitas

    CREDIT_LIMIT : Limite do cartão de crédito para o usuário

    PAYMENTS : Valor do pagamento feito pelo usuário

    MINIMUM_PAYMENTS : Valor mínimo de pagamentos feitos pelo usuário

    PRCFULLPAYMENT : Porcentagem do pagamento integral pago pelo usuário

    TENURE : Prazo do serviço de cartão de crédito para o usuário