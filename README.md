# Machine Learning & Ciência de Dados para Negócios

Um repositório com projetos práticos de ciência de dados e machine learning aplicados ao contexto empresarial, abordando diferentes departamentos e necessidades de negócios.

## Projetos Disponíveis

### 1. Marketing (M-department)
Análise de segmentação de clientes utilizando técnicas de clustering para identificar padrões de comportamento e otimizar estratégias de marketing.

**Tecnologias utilizadas:**
- Pandas, NumPy
- Scikit-learn (KMeans, PCA)
- Visualização de dados (Seaborn, Matplotlib)

**Dataset:** Marketing.csv - Dados transacionais de clientes

### 2. Recursos Humanos (RH-department)
Análise preditiva para identificar fatores que influenciam a rotatividade de funcionários e desenvolvimento de modelos para prever possíveis demissões.

**Tecnologias utilizadas:**
- Pandas, NumPy
- Modelos de classificação 
- Visualização de dados (Seaborn, Matplotlib)

**Dataset:** Human_Resources.csv - Dados de colaboradores

### 3. Análise de Produto (RP-department)
Processamento de linguagem natural (NLP) para análise de sentimento em reviews de produtos, permitindo entender a percepção dos clientes.

**Tecnologias utilizadas:**
- Pandas, NumPy
- Processamento de texto
- Classificação de sentimentos

**Dataset:** amazon_alexa.tsv - Reviews de produtos Amazon Alexa

### 4. Análise de Departamentos (S-department)
Projeto em desenvolvimento para análise estatística dos diferentes departamentos da empresa.

## Estrutura do Repositório

```
├── data/                      # Datasets utilizados
│   ├── Marketing.csv          # Dados para análise de marketing
│   ├── Human_Resources.csv    # Dados de RH
│   ├── amazon_alexa.tsv       # Reviews de produtos
│   ├── text_classifier.pkl    # Modelo serializado para classificação
│   └── outros arquivos        # Arquivos auxiliares
├── M-department.ipynb         # Notebook de análise de marketing
├── RH-department.ipynb        # Notebook de análise de RH
├── RP-department.ipynb        # Notebook de análise de produto
└── S-department.ipynb         # Notebook de análise departamental (em desenvolvimento)
```

## Como Utilizar

1. Clone este repositório
2. Instale as dependências necessárias: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
3. Execute os notebooks Jupyter para explorar as análises e modelos

## Licença

Este projeto é disponibilizado para fins educacionais e de demonstração.
