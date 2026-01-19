# 🤖 ChatBot com IA usando Streamlit e OpenAI

Este projeto consiste em um **chatbot com Inteligência Artificial** desenvolvido em **Python**, utilizando **Streamlit** para o frontend e a **API da OpenAI** para geração das respostas.

O objetivo principal é permitir que o usuário interaja com a IA em tempo real, mantendo o histórico da conversa durante a sessão.

> 📚 **Projeto de estudos desenvolvido pela hashtag programação, durante a Jornada Python.**

---

## 📌 Funcionalidades

* **Interface Interativa:** Chat simples e intuitivo integrado com Streamlit.
* **Memória de Sessão:** Uso de `st.session_state` para manter o histórico da conversa.
* **Respostas Inteligentes:** Integração direta com o modelo de Chat Completions da OpenAI.
* **Segurança Profissional:** Gerenciamento de chaves de API através de `st.secrets`.

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* **Streamlit**
* **OpenAI API**

---

## 📂 Estrutura do Projeto

```text
📁 chatbot-streamlit
│
├── .streamlit/
│   └── secrets.toml      # Onde fica sua chave (NÃO ENVIADO AO GITHUB)
├── .gitignore            # Arquivo que impede o envio de dados sensíveis
├── main.py               # Arquivo principal da aplicação
├── auxiliar.py           # Funções auxiliares (se aplicável)
└── README.md             # Documentação do projeto
