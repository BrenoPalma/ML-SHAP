# ML-SHAP
### Resumo do Projeto

Este repositório contém o código desenvolvido para o TCC *"Um Estudo Baseado em Machine Learning e SHAP para Detecção de Ataques DDoS utilizando o Dataset CICDDoS2019"*. O objetivo é implementar e avaliar modelos de aprendizado de máquina para detectar ataques DDoS, utilizando o dataset CICDDoS2019, com foco em desempenho preditivo e interpretabilidade através da técnica SHAP.

### Resultados Principais

- **Modelos**: Random Forest e XGBoost destacaram-se com F1-score de 0,9995 e AUC próximo de 1,0.
- **Features Importantes**: "ACK Flag Count", "Fwd Packet Length Min" e "Flow Duration" foram as mais influentes.
- **Explicabilidade**: SHAP revelou padrões claros, como a relevância de "ACK Flag Count" em ataques SYN Flood.
