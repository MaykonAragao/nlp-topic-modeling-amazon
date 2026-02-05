# 📝 Inteligência de Texto: Modelagem de Tópicos (Amazon Reviews)

## 📋 Sobre o Projeto
Este projeto utiliza técnicas de **NLP (Natural Language Processing)** para analisar automaticamente 10.000 avaliações de clientes. O objetivo é descobrir os principais temas discutidos pelos consumidores sem a necessidade de leitura manual, utilizando Machine Learning não supervisionado.

**Dataset:** [Amazon Fine Food Reviews (Kaggle)](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

## 🛠 Tecnologias e Técnicas
*   **Python 3.x**
*   **NLTK:** Limpeza de texto e remoção de Stopwords.
*   **Scikit-Learn:** Vetorização TF-IDF e modelo LDA (Latent Dirichlet Allocation).
*   **Regex:** Limpeza de ruidos e tags HTML.

## ⚙️ Como Funciona
1.  **Pré-processamento:** Limpeza profunda de strings, normalização (letras minúsculas) e remoção de palavras irrelevantes.
2.  **Vetorização:** Conversão de texto em matrizes numéricas pesadas pela relevância das palavras.
3.  **Modelagem LDA:** Agrupamento probabilístico das palavras em 5 tópicos dominantes.
4.  **Classificação:** Atribuição automática de cada comentário a um dos temas descobertos.

## 📊 Resultados
O modelo identificou com sucesso categorias como:
*   **Bebidas Quentes:** Termos relacionados a café, chá e infusão.
*   **Logística/Experiência:** Termos focados em preço, entrega e pedidos na Amazon.

## 🚀 Como Executar
1. Clone o repositório.
2. Instale as dependências: `pip install pandas nltk scikit-learn`.
3. Certifique-se de ter o arquivo `Reviews.csv` na pasta.
4. Execute o notebook `01_analise_topicos.ipynb`.

---
*Desenvolvido durante Mentoria de Machine Learning Prático.*
