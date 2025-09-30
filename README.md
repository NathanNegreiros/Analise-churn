# 📊 Análise de Churn
Projeto de análise de churn realizado no Google Sheets, explorando hipóteses e insights de negócio.

---

## 🔎 Hipóteses e Resultados da Análise

### 🟢 Hipótese 1: O primeiro mês é o mais crítico para o cliente entrar em churn?

![Gráfico de Barras - Churn por Mês](grafico_barras.jpg)

✅ **Verdadeiro**  
A análise mostrou que os três primeiros meses após a compra concentram as maiores taxas de churn:

- **1º mês** → pico mais alto de cancelamentos  
- **Até o 3º mês** → churn ainda se mantém elevado  
- **A partir do 3º mês** → começa a se estabilizar  
- **Após o 6º mês** → queda significativa no churn, indicando início da fidelização  

💡 **Insight:** os três primeiros meses são cruciais para a retenção do cliente, exigindo maior atenção e esforço em ações de engajamento.

---

### 🟠 Hipótese 2: A taxa de churn da empresa é de 30%?

![Gráfico de Linhas - Queda do Churn](grafico_linhas.jpg)

⚠️ **Parcialmente verdadeiro**  
O cálculo mostrou uma taxa de **26,54% no total**. Apesar de estar abaixo dos 30%, ainda é um valor próximo e relevante.  

💡 **Insight:** a taxa de churn gira em torno de 26% — ou seja, aproximadamente **1 em cada 4 clientes cancela**.

---

### 🔴 Hipótese 3: A taxa de churn ao longo do tempo de ativação é crescente?

![Gráfico de Linhas - Evolução do Churn](grafico_linhas.jpg)

❌ **Falso**  
Os dados indicam o contrário:  

- Nos primeiros meses → taxa é alta  
- A partir do 3º mês → estabiliza  
- Após o 6º mês → cai de forma acentuada  

💡 **Insight:** quanto mais tempo o cliente permanece, menor a chance de cancelamento.  
Isso mostra que esforços de retenção **nos primeiros meses trazem retorno no longo prazo**.

---

### 💳 Hipótese 4: A maior taxa de churn ocorre em clientes que pagam por boleto?

![Gráfico de Pagamentos - Churn por Método](grafico_pagamentos.jpg)

✅ **Verdadeiro**  
O método de pagamento **boleto (electronic check)** apresentou as maiores taxas de churn, mesmo com pequenas variações em alguns meses.  

💡 **Insight:** clientes que utilizam **boleto têm maior risco de cancelar**.  
A empresa deve rever essa política, incentivando ou migrando clientes para outros métodos de pagamento.

---

## 📌 Conclusões Gerais

- Os três primeiros meses após a compra são o período mais crítico e devem receber **esforços concentrados de retenção**.  
- Se o cliente permanecer até o sexto mês, a probabilidade de churn cai consideravelmente.  
- A empresa deve **rever a política de pagamento via boleto**, já que esse meio está associado a maior risco de cancelamento.
