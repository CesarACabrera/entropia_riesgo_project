# entropia_riesgo_project
# Segundo Cérebro: Entropia em Métricas Coerentes de Risco

Repositório criado para documentar a construção de um segundo cérebro no Gemini Notebook (NotebookLM), focado na intersecção entre Teoria da Informação e Finanças Quantitativas.

---

## 🎯 Tema e Objetivo
> **"Servir como base de consulta para compreender a formulação matemática da entropia e sua aplicação na modelagem de métricas coerentes de risco financeiro."**

---

## 📚 Curadoria de Fontes e Confiabilidade
A curadoria seguiu três critérios rigorosos: **rigor matemático** (evitar metáforas vagas de mercado), **complementaridade** (textos seminais com demonstrações e vídeos com intuição analítica) e **foco prático em finanças**.

### 1. Artigo Acadêmico Seminal
* **Título:** *Coherent Measures of Risk* (Artzner, Delbaen, Eber & Heath, 1999 – *Mathematical Finance*).
* **Confiabilidade:** Artigo pioneiro revisado por pares (*peer-reviewed*), com milhares de citações. Estabeleceu os 4 axiomas de risco coerente na literatura acadêmica mundial.
* **Papel no caderno:** Fornece o arcabouço formal e as demonstrações de por que métricas tradicionais (como o VaR) falham na agregação de carteiras.

### 2. Conteúdos Audiovisuais de Apoio
* **Canal Lemnismath:** Demonstrações passo a passo do formalismo matemático da entropia e probabilidade, garantindo precisão analítica.
* **Canal Veritasium (2 vídeos):** Divulgação científica rigorosa com consultoria de especialistas, oferecendo a intuição física da entropia e sua transição para a Teoria da Informação de Shannon.

---

## 🧭 Diretriz de Comportamento do Notebook
Para calibrar a IA e garantir respostas fiéis às fontes, foi estabelecida a seguinte instrução de sistema:

1. Responda estritamente com base nos materiais carregados (Artzner et al., Lemnismath e Veritasium).
2. Sempre cite explicitamente qual fonte embasa cada raciocínio.
3. Mantenha o rigor formal: avalie o cumprimento dos axiomas de coerência (subaditividade, monotonicidade, homogeneidade positiva e invariância translacional).
4. Faça a ponte entre a intuição probabilística da entropia e a modelagem matemática de risco no mercado financeiro.
5. Se uma questão não estiver coberta pelas fontes, aponte a limitação com clareza.

---

## 💬 Testes e Evidências com Citações

### Pergunta 1: Axiomas de Risco e Subaditividade do VaR
* **Pergunta:** *"Com base no artigo de Artzner et al. (1999), quais são os 4 axiomas que definem uma medida de risco coerente e por que o Value at Risk (VaR) tradicional viola o axioma da subaditividade?"*
* **Fontes citadas:** *Coherent Measures of Risk* (Artzner et al., 1999).
* **Síntese da resposta:** O notebook explicou a violação da subaditividade pelo VaR em caudas pesadas e demonstrou a exigência de diversificação garantida pelos 4 axiomas.
* ![Evidência da citação 1](evidencias/evidencia-1.pdf)

### Pergunta 2: Entropia como Medida de Informação e Incerteza
* **Pergunta:** *"A partir das explicações de entropia dos vídeos (Veritasium e Lemnismath), como a entropia mede a incerteza e a surpresa da informação em uma distribuição de probabilidades?"*
* **Fontes citadas:** Aulas dos canais Veritasium e Lemnismath.
* **Síntese da resposta:** O notebook articulou a fórmula da entropia de Shannon e explicou intuitivamente a relação entre probabilidade de ocorrência e conteúdo informacional.
* ![Evidência da citação 2](evidencias/evidencia-2.pdf)

---

## 🔗 Link do Notebook Compartilhado
* [Acesse o Gemini Notebook deste projeto](https://notebook.google.com/notebook/4aa3896a-aa0f-4d6b-b4fc-6c711c78ea36)