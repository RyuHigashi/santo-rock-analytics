# 🎸 Santo Rock Bar - Analytics & ML

Análise de dados e previsão de público para casa de shows ao vivo usando Python, Pandas e Machine Learning.

---

## 📊 Sobre o Projeto

O **Santo Rock Bar** é uma casa de shows que realiza eventos ao vivo 5 vezes por semana. Este projeto utiliza dados reais de operação para:

- 📈 Analisar padrões de faturamento e público
- 🎯 Identificar fatores que impactam o sucesso dos eventos
- 🤖 Prever público esperado usando Machine Learning
- 💡 Gerar insights acionáveis para otimizar operações

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Análise e manipulação de dados
- **Matplotlib / Seaborn** - Visualizações
- **Scikit-learn** - Machine Learning (Random Forest)
- **Jupyter Notebook** - Documentação e análise exploratória
- **Excel / Power Query** - ETL inicial

---

## 📁 Estrutura do Projeto

```
santo-rock-analytics/
├── README.md                           # Este arquivo
├── notebooks/
│   ├── 01_analise_exploratoria.ipynb  # EDA e visualizações
│   └── 02_modelo_ml.ipynb             # Modelo de previsão
├── dados/
│   └── exemplo_amostra.csv            # Dados de exemplo (fictícios)
├── scripts/
│   └── etl_pipeline.py                # Pipeline de limpeza
└── visualizacoes/
    └── graficos/                       # Gráficos gerados
```

---

## 🚀 Funcionalidades

### **1. Análise Exploratória de Dados (EDA)**
- Distribuição de faturamento por dia da semana
- Análise de sazonalidade (mês, feriados)
- Correlação entre público e faturamento
- Identificação de outliers

### **2. Feature Engineering**
- Criação de features temporais (mês, dia_semana, é_feriado)
- Encoding de variáveis categóricas (bandas)
- Normalização de dados numéricos

### **3. Modelo de Machine Learning**
- Algoritmo: **Random Forest Regressor**
- Target: Previsão de público esperado
- Features: dia_semana, mês, banda, histórico
- Métricas: MAE (Mean Absolute Error), R²

---

## 📈 Principais Insights

🔍 *Em desenvolvimento* - Insights serão adicionados após análise completa dos dados.

Exemplos do que será analisado:
- Qual dia da semana gera maior faturamento?
- Existe sazonalidade no público?
- Quais bandas atraem mais público?
- Como otimizar custos operacionais?

---

## ⚠️ Nota sobre Dados

Os dados financeiros reais do **Santo Rock Bar** são confidenciais e não estão disponíveis neste repositório público.

O arquivo `dados/exemplo_amostra.csv` contém **dados fictícios** para demonstração da estrutura e metodologia do projeto.

Em entrevistas, posso demonstrar o projeto rodando em **dados reais** mediante acordo de confidencialidade.

---

## 🎯 Objetivos do Projeto

Este projeto foi desenvolvido como parte do meu portfólio de **Data Science** para demonstrar:

✅ Capacidade de trabalhar com dados reais de negócio  
✅ Pipeline completo de ETL → EDA → ML  
✅ Habilidades em Python, Pandas, Scikit-learn  
✅ Pensamento analítico aplicado a problemas reais  
✅ Comunicação de insights através de visualizações  

---

## 📊 Próximos Passos

- [ ] Finalizar limpeza e preparação dos dados
- [ ] Completar análise exploratória
- [ ] Treinar modelo de previsão de público
- [ ] Criar dashboard interativo (Power BI ou Streamlit)
- [ ] Implementar sistema de recomendação de bandas

---

## 👨‍💻 Autor

**Ryu Higashi**

Estudante de Ciência de Dados e IA | Fundação Santo André

📧 [Email](Ryuhigashi@hotmail.com)
💼 [LinkedIn](https://linkedin.com/in/seu-perfil)  
🐙 [GitHub](https://github.com/RyuHigashi)

---

## 📄 Licença

Este projeto está sob licença MIT - veja detalhes em [LICENSE](LICENSE).

**Nota:** Os dados reais utilizados neste projeto são propriedade do Santo Rock Bar e não podem ser redistribuídos.

---

⭐ **Se este projeto foi útil, deixe uma estrela!**
