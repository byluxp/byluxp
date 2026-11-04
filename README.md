<div align="center">

# LUCILA VITÓRIA

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00F0FF&center=true&vCenter=true&width=720&lines=Construo+ferramentas+com+IA;Automa%C3%A7%C3%A3o+para+qualquer+setor.)](https://git.io/typing-svg)

Estudante de Análise e Desenvolvimento de Sistemas · 7 anos em EHS na indústria e na mineração · Belo Horizonte, MG

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucila-cardoso/)
[![E-mail](https://img.shields.io/badge/E--mail-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:lucila.vitoria@outlook.com.br)

</div>

---

## ⚡ // SOBRE MIM

> **"Transformando riscos em decisões e conhecimento de negócio em sistema."**

Passei anos em obras e fábricas vendo a mesma cena: documentos chegando pelo WhatsApp, planilhas conferidas linha por linha, prazos vencendo sem ninguém perceber. Hoje eu construo as ferramentas que eu queria ter tido nessa rotina: sistemas e robôs que usam IA para ler documentos, cruzar dados e avisar o que está faltando.

O que eu trago de diferente é conhecer o problema por dentro. Antes de escrever código, eu já sei qual regra não pode falhar, qual documento vence e quem vai usar a ferramenta no dia a dia.

---

## 🚀 // O QUE EU CONSTRUÍ

### 🦺 SicherPlan: gestão de Saúde e Segurança do Trabalho
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
· [repositório](https://github.com/byluxp/sicherPlan)

<img src="https://raw.githubusercontent.com/byluxp/sicherPlan/main/docs/img/sicherplan-demo.gif" alt="Demonstração do SicherPlan com dados fictícios" width="720"/>

- **Problema:** o controle de EPIs, exames (ASO), treinamentos e vencimentos vive em planilhas soltas e no papel.
- **Solução:** sistema full stack que centraliza colaboradores, EPIs, ASOs e treinamentos, mostra um painel de vencimentos e gera certificados de NR.
- **IA no produto:** lê RG, CNH, ASO e o certificado de aprovação do EPI em PDF e preenche o cadastro.
- **Regra que importa:** o sistema **bloqueia o certificado de NR-35 para quem está inapto para trabalho em altura**. Uma regra de negócio que protege uma vida.

### 🤖 Robô de documentos de SST no WhatsApp
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)
· 🔒 código privado (uso interno) · [estudo de caso](https://github.com/byluxp/robo-documentos-sst-case)

- **Problema:** empresas terceirizadas mandam dezenas de documentos (ASO, ficha de EPI, treinamentos de NR) pelo WhatsApp, muitas vezes todos num único PDF. Alguém precisava abrir, separar por funcionário, renomear e conferir o que faltava.
- **Solução:** o robô recebe os arquivos, a IA identifica cada página e o funcionário, divide os PDFs, salva nas pastas padrão, confirma o que recebeu e cobra o que falta.
- **Resultado:** cerca de **30 segundos por envio, contra 5 minutos à mão**, em fase de testes no trabalho.
- **Decisões:** roda no meu computador e não num servidor, para não arriscar o bloqueio do número; só conversa com números liberados; alerta sobre dados pessoais e de saúde no plano gratuito da IA (LGPD).

### 🧾 Automação de orçamentos
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=FFE600)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
· 🔒 código privado (dados de clientes) · [estudo de caso](https://github.com/byluxp/automacao-orcamentos-case)

- **Problema:** em cada orçamento, alguém precisava achar à mão, numa planilha mestra, o serviço equivalente a cada linha da planilha do cliente.
- **Solução:** o script compara as descrições com **TF-IDF** (por caracteres e por palavras), um dicionário de sinônimos e uma lista de **"falsos amigos"**, palavras parecidas com significado diferente, como *rede* e *parede*. Cada linha sai com um nível de confiança.
- **O que aprendi:** semelhança de texto achava "demolição em m³" igual a "demolição em m²". Num orçamento, a unidade muda o preço inteiro. A próxima etapa é tornar a unidade uma regra obrigatória e medir o acerto contra um gabarito.

---

## 🧠 // COMO EU USO IA PARA CONSTRUIR

- **Claude Code** como par de programação no dia a dia: planejo, reviso e testo junto com ele.
- **Gemini API dentro dos produtos**, para ler documentos e devolver dados estruturados em JSON.
- **As decisões continuam comigo:** quais regras não podem falhar, o que uma pessoa precisa validar e onde ficam os dados de quem usa.

---

## 🤝 // CONTRIBUIÇÕES E ESTUDOS

| Projeto | O que eu fiz |
| :--- | :--- |
| 🤖 [Bot Tech Girls](https://github.com/byluxp/discord-bot-tech-girls) | **Contribuição** num bot de Discord da comunidade Tech Girls. Minha parte:<br>• **Automação com IA:** o agente que lê a notícia, decide se é relevante, resume em 3 linhas e devolve **JSON validado** para o Discord.<br>• **Busca de vagas com a API JSearch:** configurei e ativei a busca, que confere cada vaga no link antes de postar com função, empresa e descrição, dentro da cota gratuita.<br>• **Documentação de testes:** 34 testes com `pytest` e avaliação de modelos de IA com notícias reais, medidos antes e depois de cada mudança (ex.: 15 de 18 acertos com o modelo novo). |
| 📈 [BIA, agente financeiro](https://github.com/byluxp/dio-lab-bia-do-futuro) | Desafio da DIO: agente com Gemini e Streamlit que responde com base numa base de conhecimento, com regras contra alucinação. |

---

## 🛠️ // STACKS E FERRAMENTAS

<div align="center">

### **IA e Automação**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFE600)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

### **Desenvolvimento**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### **Dados e Ambiente**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=00F0FF)
![SQL](https://img.shields.io/badge/SQL-00F0FF?style=for-the-badge&logo=postgresql&logoColor=000)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### **📚 Estudando agora**
![n8n](https://img.shields.io/badge/n8n-FF6584?style=for-the-badge&logo=n8n&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-8A2BE2?style=for-the-badge&logoColor=white)

</div>

---

## 📊 // TAMBÉM FAÇO ANÁLISE DE DADOS

- [Análise de dados de One Piece](https://github.com/byluxp/projeto-data-analysis-one-piece): Python.
- [Trilha de análise de dados](https://github.com/byluxp/analise-de-dados-nivel-basico): e-commerce Olist com SQL, Excel, Power BI e Python (em andamento).

---

<div align="center">

*⚡ "Sorte é o que acontece quando a preparação encontra a oportunidade." ⚡*

</div>
