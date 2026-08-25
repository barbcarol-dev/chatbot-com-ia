# Chatbot de Inteligência Artificial com Streamlit e OpenAI

Aplicação interativa desenvolvida em Python que utiliza a biblioteca Streamlit para a interface de usuário e a API da OpenAI para o processamento de linguagem natural, mantendo o histórico da conversa durante a sessão.

Projeto desenvolvido como estudo prático durante a **Jornada Python**, promovida pela **Hashtag Programação**.

---

## Funcionalidades

- **Interface Responsiva:** Chat intuitivo e dinâmico construído com a biblioteca Streamlit.
- **Gerenciamento de Estado de Sessão:** Manutenção do histórico de mensagens através do `st.session_state`.
- **Respostas Inteligentes:** Integração direta com os modelos de *Chat Completions* da OpenAI.
- **Segurança de Credenciais:** Gerenciamento seguro de chaves de API utilizando `st.secrets` e arquivos ignorados no `.gitignore`.

---

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Interface Gráfica:** Streamlit
- **Inteligência Artificial:** OpenAI API

---

## Estrutura do Repositório

```text
├── .streamlit/
│   └── secrets.toml    # Chaves de API e variáveis de ambiente (não enviado ao Git)
├── .gitignore          # Especificação de arquivos ignorados no versionamento
├── main.py             # Código principal da aplicação
├── auxiliar.py         # Funções auxiliares e scripts secundários
└── README.md           # Documentação do projeto
```

---

## Como Executar o Projeto

### Pré-requisitos

- **Python 3.8+** instalado em sua máquina.
- **Chave de API da OpenAI** (API Key).

### Instruções

1. Clone o repositório:
   ```bash
   git clone https://github.com/barbcarol-dev/chatBot-com-IA.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd chatbot-streamlit
   ```

3. Instale as bibliotecas necessárias:
   ```bash
   pip install streamlit openai
   ```

4. Configure as credenciais da API:
   - Crie uma pasta chamada `.streamlit` na raiz do projeto.
   - Crie o arquivo `secrets.toml` dentro da pasta `.streamlit`.
   - Adicione sua chave de API no arquivo: `OPENAI_API_KEY = "sua-chave-aqui"`

5. Inicie a aplicação:
   ```bash
   streamlit run main.py
   ```

---

## Autora

**Bárbara Caroline**  
Estudante de Programação, Python e Análise de Dados.
