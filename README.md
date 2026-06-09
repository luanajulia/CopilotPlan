# 🚀 Guia Prático: Modos do Copiloto (AI Copilot Modes)

Um guia definitivo e prático para entender, dominar e extrair o máximo potencial dos diferentes modos de operação do Copiloto (**Ask, Edit, Plan, Agent e Study**). Saiba exatamente quando e como usar cada um para acelerar seu fluxo de trabalho e aprendizado.

---

## 📌 Índice
- [Visão Geral](#-visão-geral)
- [Os 5 Modos do Copiloto](#-os-5-modos-do-copiloto)
  - [💬 Ask (Perguntar)](#-ask-perguntar)
  - [📝 Edit (Editar)](#-edit-editar)
  - [📅 Plan (Planejar)](#-plan-planejar)
  - [🤖 Agent (Agente)](#-agent-agente)
  - [📚 Study (Estudar)](#-study-estudar)
- [Como Contribuir](#-como-contribuir)

---

## 🔍 Visão Geral

As ferramentas de IA evoluíram de simples caixas de chat para assistentes contextuais complexos. Este repositório centraliza as melhores práticas, exemplos de prompts e casos de uso reais para os 5 principais modos do Copiloto, ajudando você a alternar entre eles com eficiência.

---

## 🛠️ Os 5 Modos do Copiloto

| Modo | Objetivo Principal | Quando Usar? |
| :--- | :--- | :--- |
| **Ask** | Explicar, tirar dúvidas e buscar informações. | Consultas rápidas, documentação e conceitos. |
| **Edit** | Modificar, refatorar ou corrigir trechos de arquivos. | Direto no código ou texto existente. |
| **Plan** | Desenhar arquiteturas e quebrar tarefas complexas. | Antes de começar um projeto ou feature grande. |
| **Agent** | Automação ponta a ponta com múltiplos passos. | Tarefas repetitivas ou buscas complexas na web/arquivos. |
| **Study** | Aprendizado focado, geração de flashcards e resumos. | Revisão de conteúdo e fixação de conhecimento. |

### 💬 Ask (Perguntar)
Focado em conversação e entendimento. O modelo atua como um consultor de conhecimento.
*   **Melhor caso de uso:** "O que este trecho de código faz?" ou "Me explique o conceito de concorrência em Go."
*   **Dica:** Use referências de arquivos ou caminhos específicos para dar contexto.

### 📝 Edit (Editar)
Interfere diretamente nos seus arquivos abertos. Ideal para alterações cirúrgicas.
*   **Melhor caso de uso:** Adicionar tratamento de exceções, refatorar uma função para torná-la mais limpa ou converter um componente.
*   **Dica:** Revise o *diff* gerado antes de aceitar as alterações.

### 📅 Plan (Planejar)
O modo estratégico. Em vez de escrever o código ou texto final imediatamente, a IA cria um passo a passo estruturado.
*   **Melhor caso de uso:** Planejar a migração de um banco de dados ou estruturar os endpoints de uma nova API.
*   **Dica:** Valide o plano gerado pela IA antes de pedir para ela executar o próximo passo.

### 🤖 Agent (Agente)
O Copiloto assume o controle de tarefas de múltiplos passos. Ele pode ler vários arquivos, fazer buscas externas (se habilitado) e encadear ações.
*   **Melhor caso de uso:** "Encontre todas as funções depreciadas no projeto e crie uma issue listando o que precisa ser atualizado."
*   **Dica:** Monitore a execução para garantir que o agente não saia do escopo desejado.

### 📚 Study (Estudar)
Transforma o assistente em um tutor personalizado. Focado em pedagogia, metáforas didáticas e testes de fixação.
*   **Melhor caso de uso:** "Crie um simulado de 5 perguntas sobre algoritmos de ordenação" ou "Me explique isso como se eu tivesse 10 anos."

