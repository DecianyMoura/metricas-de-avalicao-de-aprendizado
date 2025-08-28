# Métricas de avaliação de aprendizado de modelos

Este repositório contém um exemplo didático de como treinar um modelo de rede neural simples (MLP) no conjunto de dados MNIST, utilizando 10 amostras por classe, calculando uma **matriz de confusão** e em seguida sendo aplicado métricas amplamente utilizadas para validação de modelos inteligentes: **acurácia, precisão, recall, F1-Score e especificidade**

---

## Objetivo

- Demonstrar como funciona a **matriz de confusão**.
- Calcular **métricas** manualmente (sem bibliotecas próprias)

---

## Pré-requisitos

- Python 3.x  
- Bibliotecas:
  - `tensorflow` (>=2.0.0-beta1)
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`

Instalação rápida (em colab ou local):

```bash
pip install tensorflow numpy pandas matplotlib seaborn
