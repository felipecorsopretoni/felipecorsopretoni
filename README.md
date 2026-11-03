# Felipe Corso Pretoni

**Engenharia de Software — PUC-Campinas (2024–2027)**
Construo sistemas com LLMs em produção: agentes com chamada de ferramentas, recuperação de contexto (RAG), saída estruturada e monitoramento de prompts.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/felipe-corso-pretoni)
[![Gmail](https://img.shields.io/badge/felipepretoni@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:felipepretoni@gmail.com)

---

## O que eu construo

- **Agentes de IA em produção** que atendem usuários reais, consultam dados ao vivo e passam a conversa para um humano quando não têm a resposta.
- **RAG e grounding**: recupero o contexto certo antes de gerar a resposta, para o modelo não inventar.
- **IA com limites claros**: fluxos em que a IA propõe e o servidor valida e aplica, sem dar ao modelo poder sobre o que não deve tocar.
- **Integração de IA com sistemas existentes** via APIs, MCP e WhatsApp Business API.

---

## Projetos em destaque

> Os projetos abaixo atendem clientes reais, por isso o código é privado. Fico à vontade para explicar a arquitetura em detalhe.

### Assistente de Atendimento com IA para Varejo · *em produção*
Agente de IA no WhatsApp que atende clientes de uma loja de iPhones. Usa chamada de ferramentas para consultar catálogo e estoque ao vivo, negociar preço e avisar o dono quando a venda precisa de aprovação. Tem um RAG lexical próprio, sem framework: quando a busca não encontra nada, a conversa vai para um humano em vez de a IA inventar uma resposta.
`Python` `FastAPI` `PostgreSQL` `Gemini via OpenRouter` `Langfuse` `WhatsApp Cloud API` `Next.js` `Docker Swarm`

### Sistema de Gestão de Obras com IA e Conector MCP
Cronograma (Gantt, curva-S), relatórios diários de obra e controle de qualidade. Uma IA lê e-mails do projeto e propõe atualizações de cronograma num fluxo de prévia e aplicação: o servidor recalcula os valores e a IA não altera linha de base nem estrutura. Também expõe um servidor MCP (OAuth 2.1 + PKCE, 28 ferramentas) para operar o painel pelo ChatGPT ou pelo Claude.
`Python` `FastAPI` `PostgreSQL` `TypeScript` `Next.js` `MCP` `Playwright`

### Monitoramento Automatizado de Protocolos para Contabilidade
Robô que acompanha sozinho os protocolos de abertura e alteração de empresas de um escritório de contabilidade, com painel de status e agente local, eliminando a consulta manual.
`Python` `Automação web` `PostgreSQL` `Docker`

### Sistema de Gestão de Varejo
Compras, estoque, vendas, caixa e CRM para uma rede de lojas em duas cidades, com dados separados por loja e clientes compartilhados na rede.
`TypeScript` `Next.js` `React` `Supabase` `Node.js`

### LIAD — Plataforma de Vendas com IA para Lojistas
Assistente de vendas com IA que responde clientes em tempo real com base no catálogo cadastrado pelo lojista.
`Node.js` `TypeScript` `Express` `Google Gemini` `Firebase`

### [Fundamentos de IA e Machine Learning](https://github.com/felipecorsopretoni/inteligencia-artificial-puc)
Implementações da disciplina de IA: KNN, SVM, BFS/DFS, agentes baseados em regras, redes neurais, regressão com gradiente descendente, K-Means e validação K-Fold.
`Python`

<details>
<summary><b>Outros projetos</b></summary>

- **Super ID**: gerenciador de senhas Android com login por QR Code (`Kotlin` `Firebase`)
- **IdoSOS**: app de acompanhamento de saúde entre idoso e cuidador (`Kotlin` `Firestore` `MongoDB`)
- **Avaliador de Funcionários**: app de avaliações com área administrativa (`Kotlin` `Firebase`)
- **MensageriaSegura**: mensagens com criptografia simétrica (`Python` `MongoDB`)
- **Jogo de RPG**: jogo com interface gráfica aplicando POO (`Java`)

</details>

---

## Stack

**IA e LLMs**
![OpenRouter](https://img.shields.io/badge/OpenRouter-GPT%20·%20Claude%20·%20Gemini-6566F1?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-tracing-0A0A0A?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-333333?style=flat-square)
![Function Calling](https://img.shields.io/badge/Function_Calling-RAG-555555?style=flat-square)

**Linguagens**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Back-end, front-end e dados**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Infra e ferramentas**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

**Idiomas:** Português (nativo) · Inglês (avançado)
