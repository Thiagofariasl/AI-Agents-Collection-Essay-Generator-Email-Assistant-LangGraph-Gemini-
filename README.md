# 🤖 AI Agents Collection

### Essay Generator & Email Assistant (LangGraph + Gemini)

Este repositório reúne dois projetos de agentes de Inteligência Artificial desenvolvidos com foco em automação de tarefas e geração de conteúdo, utilizando arquitetura de múltiplos agentes com LangGraph.

---

## 📌 Projetos

### 🧾 AI Essay Generator

Gerador de redações com IA que:

* Planeja a estrutura do texto
* Realiza pesquisas automaticamente
* Gera rascunhos de alta qualidade
* Revisa e melhora o conteúdo iterativamente

---

### 📧 AI Email Assistant

Assistente executivo com IA capaz de:

* Escrever e-mails automaticamente
* Agendar reuniões
* Verificar disponibilidade em calendário
* Utilizar memória contextual para interações mais inteligentes

---

## ⚙️ Tecnologias Utilizadas

* Python
* LangGraph
* Google Gemini
* Tavily (Web Search)
* Gradio (Interface Web)
* SQLite (Memória / Checkpoints)

---

## 🧠 Conceitos Aplicados

* Multi-agent systems
* Orquestração de agentes
* Uso de ferramentas (tools)
* Memória e contexto em IA
* Loop de melhoria contínua (self-reflection)

---

## 🔄 Fluxo do Essay Generator

Planejamento → Pesquisa → Geração → Revisão → Refinamento

---

## 🚀 Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/Thiagofariasl/AI-Agents-Collection-Essay-Generator-Email-Assistant-LangGraph-Gemini-.git
cd AI-Agents-Collection-Essay-Generator-Email-Assistant-LangGraph-Gemini-
```

---

### 2. Criar ambiente virtual

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

---

### 3. Instalar dependências

```bash
pip install -r requirements.txt
```

---

### 4. Configurar variáveis de ambiente

Crie um arquivo `.env`:

```env
GEMINI_API_KEY=your_key_here
TAVILY_API_KEY=your_key_here
```

---

### 5. Rodar a aplicação

```bash
python app.py
```

---

## 📂 Estrutura do Projeto

```
📦 AI-Agents-Collection
 ┣ 📂 essay-generator
 ┃ ┣ app.py
 ┃ ┣ new_backend.py
 ┃ ┗ ...
 ┣ 📂 email-assistant
 ┃ ┣ prompts.py
 ┃ ┗ ...
 ┣ README.md
 ┗ requirements.txt
```

---

## 🎯 Objetivo

Este projeto foi desenvolvido com o objetivo de praticar e demonstrar aplicações reais de agentes de IA, incluindo automação de tarefas e geração de conteúdo com uso de múltiplos agentes e memória.

---

## 📬 Contato

Desenvolvido por Thiago Farias
🔗 https://github.com/Thiagofariasl

---
