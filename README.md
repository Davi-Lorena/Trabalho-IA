# 🤖 Trabalho Prático de Inteligência Artificial (XMCO01) - Bank Marketing

Repositório dedicado à entrega do trabalho prático da disciplina de **Inteligência Artificial (XMCO01)** da **UNIFEI** (Universidade Federal de Itajubá), ministrada pela professora Isa Drummond. O objetivo do projeto é explorar modelos supervisionados e não supervisionados de aprendizado de máquina utilizando a biblioteca `scikit-learn` em Python.

---

## 📋 Sobre o Projeto

O trabalho baseia-se no clássico conjunto de dados **Bank Marketing** (disponível no repositório UCI) e foi executado em duas versões dos dados para comparar o impacto preditivo:
1. **Conjunto Original:** Contém todos os atributos originais do dataset, incluindo o atributo `duration` (duração da chamada telefônica).
2. **Conjunto Modificado:** O mesmo conjunto de dados, porém **sem o atributo `duration`**. Essa remoção simula um cenário real onde a duração da chamada é desconhecida antes do término do contato, avaliando a robustez dos modelos.

### ⚙️ Modelos Aplicados
* **Aprendizado Supervisionado (Classificação):**
  * **Random Forest** (`RandomForestClassifier`)
  * **Perceptron de Múltiplas Camadas - MLP** (`MLPClassifier`)
* **Aprendizado Não Supervisionado (Agrupamento):**
  * **K-Means** (`KMeans`)

---

## 👥 Equipe e Divisão de Tarefas

Conforme o planejamento e execução do grupo, as responsabilidades do projeto e da apresentação foram divididas da seguinte forma:

| Membro | Papel / Responsabilidade Principal | Atuação na Apresentação |
| :--- | :--- | :--- |
| **Davi** (Membro 1) | Coordenação geral do grupo, introdução teórica, carregamento, análise exploratória dos dados e fundamentação da modificação do dataset (`duration`). | Introdução, objetivos e apresentação do dataset. |
| **Amanda** (Membro 2) | Pré-processamento dos dados (One-Hot Encoding para variáveis categóricas, `StandardScaler` para numéricas), divisão treino/teste estratificada (`stratify=y`, `random_state`) e funções utilitárias. | Preparação, engenharia de atributos e divisão dos dados. |
| **Theo** (Membro 3) | Configuração, ajuste de hiperparâmetros (`n_estimators`, `max_depth`, critérios), testes, extração de relatórios de métricas e matrizes de confusão para o **Random Forest**. | Apresentação e discussão do modelo Random Forest. |
| **Samuel** (Membro 4) | Configuração, ajuste de hiperparâmetros (`hidden_layer_sizes`, `activation`, `solver`, épocas), testes, extração de relatórios de métricas e matrizes de confusão para o **MLP**. | Apresentação e discussão do modelo MLP. |
| **Karol** (Membro 5) | Implementação do **K-Means**, definição do número de clusters ($k$) via método do cotovelo, cálculo do **Índice de Silhueta** e análise interpretativa dos grupos formados. | Apresentação do modelo K-Means e agrupamento. |
| **Rafaella** (Membro 6) | Elaboração das tabelas comparativas entre o conjunto original e o modificado, análise crítica dos resultados, conclusões finais e revisão/formatação geral do Jupyter Notebook. | Síntese comparativa, conclusões e encerramento. |

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python
* **Aprendizado de Máquina:** `scikit-learn`
* **Manipulação de Dados:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Ambiente de Desenvolvimento:** Jupyter Notebook (`.ipynb`)

---

## 📂 Estrutura do Repositório

* `Trabalho_IA.ipynb`: Jupyter Notebook principal contendo o passo a passo completo da execução, desde a leitura dos dados, pré-processamento, treinamento dos modelos supervisionados e não supervisionados, até as métricas comparativas e análises críticas.

---
*Universidade Federal de Itajubá (UNIFEI) • Disciplina de Inteligência Artificial (XMCO01) • 2026/2*
