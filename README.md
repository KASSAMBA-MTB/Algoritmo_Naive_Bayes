# 🧠📊 Aprendizado Probabilístico e Classificador Naive-Bayes

## 📌 Descrição

Este projeto apresenta conceitos fundamentais de **Aprendizado de Máquina**, com foco em **métodos probabilísticos**, especialmente o **Classificador Naive-Bayes**.

O conteúdo aborda desde os paradigmas de aprendizado até a aplicação prática do **Teorema de Bayes**, incluindo exemplos e análise do algoritmo.

---

## 🧠 Conteúdos Abordados

* Paradigmas de Aprendizado de Máquina
* Métodos Bayesianos
* Teorema de Bayes
* Aprendizado Bayesiano
* Classificador Naive-Bayes
* Exemplo prático: Problema da Balança
* Análise do algoritmo

---

## 🔹 Paradigmas de Aprendizado de Máquina

Os principais paradigmas são:

### ✔️ Simbólico

* Baseado em regras e lógica
* Exemplos: árvores de decisão, sistemas especialistas

### ✔️ Estatístico

* Utiliza modelos probabilísticos
* Baseado em inferência e distribuição de dados
* Destaque: **Modelos Bayesianos**

### ✔️ Baseado em Exemplos

* Classificação por similaridade
* Exemplo: K-Nearest Neighbors (KNN)

### ✔️ Conexionista

* Inspirado no cérebro humano
* Utiliza redes neurais artificiais

### ✔️ Evolutivo

* Inspirado na teoria da evolução
* Utiliza algoritmos genéticos

---

## 📊 Métodos Bayesianos

Os métodos Bayesianos:

* Combinam **conhecimento prévio (probabilidade a priori)** com dados observados
* Permitem calcular a probabilidade de um evento com base em evidências
* São amplamente utilizados em classificação

---

## 🧮 Teorema de Bayes

O Teorema de Bayes permite calcular probabilidades condicionais:

* Considera a probabilidade de um evento com base em outro
* Utiliza:

  * Probabilidade a priori
  * Probabilidade condicional
  * Probabilidade total

### 📌 Ideia central:

> A probabilidade de um evento depende tanto dos dados observados quanto do conhecimento prévio.

---

## 🧠 Aprendizado Bayesiano

No aprendizado Bayesiano:

* O objetivo é encontrar a hipótese mais provável
* Utiliza o método MAP (*Maximum a Posteriori*)
* Calcula:

👉 P(classe | dados)

Aplicação comum:

* Diagnóstico médico
* Classificação de padrões

---

## 🤖 Classificador Naive-Bayes

O Naive-Bayes é um classificador probabilístico baseado no Teorema de Bayes.

### 📌 Principal característica:

👉 Assume que os atributos são **independentes entre si**

### 📊 Fórmula:

P(x | yi) = P(x1 | yi) × P(x2 | yi) × ... × P(xd | yi)

---

## ⚖️ Exemplo: Problema da Balança

Neste problema, a classificação depende de:

* Peso esquerdo
* Distância esquerda
* Peso direito
* Distância direita

### 🎯 Classes possíveis:

* Esquerda
* Direita
* Balanceada

A decisão é baseada na comparação:

👉 Peso × Distância

---

## 📈 Resultado do Exemplo

Para um novo exemplo:

* Peso esquerdo = 3
* Distância esquerda = 2
* Peso direito = 1
* Distância direita = 3

Resultado:

* P(esquerda) = 0,71
* P(direita) = 0,20
* P(balanceada) = 0,09

👉 Classificação final: **Esquerda**

---

## ⚖️ Análise do Algoritmo Naive-Bayes

### ✅ Vantagens

* Fácil implementação
* Baixo custo computacional
* Funciona bem em diversos problemas
* Robusto a ruídos
* Interpretável

---

### ❌ Desvantagens

* Assume independência dos atributos (nem sempre realista)
* Dificuldade com atributos contínuos (necessita discretização)
* Sensível a atributos irrelevantes

---

## 🎯 Objetivo Acadêmico

Este material tem como objetivo:

* Compreender fundamentos de aprendizado probabilístico
* Aplicar o Teorema de Bayes em problemas reais
* Entender o funcionamento do Naive-Bayes
* Desenvolver base teórica para algoritmos de classificação

---

## 📚 Referência

FACELI, Katti et al.
**Inteligência Artificial: Uma Abordagem de Aprendizado de Máquina**

---

## 👨‍💻 Autor

**Walter Junio Pontes Teixeira**
Curso: Ciência de Dados

---
