# 🤖 Chatbot com PDF usando LangChain + Groq + Gradio

Este projeto implementa um chatbot inteligente que **lê o conteúdo de um arquivo PDF** e responde perguntas com base nesse conteúdo, utilizando **Inteligência Artificial**. Ele roda diretamente no **Google Colab** com uma interface amigável construída com **Gradio**.

---

## 📌 Funcionalidades

- 📄 Upload de arquivos PDF.
- 🧠 Leitura e indexação inteligente do conteúdo.
- 💬 Chat interativo para perguntas e respostas.
- 🚀 Modelo de linguagem avançado via **Groq (LLaMA 3)**.
- ✅ Interface visual amigável com botão de envio de perguntas.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

| Tecnologia              | Função                                                             |
|-------------------------|--------------------------------------------------------------------|
| **Python**              | Linguagem principal do projeto                                     |
| **Google Colab**        | Ambiente de execução online com suporte a notebooks Jupyter        |
| **LangChain**           | Cadeias inteligentes para IA baseada em documentos                 |
| **Gradio**              | Interface gráfica web para interações com o modelo                 |
| **Groq API**            | Execução de modelo LLaMA 3 (gratuito e rápido)                     |
| **FAISS**               | Base vetorial para busca semântica no conteúdo do PDF              |
| **PyPDF**               | Leitura e extração de texto de PDFs                                |
| **HuggingFace Embeddings** | Conversão de texto em vetores semânticos                     |

---

## 🚀 Como Usar

1. Clone este repositório ou copie o código para um notebook no Google Colab.
2. Execute as células do código.
3. Faça upload de um arquivo PDF.
4. Digite uma pergunta e clique em **"Perguntar"**.
5. O chatbot responderá com base no conteúdo do documento.

---

## 📸 Interface

A interface gráfica é simples e responsiva:

- **Upload de PDF**
- **Status de carregamento**
- **Campo de pergunta**
- **Botão de envio**
- **Campo de resposta gerada pela IA**

---

## 📋 Exemplo de Uso

> **Pergunta:** Qual é o objetivo principal do documento?

> **Resposta do Chatbot:** O objetivo principal descrito é apresentar...

> *(A resposta dependerá do conteúdo do PDF carregado.)*

---

## 🔑 Configuração da API Groq

Para utilizar o modelo LLaMA 3 via Groq, você precisa de uma chave de API válida:

```python
GROQ_API_KEY = "sua_chave_groq_aqui"

👨‍💻 Autor
Desenvolvido por [Jabes Christian].
Este projeto é livre para fins educacionais, demonstrações de IA e aplicações com documentos baseados em texto.
