# ✅ Checkpoint: Árvores de Decisão – EBAC

Este projeto tem como objetivo aplicar os conceitos de **classificação supervisionada** utilizando o algoritmo de **Árvore de Decisão** com a biblioteca `scikit-learn`. A atividade faz parte do curso de Ciência de Dados da **EBAC**.

---

## 🎯 Objetivos

- Carregar e tratar uma base de dados fictícia.
- Construir um modelo de árvore de decisão.
- Avaliar o desempenho do modelo com métricas como **acurácia** e **matriz de confusão**.
- Visualizar a estrutura da árvore para interpretação dos critérios de decisão.

---

## 🧰 Tecnologias Utilizadas

- Python 3.x
- Jupyter Notebook
- Bibliotecas"
- ``pandas``
- ``numpy``
- ``matplotlib``
- ``seaborn``
- ``scikit-learn``

---

## 📁 Estrutura do Projeto

```text
Checkpoint-Arvore-Decisao/
└── README.md                           # Documentação do projeto
```
---

### 🚀 Como Executar

1.Clone o repositório:
```bash
   git clone https://github.com/fabiooliveira95/Checkpoint-Arvore-Decisao.git
```
2.Acesse a pasta do projeto:
```bash 
  cd Checkpoint-Arvore-Decisao.git
```

3.Instale as dependências: 
```bash
   pip install pandas
```
```bash
   pip install matplotlib
```
```bash
   pip install seaborn
```
```bash
   pip install scikit-learn
```

📝 Etapas Realizadas

1.Importação e tratamento da base de dados
     
* Leitura de arquivo CSV
* Conversão de colunas categóricas para dummies
* Verificação de valores nulos

2.Separação em treino e teste

* 70% dos dados para treino e 30% para teste
* Variável resposta: aprovação ou reprovação

3.Construção do modelo

* Utilização de ``DecisionTreeClassifier``
* Ajuste do modelo com ``fit``

4.Avaliação

* Predições com o modelo treinado
* Geração da matriz de confusão com rótulos "aprovado" e "reprovado"

5.Cálculo da acurácia

* Visualização da Árvore
* Exibição gráfica dos nós de decisão utilizando ``plot_tree``

📈 Resultados esperados

* Obter uma árvore de decisão bem ajustada à base.
* Visualizar claramente as divisões e critérios de decisão.
* Entender o impacto de cada variável na classificação.

## 📬 Contato

* Fábio Oliveira
* 🔗 [LinkedIn](https://www.linkedin.com/in/fabio-oliveira-araujo-cientista/)
* 📧 fabiooliveira0067@gmail.com
