# Projeto de PLN: Sistema de Perguntas e Respostas sobre o Mercado de Carbono

Este repositório contém o projeto final desenvolvido para a disciplina de Processamento de Linguagem Natural (UFABC).

O projeto consiste na implementação de um sistema de Perguntas e Respostas (Q&A) utilizando Processamento de Linguagem Natural (PLN). O objetivo é fornecer respostas precisas sobre o mercado regulado de carbono, baseando-se em documentos oficiais da CVM.

## 🧠 Técnicas Utilizadas

Para o desenvolvimento deste sistema, foram utilizadas as seguintes técnicas de PLN:

* **Similaridade de textos:** Para recuperação de trechos relevantes (Retrieval).
* **Sistemas de perguntas e respostas:** Geração de respostas baseadas em contexto (RAG - Retrieval-Augmented Generation).
* **Sumarização de textos:** Síntese de informações para respostas objetivas.

## 🛠️ Tecnologias

O projeto foi construído utilizando:

* **LangChain:** Framework para orquestração do fluxo de PLN.
* **Google Gemini (gemini-2.5-flash):** LLM utilizado para geração de texto.
* **ChromaDB:** Banco de dados vetorial para armazenamento dos embeddings.

## 📚 Fonte de Dados

A base de conhecimento utilizada para alimentar o modelo foi o FAQ oficial da CVM sobre o mercado de carbono:

* FAQ Mercado de Carbono - CVM (Set/2025)

## 🚀 Como Executar

Para rodar o projeto no Google Colab, é necessário configurar a chave da API (Secret) para o modelo Gemini:

1.  **Obtenha a API Key:** Gere sua chave no Google AI Studio.
2.  **Configure os Segredos (Secrets) no Colab:**
    * Abra o notebook no Google Colab.
    * No menu lateral esquerdo, clique no ícone de Chave (**Segredos/Secrets**).
    * Clique em "Adicionar novo segredo".
    * No campo **Nome**, digite: `GEMINI_KEY`
    * No campo **Valor**, cole sua API Key.
    * Ative a opção **"Notebook access"** (Acesso ao notebook) para este segredo.

## 👥 Contribuidores

<a href="https://github.com/BrunoGallani/projeto_PLN_UFABC/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=BrunoGallani/projeto_PLN_UFABC" />
</a>

### Equipe do Projeto (FNET)

* **Bruno Augusto Soares Gallani** - RA: 11202230282
* **Gabriel Cipriano Gomes dos Santos** - RA: 11202111302
* **Rafael de Souza Coelho** - RA: 11202232212

---
*Projeto acadêmico - FNET*