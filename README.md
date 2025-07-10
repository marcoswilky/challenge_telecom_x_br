# Análise de Churn de Clientes - TelecomX_BR

Este projeto tem como objetivo analisar a evasão de clientes (churn) em uma empresa de telecomunicações, identificando padrões e fatores associados ao cancelamento de serviços. A análise foi realizada utilizando Python e bibliotecas como Pandas, NumPy, Matplotlib e Seaborn.

## 📦 Sobre o Projeto

A evasão de clientes é um dos principais desafios enfrentados por empresas de serviços recorrentes. Antecipar quais clientes têm maior propensão a cancelar permite criar estratégias de retenção mais eficazes.

Neste notebook, realizei:

- Extração dos dados de um dataset público.
- Limpeza, transformação e preparação dos dados.
- Análises estatísticas e visuais para identificar padrões de churn.
- Geração de insights e recomendações estratégicas.

## 🔗 Fonte dos Dados

Os dados utilizados estão disponíveis em:  
[TelecomX_Data.json](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json)

## ⚙️ Etapas do Projeto

### 1. Extração

- Importação dos dados diretamente de um arquivo JSON hospedado no GitHub.
- Conversão para DataFrame Pandas.

### 2. Transformação

- Verificação e tratamento de valores ausentes.
- Conversão de colunas binárias (Yes/No) para valores numéricos (0/1).
- Ajuste dos tipos de dados para facilitar análises.
- Renomeação de variáveis e rótulos para melhor visualização.

### 3. Análise

- Estatísticas descritivas por grupo de churn.
- Visualização da distribuição de churn (gráficos de barras e pizza).
- Análise de churn por variáveis categóricas (contrato, método de pagamento, dependentes, etc.).
- Análise de churn por variáveis numéricas (tempo de contrato, gastos mensais e totais).

## 📊 Principais Resultados

- **Taxa de churn:** Aproximadamente 26,5% dos clientes cancelaram o serviço.
- **Tipo de contrato:** Contratos mensais apresentaram maior evasão; contratos de 1 ou 2 anos mostraram maior fidelidade.
- **Método de pagamento:** Cheque eletrônico está associado a maior churn; métodos automáticos têm menor evasão.
- **Perfil de clientes:** Clientes sem dependentes ou parceiros e com pouco tempo de contrato são mais propensos a cancelar.
- **Gasto total:** Clientes que cancelaram tinham, em média, menor gasto total e menor tempo de contrato.

## 💡 Insights e Recomendações

- **Foco em novos clientes:** Programas de fidelidade ou benefícios nos primeiros meses podem reduzir churn precoce.
- **Incentivo a contratos longos:** Oferecer descontos ou bônus para contratos anuais ou bienais.
- **Promoção de pagamentos automáticos:** Incentivar métodos automáticos com cashback ou bônus.
- **Atenção a perfis de risco:** Monitorar clientes com contrato mensal, sem dependentes e com alta mensalidade.

## 🛠️ Como Executar

1. Clone este repositório.
2. Instale as dependências:
   ```sh
   pip install pandas numpy matplotlib seaborn requests
