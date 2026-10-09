# 🤖 Eletiva III: Inteligência Artificial
* **Período Letivo:** 2026.2
* **Módulo:** 5 (TADS 39 - Faculdade Senac-PE)
* **Categoria:** Machine Learning, Algoritmos Supervisionados e Não-Supervisionados
* **Tags:** `#ia` `#machine-learning` `#arvore-de-decisao` `#k-means` `#overfitting` `#scikit-learn`

---

## 🎯 Objetivos de Aprendizagem
Compreender a aplicação prática, ajuste de hiperparâmetros e métricas de desempenho em modelos de Aprendizado Supervisionado (Classificação com Árvore de Decisão) e Não-Supervisionado (Agrupamento com K-Means).

---

## 📂 Artefatos e Entregas

### 📊 [Modificando os Algoritmos — Respostas Práticas](./relatorios/modificando-algoritmos-arvore-kmeans.pdf)
* **Formato:** Relatório Técnico Experimental (PDF)
* **Autores:** Giseli Felix e Victor Torres
* **Dataset:** Parâmetros clínicos de saúde (Glicose, Idade, IMC)

#### 📌 Metadados & Resultados dos Experimentos:
1. **Árvore de Decisão (Supervisionado):**
   * *Profundidade (`max_depth`):* Subida de acurácia de 85% (`max_depth=2`, 5 nós) para 95% (`max_depth=3`, 7 nós), estabilizando a complexidade estrutural e mitigando risco de overfitting.
   * *Poder Preditivo (Features):* A variável glicose isolada apresentou acurácia de 85%, demonstrando maior ganho de informação frente à idade (65%) e IMC (55%).
   * *Divisão Treino/Teste:* Testes com 20%, 30% e 40% mantiveram o modelo consistente em torno de 95% de acurácia.
2. **K-Means (Não-Supervisionado):**
   * *Fragmentação por Clusters (`n_clusters`):* Análise vetorial particionando dados por distâncias euclidianas em subgrupos clínicos intermediários de risco (testados K=2, K=3 e K=4).
3. **Quadro Comparativo:** Classificação (regras *if-else* para rótulos conhecidos) versus Agrupamento (proximidade geométrica sem supervisão prévia).

---

## 🔗 Relação com outras Unidades Curriculares
* **High Tech Aplicada ao Mercado:** Fundamento teórico para entender o funcionamento de pipelines mais complexos baseados em redes neurais e transformadores.
