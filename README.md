# 📚 Portfólio Python & Inteligência Artificial

Este repositório reúne **notebooks práticos de Python, Inteligência Artificial e LLMs**, desenvolvidos ao longo de estudos, cursos e projetos aplicados, com foco em **IA Generativa, Agentes Autônomos, LangGraph, RAG e aplicações reais em negócios**.

Todo o conteúdo foi criado e executado no **Google Colab**, com abordagem prática, didática e orientada a casos reais.

---

## 🚀 Conteúdos do Repositório

### 🧠 Inteligência Artificial & LLMs
- **Human in the Loop**  
  Conceitos e práticas para integração da tomada de decisão humana em sistemas de IA.

- **LLMs para Empresas e Negócios**  
  Aplicações práticas de LLMs em diferentes áreas:
  - Marketing  
  - Atendimento e Suporte  
  - Recursos Humanos  
  - Educação  
  - Finanças  

- **Preparação e Fundamentos em IA**  
  Conceitos essenciais sobre LLMs, contexto, prompting e uso estratégico em ambientes corporativos.

---

### 🤖 Agentes Autônomos & LangGraph
- **Fundamentos do LangGraph (DascIA Academy)**  
  Introdução à arquitetura baseada em grafos, estados e fluxos de agentes.

- **Criando seus primeiros Agentic Workflows**  
  Criação prática de fluxos agentic com:

- Estados persistentes  
- Execução condicional  
- Orquestração de múltiplos agentes  

- **Routers & Arquitetura de Agentes**  
  Estratégias de:

- Modularização  
- Separação de responsabilidades  
- Encaminhamento inteligente entre agentes

- **Routers Preditivos (LLM Routing)**  
  Uso de LLMs como camada decisória para escolher dinamicamente qual agente ou fluxo deve ser executado.

- **LangGraph do Zero — Aula Prática**  
  Construção passo a passo de um agente funcional utilizando LangGraph.

---

### 🔎 RAG — Retrieval-Augmented Generation

- **Curso de RAG (DascIA Academy)**  
  Desenvolvimento de pipelines completos de RAG aplicando:

  - Indexação e chunking de documentos  
  - Criação de embeddings  
  - Armazenamento em Vector Store  
  - Recuperação semântica de contexto  
  - Enriquecimento dinâmico de prompts  
  - Integração estruturada com LLMs  

  Foco em aplicações corporativas, bases privadas de conhecimento e sistemas de consulta inteligente.

---

### 🎨 IA Generativa & Ferramentas

- **ComfyUI no Google Colab**  
  Implementação prática de pipelines de geração de imagens com IA, incluindo:

  - Configuração de ambiente no Colab  
  - Execução de workflows visuais  
  - Manipulação de modelos generativos  
  - Customização de parâmetros para controle de geração  

  Aplicação voltada para experimentação, prototipagem e compreensão da arquitetura de modelos de difusão.

---

### 🐍 Fundamentos de Python

- **Python Básico (DascIA Academy)**  
  Domínio de:

  - Sintaxe e estrutura da linguagem  
  - Variáveis e tipos de dados  
  - Estruturas condicionais e loops  
  - Funções e organização básica de código  

- **Fundamentos de Programação**  
  Desenvolvimento de raciocínio lógico aplicado a:

  - Resolução de problemas  
  - Estruturação algorítmica  
  - Boas práticas iniciais  

- **Format e f-strings**  
  Uso moderno de formatação de strings para geração dinâmica de textos e construção de mensagens estruturadas.

- **Conversão e Manipulação de Tipos**  
  Casting entre tipos (int, float, str, bool), validação de dados e boas práticas para evitar erros em tempo de execução.

---

# 📊 Projetos Práticos

## 🌦️ Final Project — AUS Weather

Projeto aplicado utilizando dados climáticos da Austrália para:

- Manipulação e análise de dados  
- Tratamento de datasets  
- Estruturação lógica de código  
- Aplicação prática de fundamentos de Python  

Projeto focado em consolidação técnica e raciocínio analítico.

---

# ⭐ Projetos em Destaque

## 🚀 1️⃣ Text2SQL Agent

Agente inteligente capaz de:

- Receber perguntas em linguagem natural  
- Interpretar intenção do usuário  
- Gerar queries SQL automaticamente  
- Consultar banco de dados  
- Retornar respostas estruturadas  

### Tecnologias:
- Python  
- LLMs  
- Arquitetura de Agente  
- Orquestração de fluxo  

Aplicação prática de IA para análise de dados orientada por linguagem natural.

---

## ⚡ 2️⃣ API Profissional com FastAPI

Projeto estruturado utilizando:

- FastAPI  
- Docker  
- Docker Compose  
- Alembic (migrations)  
- Arquitetura modular  
- Variáveis de ambiente  
- Estrutura pronta para produção  

### Conceitos aplicados:
- Criação de rotas REST  
- Validação com Pydantic  
- Separação por camadas  
- Organização profissional de projeto  
- Preparação para deploy  

Projeto voltado para construção de APIs modernas e escaláveis em Python.

---

## 🌦️ 3️⃣ AUS Weather — Projeto de Análise de Dados

Projeto de análise e manipulação de dados climáticos aplicando:

- Fundamentos de Python  
- Estruturação lógica  
- Limpeza e manipulação de dados  

Representa a consolidação da base técnica para evoluções em Data Science e IA.

---

## 🏆 4️⃣ Prompt Packer
Script de engenharia de prompt que:

- Recebe via terminal:
  - Role  
  - Tom de voz  
  - Tarefa  
  - Número máximo de palavras  

- Monta prompt estruturado com f-strings  
- Estima quantidade de palavras (1 palavra ≈ 6.11 caracteres)  
- Valida se está dentro do intervalo aceitável (±10 palavras)  

Aplicação prática de controle de saída de LLMs.

---

## 🏆 5️⃣ Persistent Chat History
Chat de terminal com memória persistente:

- Lê histórico salvo em `.txt`  
- Loop contínuo até `/stop`  
- Salvamento incremental com `with open()`  
- Estrutura organizada por roles  

Aplicação de persistência e controle de contexto.

---

## 🏆 6️⃣ Token Cost Calculator
Mini-biblioteca para estimar custo mensal de modelos:

- Tabela de custo por modelo  
- Cálculo baseado em tokens de entrada e saída  
- Consideração de janela de contexto crescente  
- Registro automático em `log.txt`  

Aplicação prática de controle financeiro de LLMs.

---

## 🏆 7️⃣ Model Provider SDK
Mini-SDK orientado a objetos:

- Classe base abstrata  
- Simulação de provedores  
- Validação de API Key  
- Controle de latência  
- Padronização de retorno  

Aplicação de POO para arquitetura extensível.

---

## 🏆 8️⃣ Simple Vector Store
Armazenamento vetorial em memória com:

- Vetores NumPy  
- Cálculo de similaridade por distância de cosseno  
- Ordenação por menor distância  
- Retorno Top-K  

Base para sistemas RAG customizados.

---

## 🏆 9️⃣ Fine-Tuning Dataset Prepper
Pipeline ETL completo:

- Normalização de roles (human/ai)  
- Remoção de dados sensíveis  
- Parse de datas  
- Deduplicação  
- Transformação para JSONL  
- Exportação pronta para fine-tuning  

Aplicação real de engenharia de dados para IA.

---

## 🏆 🔟 Token Usage Dashboard
Dashboard orientado a objetos para análise de datasets:

- Leitura de JSONL  
- Estimativa de tokens  
- Classificação de tópicos por regras  
- Geração de histogramas e gráficos  

Aplicação de análise quantitativa em datasets de treinamento.

---

## 🏆 1️⃣1️⃣ The CLI Assistant
Assistente de terminal com:

- Memória persistente  
- Ferramentas integradas (contagem de palavras, data/hora)  
- Estrutura baseada em agente  
- Loop interativo  
- Integração com modelo LLM  

Aplicação prática de arquitetura agentic em ambiente CLI.

---

## 🛠️ Tecnologias Utilizadas
- Python  
- Jupyter Notebook  
- Google Colab
- FastAPI
- Docker & Docker Compose
- Alembic
- LLMs (aplicações práticas)  
- LangGraph  
- RAG (Retrieval-Augmented Generation)  
- ComfyUI  

---

## 🎯 Objetivo do Repositório
Este repositório tem como objetivo:
- Consolidar conhecimento técnico em **Python e IA**
- Demonstrar evolução prática como AI Engineer
- Servir como **portfólio técnico profissional**
- Demonstrar aplicações reais de IA em **negócios e automações**
- Construir base sólida para agentes autônomos e APIs inteligentes

---

## 👤 Autor
**Diego Hugo**  
Especialista em Inteligência Artificial com foco em **Automações Inteligentes, Agentes Autônomos e Python**

📌 Áreas de atuação:
- IA Generativa  
- Agentes Autônomos (LangGraph)  
- RAG  
- APIs com FastAPI 
- Automação Inteligente (Python / n8n)  
- Aplicações reais de IA para empresas  

---

## 📄 Observações
- Os notebooks são independentes e podem ser executados separadamente no **Google Colab**
- Os projetos estruturados seguem padrão profissional
- O conteúdo é voltado tanto para aprendizado quanto para aplicação prática em projetos reais

🚀 Fique à vontade para explorar, estudar, adaptar e evoluir os códigos.
