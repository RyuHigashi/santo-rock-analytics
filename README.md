# 🎸 Santo Rock Analytics

Análise de dados de um bar de música ao vivo utilizando Python, Pandas e técnicas de ciência de dados para extrair insights operacionais e apoiar decisões estratégicas.

---

## 📊 Sobre o Projeto

Este projeto consiste em uma análise exploratória de dados (EDA) de vendas e faturamento de um estabelecimento de entretenimento que opera 5 dias por semana (quarta a domingo) com música ao vivo.

O objetivo é identificar padrões de consumo, sazonalidade, comportamento do público e oportunidades de otimização operacional através da análise de dados reais de sistemas de ponto de venda (POS).

---

## 🎯 Objetivos

- Identificar dias da semana com maior faturamento
- Analisar variação mensal e tendências
- Detectar eventos automaticamente usando gaps de vendas
- Visualizar padrões de consumo ao longo do tempo
- Fornecer insights acionáveis para decisões de negócio

---

## 🔧 Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação e análise de dados
- **Matplotlib** - Visualização de dados
- **Power Query** - Limpeza e transformação de dados
- **Google Colab** - Ambiente de desenvolvimento
- **Excel** - Armazenamento e organização

---

## 📈 Principais Insights

### 💰 Faturamento por Dia da Semana
- **Sábado** é o dia mais lucrativo (fatura quase 5x mais que Quarta)
- **Quarta-feira** apresenta o menor faturamento
- Quinta e Sexta têm performance intermediária similar
- Domingo apresenta faturamento moderado

### 📅 Evolução Mensal
- **Janeiro**: Melhor mês do trimestre analisado
- **Fevereiro**: Manteve o ritmo (queda de apenas 1,6%)
- **Março**: Queda significativa de 13% em relação a Fevereiro

### 📊 Padrões Identificados
- Aproximadamente 21 eventos por mês detectados
- Alta variabilidade no faturamento entre eventos
- Março apresentou maior instabilidade (maior amplitude entre eventos fortes e fracos)
- Janeiro demonstrou performance mais consistente

---

## 🛠️ Metodologia

### 1. Coleta de Dados
- Exportação de dados de sistema POS (MEEP)
- Período analisado: 3 meses (Janeiro a Março de 2026)

### 2. Limpeza e Preparação
- Remoção de duplicatas
- Tratamento de valores nulos
- Filtro de transações confirmadas
- Exclusão de lançamentos internos (Cashless)
- Padronização de tipos de dados

### 3. Detecção de Eventos
Implementação de algoritmo de detecção automática:
- Gap > 4 horas sem vendas = novo evento
- Permite análise correta de eventos overnight (18h - 05h)
- Identificação de 63 eventos no período

### 4. Análise Exploratória
- Estatísticas descritivas por período
- Análise de tendências temporais
- Identificação de outliers
- Visualizações comparativas

---

## 📁 Estrutura do Projeto

- `README.md`
- `dados/`
  - `exemplo_amostra.csv` (dados fictícios para demonstração)
- `notebooks/`
  - `analise_exploratoria.ipynb`
- `.gitignore`


---

## 🚀 Como Usar

### Pré-requisitos
```bash
pip install pandas matplotlib jupyter
```

### Executar Análise
1. Clone o repositório
2. Abra o notebook no Jupyter/Colab
3. Execute as células sequencialmente

---

## 📊 Exemplos de Visualizações

O projeto inclui análises visuais como:
- Comparativo de faturamento por dia da semana
- Evolução mensal comparativa
- Tendência de faturamento por evento ao longo do tempo
- Distribuição e variabilidade (boxplots)

---

## 💡 Aprendizados

- Implementação de pipeline ETL com Power Query e Pandas
- Detecção automática de eventos usando diferenças temporais
- Análise de séries temporais com dados de negócio real
- Tratamento de dados financeiros sensíveis
- Visualização de dados para tomada de decisão estratégica

---

## 🔐 Nota sobre Dados

Este repositório contém apenas dados de exemplo fictícios para fins de demonstração. Os dados reais e métricas financeiras são confidenciais e mantidos em repositório privado.

---

## 👨‍💻 Autor

**Ryu Higashi**
- Estudante de Ciência de Dados e IA - Fundação Santo André
- GitHub: [@RyuHigashi](https://github.com/RyuHigashi)

---

## 📝 Licença

Este projeto é de uso pessoal para fins de portfólio e aprendizado.
