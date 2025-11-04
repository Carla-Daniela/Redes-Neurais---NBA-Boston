# 🏀 Celtics Stats Analyzer  -  Redes Neurais  
#### Desenvolvido por:
- [Carla Daniela](https://github.com/Carla-Daniela)
- [Letícia Lívia](https://github.com/mymph)  
- [Tayane Cibely](https://github.com/TayaneCibely)

### Acesso Regressão Linear
[https://boston-celtics--regressao-linear.streamlit.app/](https://boston-celtics--regressao-linear.streamlit.app/)

### Acesso Regressão Logística
[https://boston-celtics--regressao-logistica.streamlit.app/](https://boston-celtics--regressao-logistica.streamlit.app/)

## Especificações Gerais
- **Time**: Boston Celtics
- **Temporada**: 2024-25
- **Modelo**: Primeira parte: Regressão Linear Múltipla | Segunda parte: Regressão Logística
- **Variáveis**: Pontos, Rebotes, Assistências e outras estatísticas

## Sobre o Projeto

### Primeira parte: 
Utiliza Regressão Linear para explorar relações estatísticas do Boston Celtics na temporada 2024/25.

### Segunda parte:
Utiliza Regressão Logística, com mesma estrutura geral, mas aplicada a problemas de classificação binária (vitória/derrota) do Boston Celtics na temporada 2024/25.

## Funcionalidades
- **Análise Estatística**: Explore relações entre diferentes estatísticas do time
- **Modelo Preditivo**: Regressão Linear para prever desempenho baseado em múltiplas variáveis e Regressão Logística para previsão probabilística de vitórias (0% a 100%)
- **Visualizações Interativas**: Gráficos de dispersão, correlação, tendências temporais, curva ROC e distribuição de probabilidades
- **Validação do Modelo**: Testes de sanidade para verificar precisão, métricas de performance (R², RMSE, Acurácia, AUC-ROC), análise de coeficientes e impacto das variáveis e
  validação cruzada simples

## Tecnologias
- **Framework**: Streamlit
- **Machine Learning**: Scikit-Learn
- **Análise de Dados**: Pandas, NumPy
- **Visualização**: Matplotlib, Seaborn
- **Dados**: NBA API (temporada 2024/25)

## 🚀 Comandos para execução
```No diretório do projeto: pip install -r requirements.txt```

```Regressão Linear: streamlit run app_linear.py ```

```Regressão Logística: streamlit run app_logistica.py```
