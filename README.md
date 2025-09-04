# 🎗️ Classificação de Câncer de Mama (Breast Cancer) com PyTorch

Projeto desenvolvido durante o curso **Deep Learning de A a Z com PyTorch e Python**, ministrado por **Jones Granatyr (Udemy)**.  
O objetivo é treinar um modelo de **Machine Learning / Deep Learning** capaz de classificar tumores de mama como **benignos** ou **malignos**, utilizando dados numéricos de características extraídas das células.

---

## 🚀 Objetivos do Projeto
- Utilizar técnicas de **aprendizado supervisionado** para classificação binária.  
- Implementar uma **rede neural artificial (ANN)** em PyTorch.  
- Comparar métricas de desempenho como **acurácia, precisão, recall e F1-score**.  
- Demonstrar a aplicação prática de **Machine Learning na saúde**, auxiliando no diagnóstico precoce.

---

## 🧠 Bibliotecas Utilizadas e Propósitos

- **PyTorch (`torch`, `torch.nn`, `torch.optim`)** → criação da rede neural, definição das camadas, funções de ativação, treinamento e ajuste de pesos.  
- **Scikit-learn (`sklearn`)** → carregamento do dataset de câncer de mama, divisão em treino/teste, padronização dos dados, métricas de avaliação.  
- **NumPy (`numpy`)** → manipulação de arrays e cálculos matemáticos de apoio.  
- **Pandas (`pandas`)** → estruturação tabular dos dados para análises iniciais.  
- **Matplotlib / Seaborn** → geração de gráficos para análise exploratória e visualização de métricas.  

---

## ⚙️ Como Executar no VS Code

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/JsnEvt/ML_BreastCancer.git
cd ML_BreastCancer
```
1. Crie e ative um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
```
Ativar no Windows
```bash
venv\Scripts\activate
```
Ativar no Linux/Mac
```bash
source venv/bin/activate
```
Instale as dependências:
```bash
pip install -r requirements.txt
```
2. Abra VS Code e execute célula por célula
```bash
code .
```
📊 Resultados Esperados

O modelo apresenta boa acurácia na distinção entre tumores benignos e malignos.

👨‍🏫 Créditos

Projeto baseado no curso Deep Learning de A a Z com PyTorch e Python de Jones Granatyr - Udemy
