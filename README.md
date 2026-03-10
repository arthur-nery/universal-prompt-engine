# ♾️ Universal Prompt Engine (UPE) v1.0

**Universal Prompt Engine (UPE)** é um **meta-prompt universal** criado para gerar prompts muito mais claros, completos e eficazes para qualquer LLM.

Em vez de pedir algo diretamente para a IA, o UPE conduz uma **entrevista estruturada** com o usuário para coletar contexto, restrições e objetivos antes de gerar o prompt final.

O resultado é um prompt **mais preciso, mais inteligente e com respostas significativamente melhores**.

---

# 🧠 O que é um Meta-Prompt

Um **meta-prompt** é um prompt que tem como objetivo **criar outros prompts**.

Em vez de perguntar diretamente para a IA, você primeiro usa o UPE para:

1. Explorar o problema
2. Estruturar o contexto
3. Definir restrições
4. Refinar o objetivo

Depois disso, o UPE gera um **prompt otimizado** pronto para ser usado em qualquer LLM.

---

# 🎯 Objetivo do Projeto

Este projeto foi criado com dois objetivos principais:

1. **Explorar publicamente meus projetos relacionados a IA**
2. **Tornar o uso de IA mais acessível e eficiente**

Embora esta versão seja mais robusta e útil para usuários técnicos, o foco do projeto sempre será **manter simplicidade e eficiência**, permitindo que pessoas com menos conhecimento técnico também consigam obter melhores resultados com IA.

---

# ⚙️ Como Funciona

O UPE opera em três etapas principais:

### 1️⃣ Entrevista

O sistema faz perguntas ao usuário para entender:

- objetivo
- contexto
- restrições
- formato desejado de saída

---

### 2️⃣ Identificação do Tipo de Prompt

O UPE identifica automaticamente se o caso exige:

- **Master Prompt** (sobre o usuário)
- **Prompt de Solução** (sobre um problema específico)

---

### 3️⃣ Geração do Prompt Final

O UPE cria um prompt completo utilizando técnicas modernas de prompt engineering como:

- **Act As (Role Definition)**
- **First Principles**
- **Deep Research**
- **Devil’s Advocate**
- **Constraints First**
- **Format As**
- **Verify & Cite**

---

# 🧭 Modos de Entrevista

O usuário pode escolher o nível de profundidade da entrevista.

### Modo 1 — Simples

3 a 5 perguntas essenciais.

Ideal para tarefas rápidas.

---

### Modo 2 — Consultivo

6 a 10 perguntas estruturadas.

Ideal para planejamento, projetos e decisões.

---

### Modo 3 — Profundo

10+ perguntas exploratórias.

Ideal para problemas complexos ou estratégicos.

---

# 🚀 Quick Start

1. Copie o prompt do **Universal Prompt Engine**.
2. Cole em uma LLM (ex: ChatGPT).
3. Responda às perguntas feitas pelo sistema.
4. Quando terminar a entrevista digite: *"Pronto"*
5. O UPE irá gerar um **prompt final otimizado**.  
  
---  
  
# 💡 Exemplo  
  
Problema original:  *"Quero ganhar dinheiro"*
  
Após usar o UPE: *"Estou com X reais disponíveis, trabalho com Y, tenho interesse em Z e quero gerar renda adicional em até 3 meses usando habilidades digitais."*

Esse nível de contexto permite que a LLM produza **respostas muito mais úteis e específicas**.  
  
---  
  
# 🧪 Status do Projeto  
  
Versão atual: **v1.0**  
  
Testado em:  
  
- ChatGPT  
  
Este projeto ainda é **experimental** e também serve como **projeto educacional** sobre meta-prompts e engenharia de prompts.  
  
---  
  
# 🛣️ Roadmap  
  
Possíveis melhorias futuras:  
  
- Melhor retenção do usuário durante a entrevista  
- Melhor adaptação para usuários do plano gratuito  
- Otimização da lógica de entrevista  
- Biblioteca de prompts gerados  
  
---  
  
# 👤 Autor  
  
Criado por **Arthur Nery**.  
  
---  
  
# 📄 Licença  
  
MIT License

---

# 📦 Arquivo do Prompt

O prompt completo do **Universal Prompt Engine v1.0** está disponível neste repositório.

Para utilizá-lo:

1. Abra o arquivo `upe-v1.0.md`
2. Copie **todo o conteúdo do prompt**
3. Cole em uma LLM de sua preferência (ex: ChatGPT)
4. Inicie o processo de entrevista com a IA

O UPE então conduzirá uma entrevista estruturada antes de gerar o prompt final.

---

# 🧑‍💻 Como Utilizar

O fluxo de uso do UPE é simples:

1. Copiar o prompt do arquivo do projeto
2. Colar em uma LLM
3. Responder às perguntas da entrevista
4. Digitar **"Pronto"** quando terminar

Após isso o sistema irá gerar um **prompt refinado e otimizado** para resolver o problema apresentado.

---

# 🙏 Inspiração

Algumas ideias de estruturação de prompts utilizadas neste projeto foram **inspiradas por conceitos compartilhados pelo empreendedor e educador em IA Dan Martell**.

Em especial os conceitos relacionados a:

- Master Prompts
- System Prompts
- Estruturação de prompts
- Uso de entrevistas para gerar contexto antes da execução da tarefa

Parte dessas ideias aparece no vídeo:

**How to Get Ahead of 99% of People (with AI)**  
https://youtu.be/bkM-lYgAxh0

Este projeto é uma **implementação independente inspirada nesses conceitos**, adaptada para criar um meta-prompt universal reutilizável.