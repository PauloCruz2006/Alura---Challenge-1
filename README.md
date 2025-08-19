# 🛒 Alura Store BR — Análises no Google Colab

## 📄 Descrição
Este projeto realiza uma análise completa dos dados de vendas da **Alura Store** do Seu João, aconselhando-o a vender uma de suas lojas para investir. 
Foi utilizado Python no Google Colab.  
O foco está em explorar métricas de desempenho das lojas, identificar padrões de consumo, medir satisfação do cliente e entender custos logísticos.

Os dados foram obtidos do repositório:
[alura-es-cursos/challenge1-data-science](https://github.com/alura-es-cursos/challenge1-data-science/tree/main/base-de-dados-challenge-1)

---

## 📊 Etapas da Análise

### 1. **Faturamento Total por Loja**
- **Objetivo:** Somar os valores de venda (`Preço`) para medir o desempenho total de cada loja.
- **Resultados:**
  - Loja 1: R$ 1.534.509,12
  - Loja 2: R$ 1.488.459,06
  - Loja 3: R$ 1.464.025,03
  - Loja 4: R$ 1.384.497,58
- **Insights:** Loja 1 lidera, enquanto Loja 4 apresenta menor faturamento.

### 2. **Vendas por Categoria**
- Agrupamento e contagem de produtos vendidos por categoria em cada loja.
- **Destaques:**  
  - **Top categorias:** Móveis e Eletrônicos concentram a maior parte das vendas.  
  - **Categorias de menor volume:** Instrumentos musicais, Livros e Utilidades domésticas.

### 3. **Média de Avaliação das Lojas**
- Cálculo da média das avaliações de clientes (`Avaliação da compra`).
- **Resultados:** Todas as lojas ficaram entre 3,98 e 4,05.
- **Insights:** Alto nível de padronização no atendimento; nenhuma loja alcançou a meta ideal de 4,5.

### 4. **Produtos Mais e Menos Vendidos**
- Identificação do item com maior e menor volume de vendas em cada loja.
- **Exemplo:** Loja 1 teve como mais vendido o **Micro-ondas (60)** e como menos vendido o **Headset (33)**.
- **Observação:** Preferências distintas entre lojas, sugerindo perfis de público diferentes.

### 5. **Custo Médio de Frete por Loja**
- Cálculo do custo médio de frete (`Frete`) para cada loja.
- **Resultados:** Variando de R$ 31,28 (Loja 4) a R$ 34,69 (Loja 1).
- **Insights:** Diferenças sugerem variação logística e oportunidades de otimização de custos.

---

## 🛠️ Tecnologias Utilizadas
- **Python**: Pandas, Matplotlib
- **Google Colab** para execução e experimentação
- **GitHub** como fonte de dados

---

## 📈 Visualizações
O notebook gera:
- Gráficos de barras para faturamento e custo de frete.
- Gráficos horizontais para vendas por categoria e produtos mais/menos vendidos.
- Análises textuais interpretando os resultados.

---

## 📌 Possíveis Extensões
- Analisar lucro líquido, considerando custos operacionais.
- Aplicar modelos preditivos para estimar vendas futuras.
- Integrar dashboards interativos (Plotly, Power BI).

---

## 👤 Autor
- **Nome:** Paulo Cruz 

---
📌 *Este README resume as análises do arquivo original `ipynb` criado no Google Colab.*
