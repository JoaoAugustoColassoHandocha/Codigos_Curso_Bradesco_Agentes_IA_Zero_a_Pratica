# Desafio Criativo: Projetando o Prompt de um Agente de Atendimento ao Cliente🎯

Bem-vindo ao **Desafio Criativo**.

Nesta atividade, você seguirá algumas etapas simples que, ao final, irão ajudar a escrever o Prompt que define o comportamento de um Agente de atendimento ao cliente, do que ele resolve sozinho até o que ele nunca deve fazer.

💡 Sobre o Exercício

Um bom prompt nasce de intenção clara, contexto e instruções específicas. Durante o desafio, você irá organizar suas ideias e transformá-las em comandos claros.

🧩 Construção Passo a Passo

Cada etapa adicionará uma nova peça ao seu prompt final. Ao concluir todas, você terá um prompt capaz de orientar uma IA a produzir exatamente o que você imaginou.

🚀 Como Resolver

Siga cada passo com atenção, registre suas respostas e, ao final, una todos os elementos para formar seu prompt final.

Aproveite o processo criativo!

## Passo 1🧱: Defina Quem é o Agente e Quem Ele Atende

Nesta etapa, você vai dizer em linguagem natural qual é o papel do seu Agente, quem procura ele e quais pedidos ele resolve.

### O que fazer ✍️

**"Crie um chatbot de atendimento"** é o tipo de pedido que devolve um texto genérico, cheio de **"Olá! Como posso ajudar?"** e nada mais. O modelo não sabe de que empresa você fala, quem é a pessoa do outro lado, nem o que está autorizado a responder.

Comece nomeando três coisas: **o papel do Agente**, **o público que fala com ele** e **a lista curta de assuntos que ele cobre**.

Escolha um cenário que você conheça, pode ser o banco onde você é cliente, a operadora do seu celular ou a loja onde você comprou algo recentemente.

### Antes de escrever, responda para si:

- Que empresa ou serviço esse Agente representa, e em qual canal ele atende? Chat do site, aplicativo, WhatsApp?

- Quem é a pessoa que chega falando com ele, e em que situação? Alguém com pressa, com dúvida simples, com problema já em andamento?

- Quais são os três ou quatro pedidos mais comuns que ele precisa dar conta?

### Modelo para você adaptar📋:

Copie o bloco abaixo no seu editor de texto e preencha os campos entre colchetes:

```

Você é um Agente de atendimento ao cliente de [empresa ou tipo de serviço], atuando no [canal: chat do app, site, WhatsApp].

Quem fala com você: [descrição de quem é o cliente e em que situação ele costuma chegar].

Os pedidos que você resolve são:
- [pedido comum 1]
- [pedido comum 2]
- [pedido comum 3]

Seu objetivo em cada conversa é [o que caracteriza um atendimento bem resolvido, em uma frase].

```

### Exemplo preenchido✨

Veja como ficaria o Modelo acima já preenchido em um caso real (use como referência, não copie literalmente):

```
Você é um Agente de atendimento ao cliente de um banco digital, atuando no chat do aplicativo.

Quem fala com você: pessoa física, cliente do banco, geralmente no celular e com pressa, que já tentou resolver sozinha no app antes de abrir o chat.

Os pedidos que você resolve são:
- Consultar o valor e a data de vencimento da fatura do cartão
- Explicar o motivo de uma cobrança que o cliente não reconhece
- Orientar o passo a passo para desbloquear um cartão novo
- Informar o limite disponível e como pedir aumento

Seu objetivo em cada conversa é responder a dúvida na primeira mensagem sempre que possível, sem pedir informação que o cliente já forneceu.
```

## Passo 2🧱: Dê Contexto, Regras de Conduta e Formato de Resposta

Nesta etapa, você vai somar ao seu prompt o tom de voz, o formato da resposta, os limites do Agente e o que ele faz quando não sabe.

### O que fazer✍️

O Passo 1 disse o que o Agente faz. Falta dizer como ele faz, e principalmente o que ele não faz.

É aqui que mora a diferença entre um atendimento que funciona e um que vira problema. Um Agente sem limite escritos responde qualquer coisa, inclusive o que não tem como saber: inventa um número de protocolo, chuta o valor de uma taxa, promete prazo que ninguém cumpre. O modelo não faz isso por má-fé, faz porque o prompt pediu uma resposta e não ofereceu a saída de admitir que não tem a informação.

Escreva também o que acontece quando o pedido sai do escopo. Todo atendimento tem um ponto em que a conversa precisa ir para uma pessoa, e esse ponto é uma decisão sua, não do modelo.

Antes de escrever, responda para si:

Em que tom essa empresa fala? Formal, próximo, direto? Quantas linhas uma boa resposta tem?
Quais assuntos o Agente nunca deve tratar sozinho, e para onde ele encaminha quando isso acontece?
O que ele responde quando a informação necessária simplesmente não está disponível para ele?
📋 Modelo para você adaptar
Copie o bloco abaixo e cole logo depois do que você escreveu no Passo 1: