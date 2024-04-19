# Modelo de Previsão de Gastos dos Senadores

Este repositório contém um modelo de previsão de gastos dos senadores, utilizando técnicas como ARIMA, regressão linear e um baseline simples.

## Descrição

O modelo é capaz de prever os gastos futuros dos senadores com base em dados históricos, permitindo uma análise preditiva útil para planejamento e controle de gastos.

## Introdução

Este modelo foi desenvolvido para fornecer insights sobre padrões de gastos dos senadores ao longo do tempo e avaliar a eficácia de diferentes técnicas de previsão.

## Resultados Finais

Os resultados finais do modelo incluem métricas de avaliação para o baseline, regressão linear e ARIMA:

- Erro Médio Absoluto (MAE) do Baseline: 41865.75
- Erro Quadrático Médio (MSE) do Baseline: 3001189636.05
- Coeficiente de Determinação (R²) do Baseline: -0.0007

- Erro Médio Absoluto (MAE) da Regressão Linear: 34561.34
- Erro Quadrático Médio (MSE) da Regressão Linear: 2190931565.92
- Coeficiente de Determinação (R²) da Regressão Linear: 0.2695

- Erro Médio Absoluto (MAE) do ARIMA: 35389.91
- Erro Quadrático Médio (MSE) do ARIMA: 2395941691.01
- Coeficiente de Determinação (R²) do ARIMA: 0.2011

## Como Usar

1. Clone este repositório.
2. Instale as dependências necessárias (pandas, matplotlib, statsmodels, sklearn).
3. Execute o código fornecido no arquivo Jupyter Notebook para treinar e avaliar o modelo.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias no código, adicionar novas técnicas de previsão ou aprimorar a documentação.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

---

**Nota**: Este é um modelo simplificado para fins demonstrativos. Para aplicações reais, recomenda-se aprimorar o modelo, considerando mais features e otimizando os parâmetros.
