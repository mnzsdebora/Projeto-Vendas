# Projeto Câncer
Projeto de Machine Learning com o objetivo de classificar um câncer como benigno ou magligno baseado no quadro clínico do câncer.
---

## **Descrição do Projeto**

A predição é feita a partir de variáveis clínicas como:
- Raio médio do câncer
- Área média do câncer
- Textura média do câncer
- Entre outros.

Foi realizada uma análise exploratória e o pré-processamento dos dados para garantir a qualidade das informações usadas nos modelos.

### **Valores de Saída (Target)**
- `0`: Maligno 
- `1`: Benigno

---

## **Técnicas e Algoritmos Utilizados**

### **Modelos de Machine Learning**
- K-Nearest Neighbors (KNN)
- Árvore de Decisão
- Modelo Dummy (baseline)
- Support Vector Classification (SVC)

### **Pré-processamento**
- Limpeza de dados
- Tratamento de valores ausentes
- Escalonamento de variáveis (quando necessário)

---

## **Principais Ferramentas e Tecnologias**

- **Linguagem**: Python  
- **Bibliotecas**:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Statsmodel  
  - SciPy  

---

## **Estrutura do Projeto**


├── data/    Conjunto de dados utilizado no projeto
