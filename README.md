# 📊 Prática de Regressão Linear com NumPy

Este repositório contém exercícios práticos desenvolvidos durante o estudo da biblioteca **NumPy** e fundamentos de **análise de dados** e **regressão linear**.

O projeto utiliza um dataset de **laranjas e toranjas**, analisando a relação entre **diâmetro e peso** das frutas e aplicando técnicas matemáticas para encontrar a melhor reta de ajuste utilizando **mínimos quadrados** e **otimização por busca aleatória**.

---

# 📁 Estrutura do Projeto

.
├── pratica_numpy.ipynb
├── dataset_citrus.csv
└── README.md

O notebook contém a resolução progressiva dos exercícios.

---

# 📊 Dataset

Dataset utilizado:

**Oranges vs Grapefruit Dataset**

Contém medições de frutas com as seguintes variáveis:

| Coluna | Descrição |
|------|------|
| Diameter | Diâmetro da fruta |
| Weight | Peso da fruta |
| Fruit | Tipo da fruta (laranja ou toranja) |

Os dados são utilizados para analisar a relação entre **diâmetro e peso**.

---

# 🧠 Conceitos Aplicados

Durante os exercícios são abordados conceitos importantes de **ciência de dados**:

- Manipulação de arrays com **NumPy**
- Leitura de datasets CSV
- Visualização de dados com **Matplotlib**
- **Regressão Linear**
- **Coeficiente Angular (a)**
- **Coeficiente Linear (b)**
- **Método dos Mínimos Quadrados**
- **Cálculo de erro com Norma Euclidiana**
- **Busca aleatória de parâmetros (Random Search)**

---

# 📈 Regressão Linear

A regressão linear busca encontrar a melhor reta que descreve a relação entre duas variáveis.

Equação da reta:

y = ax + b

Onde:

- **a** → coeficiente angular (inclinação da reta)
- **b** → coeficiente linear (intercepto)

---

# 🔬 Exercícios Desenvolvidos

## Exercício 1
Leitura do dataset utilizando **NumPy**.

np.loadtxt()

---

## Exercício 2
Separação dos dados de **laranja** e **toranja** e construção do gráfico:

Peso vs Diâmetro

---

## Exercício 3
Cálculo da regressão linear utilizando a **fórmula de mínimos quadrados**.

a = (n∑XY − ∑X∑Y) / (n∑X² − (∑X)²)

b = média(Y) − a * média(X)

---

## Exercício 4
Estimativa do coeficiente angular utilizando **busca aleatória**:

1. Geração de 100 coeficientes angulares aleatórios
2. Cálculo do erro para cada reta
3. Seleção da reta com **menor erro**

Utilizando:

np.random.uniform()  
np.linalg.norm()

---

# 📊 Tecnologias Utilizadas

- Python
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

# 🚀 Objetivo do Projeto

Este projeto tem como objetivo consolidar conhecimentos fundamentais para áreas como:

- **Data Science**
- **Machine Learning**
- **Data Engineering**
- **Análise de Dados**

Através da implementação manual de conceitos matemáticos importantes.

---

# 📚 Aprendizados

Durante o desenvolvimento foram reforçados conceitos como:

- Manipulação eficiente de arrays
- Modelagem matemática de dados
- Interpretação de regressões
- Avaliação de erro em modelos
- Fundamentos de otimização de parâmetros

---

# 👨‍💻 Autor

Lucas Rodrigues Dias Nascimento  

🔗 LinkedIn  
https://www.linkedin.com/in/lucas-nascimento-2098691a4/

🔗 GitHub  
https://github.com/lucasrodriguesdias

---

# ⭐ Observação

Este projeto faz parte do processo de aprendizado em **análise e engenharia de dados**, explorando conceitos fundamentais utilizados posteriormente em bibliotecas como:

- Scikit-Learn
- Pandas
- TensorFlow
- PyTorch
