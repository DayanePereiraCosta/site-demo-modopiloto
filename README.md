# ☀️ Aurora Financeira
### Atendimento financeiro inteligente com Inteligência Artificial e AWS

O **Aurora Financeira** é um projeto demonstrativo de atendimento financeiro digital que utiliza Inteligência Artificial e serviços AWS para oferecer uma experiência de atendimento mais simples, rápida e eficiente.

Por meio de uma conversa natural, o cliente pode escrever o que precisa e o assistente virtual interpreta sua solicitação, identifica sua intenção e direciona o atendimento adequado.

> ⚠️ **Projeto fictício:** todos os clientes e dados utilizados são demonstrativos. Não informe informações pessoais reais.

## 🚀 Funcionalidades

- 🤖 Atendimento conversacional com Inteligência Artificial.
- 📄 Solicitação de segunda via de boleto.
- 📊 Consulta de extrato e informações do contrato.
- 👩‍💻 Possibilidade de atendimento humano.
- ⭐ Avaliação da experiência de atendimento.

## 🧠 Inteligência Artificial

O projeto utiliza o **Amazon Lex** para interpretar mensagens em linguagem natural e identificar as intenções (*Intents*) dos usuários.

Exemplos de solicitações:
- "Quero a segunda via do meu boleto."
- "Quanto falta pagar do meu financiamento?"
- "Quero falar com um atendente."

A partir da intenção identificada, o fluxo de atendimento direciona a solicitação para a operação correspondente.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| HTML5, CSS3 e JavaScript | Interface web |
| Amazon Connect | Atendimento digital por chat |
| Amazon Lex | Interpretação de linguagem natural |
| AWS Lambda | Lógica de negócio |
| Supabase | Banco de dados |
| Amazon SES | Envio de e-mails |

## 🏗️ Arquitetura da solução

```text
       CLIENTE
          |
          v
    SITE AURORA
          |
          v
   AMAZON CONNECT
          |
          v
      AMAZON LEX
          |
          v
      AWS LAMBDA
        /     \
       v       v
  SUPABASE  AMAZON SES
```

*Diagrama conceitual da solução.*

## 🧪 Como testar

1. Acesse o [Aurora Financeira]( https://dayanepereiracosta.github.io/site-demo-modopiloto/).
2. Clique no ícone de chat no canto inferior direito.
3. Inicie uma conversa.
4. Escreva sua solicitação em linguagem natural.
5. Explore as opções de atendimento.

Utilize somente dados fictícios durante os testes.

## 🎯 Objetivo do projeto

Explorar a integração entre desenvolvimento web, Inteligência Artificial e computação em nuvem, aplicando conceitos de:

- Processamento de linguagem natural (NLP).
- Automação de processos.
- Arquitetura Serverless.
- Integração entre serviços AWS.
- Experiência do usuário (UX).

---
## 👩‍💻 Autoria

Desenvolvido por **Dayane Pereira Costa**, estudante de Análise e Desenvolvimento de Sistemas, em projeto de demonstração da **Modo Piloto Consultoria de Tecnologia**.
