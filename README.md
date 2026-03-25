# Chatbot Barbearia Corte Fino

## Descrição do Projeto
Este projeto consiste no desenvolvimento de um chatbot utilizando um modelo de linguagem (LLM) para simular o atendimento de uma barbearia.

## O assistente virtual é capaz de:
* Informar valores dos serviços
* Realizar agendamentos
* Responder dúvidas dos clientes

## O chatbot foi configurado com:
* Personalidade de atendente
* Contexto específico do negócio
* Controle de fluxo com limite de 3 interações

Ao final da terceira interação, o sistema gera automaticamente um resumo da conversa e encerra o atendimento.


## Tecnologias Utilizadas
* Python
* Google Colab
* API Gemini (Google GenAI)


##Como Executar o Projeto
Siga os passos abaixo para reproduzir a execução:

### 1. Acesse o Google Colab
Abra o arquivo `.ipynb` disponível neste repositório no Google Colab.


### 2. Configure sua API Key
* No Colab, clique no ícone de 🔑 (Secrets)
* Adicione uma nova chave com o nome: GOOGLE_API_KEY
* Cole sua chave da API do Google

### 3. Execute os blocos de código
Execute as células na seguinte ordem:
1. Importação das bibliotecas
2. Definição do contexto
3. Execução do chatbot


### 4. Interaja com o chatbot
* Digite suas perguntas no terminal do Colab
* O chatbot responderá normalmente
* Após 3 interações, ele irá:

  * Gerar um resumo da conversa
  * Encerrar o atendimento automaticamente



Este projeto foi desenvolvido com fins acadêmicos para demonstrar o uso de engenharia de prompt e controle de fluxo em aplicações com modelos de linguagem.
