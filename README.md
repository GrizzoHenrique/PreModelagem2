# Pré-processamento de dados: Churn telecom Parte 2

## Objetivo:
**Nesta segunda parte iremos analisar visualmente o comportamento dos clientes de uma empresa de Telecom para responder: Quais variáveis estão mais correlacionadas com a desistência do cliente?**

### O Dataset:
**Os dados foram importados a partir do tratamento realizado anteriormente, incluindo:**
* **Variáveis Categóricas**: Tipo de contrato, método de pagamento e serviços(Internet,TV, ETC..)
* **Variáveis Numéricas**: Pagamento mensal e tempo de permanência
* **Target**: Churn(sim/não)

### Tecnologias Utilizadas: 

| Biblioteca | Versão | Propósito |
|-----------|--------|----------|
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) | Latest | Manipulação e análise de dados |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) | Latest | Computação numérica |
| ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) | Latest | Machine Learning e métricas |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white) | Latest | Visualizações estáticas |
| ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=seaborn&logoColor=white) | Latest | Gráficos estatísticos |
| ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white) | Latest | Visualizações interativas |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | 3.7+ | Linguagem principal |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37726?style=for-the-badge&logo=jupyter&logoColor=white) | Latest | Ambiente interativo |

### Etapas do projeto:
1. Realizar uma análise univariada:
   * Utilizar a função describe()
   * Identificar possiveis outliers
   * Plotar Gráficos importantes para a análise
   * Verificar se as variáveis booleanas estão balanceadas
2. Identificar a tratar colunas que contem outliers
3. Realizar análise bivariada

##  Como Executar

### Pré-requisitos
- Python 3.7+
- pip ou conda
- Power BI Desktop (opcional, para dashboard)
- SQLite (incluído no Python)

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GrizzoHenrique/PreModelagem2.git
cd PreModelagem2

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt
