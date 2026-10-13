# Fluxo de Desenvolvimento BMAD - MiniTelaModern

Este diretório gerencia o ciclo de vida e a governança do projeto **MiniTelaModern** estritamente alinhado às 5 fases do framework **BMAD** (*Breakthrough Method for Agile AI-Driven Development*).

---

## Estrutura das Fases

### [Fase 1: Negócio e Especificação (Business & Planning)](file:///c:/Users/Marcelo%20Maymone/Documents/antigravity_projetos/minitela_positivo/docs/bmad/1-negocio)
* **Papéis:** Analista de Negócios (`analyst.md`), Gerente de Produto (`product_manager.md`), Designer UX (`bmad-agent-ux-designer.md` / Sally) e Revisor Adversarial (`adversarial_reviewer.md`).
* **Diretriz de UX/UI (/impeccable):** Utilização obrigatória dos comandos `/impeccable init` e `/impeccable shape` para capturar a essência do produto, personas, modo de interação (*Operate*) e diretrizes de experiência de uso.
* **Artefatos Gerados:**
  - `business-brief.md`: Declaração do problema, glossário de linguagem ubíqua, subdomínios DDD e mapeamento de fluxo de valor (VSM).
  - `prd.md`: Documento de Requisitos do Produto com as 5 leis da especificação (Problema, Capacidades, Restrições, Não-Objetivos e Sinais de Sucesso).
  - `revisao-adversarial-fase1.md`: Auditoria cética levantando ao menos 10 furos lógicos e casos de borda antes da aprovação.

### [Fase 2: Arquitetura e Engenharia de Soluções (Solutioning)](file:///c:/Users/Marcelo%20Maymone/Documents/antigravity_projetos/minitela_positivo/docs/bmad/2-arquitetura)
* **Papéis:** Product Owner (`product_owner.md`) e Arquiteto-Chefe Winston (`architect.md`).
* **Diretriz de UX/UI (/impeccable):** Utilização obrigatória da skill `/impeccable` para estruturação do Design System em `DESIGN.md`: tokens visuais, paleta de cores para modo escuro/claro nativo do Windows 11 26H2, tipografia Segoe UI Variable, materiais *Mica* / *MicaAlt*, layout responsivo da janela de configurações e diagramação do display LCD de 240x240 pixels (hierarquia de informação e legibilidade extrema).
* **Artefatos Gerados:**
  - `ARCHITECTURE-SPINE.md`: Consolidação de padrões de design, princípios SOLID, Registros de Decisões de Arquitetura (ADRs) e diagramas Mermaid.
  - `DESIGN.md`: Especificação visual e sistema de tokens de UX/UI concebidos via `/impeccable`.
  - `epics-and-tasks.md` / `task.md`: Decomposição atômica de histórias de usuário e rastreador de tarefas.

### [Fase 3: Desenvolvimento Meticuloso (Implementation)](file:///c:/Users/Marcelo%20Maymone/Documents/antigravity_projetos/minitela_positivo/docs/bmad/3-desenvolvimento)
* **Papéis:** Engenheiro Sênior Amelia (`developer.md`) com simulação Party-Mode (Tech Writer e QA).
* **Diretrizes Técnicas e de Design:**
  - Implementação estrita em C# .NET 9 + WPF-UI, orientada a testes (TDD), sem subprocessos CLI e comentários focados no "porquê".
  - **Execução Impeccable de UI:** Aplicação rígida do `reference/craft-floor.md` do `/impeccable` no código XAML/C#: sem layouts genéricos, micro-interações fluidas do Windows 11, estados vazios (*empty states*), tratamento gracioso de truncamento de texto na tela de 240x240 e refinamento via `/impeccable polish` e `/impeccable harden`.

### [Fase 4: Governança, Segurança e Qualidade (Review & QA)](file:///c:/Users/Marcelo%20Maymone/Documents/antigravity_projetos/minitela_positivo/docs/bmad/4-qualidade-e-seguranca)
* **Papéis:** Auditor de Segurança Vex (`security_auditor.md`), Arquiteto de Testes Quinn (`qa_test_architect.md`) e Auditor de UX/UI.
* **Diretriz de UX/UI (/impeccable):** Auditoria técnica de design com `/impeccable audit` e `/impeccable critique` (verificação de acessibilidade WCAG, contraste em telas pequenas, tempos de resposta e consistência visual com o Windows 11 26H2).
* **Artefatos Gerados:**
  - `security-audit.md`: Modelagem de ameaças, prevenção de TOCTOU e análise de vetores de injeção/falhas seriais.
  - `test-summary.md`: Matriz de rastreabilidade cobrindo 100% dos requisitos funcionais em testes automatizados.
  - `ux-audit-report.md`: Relatório de auditoria heurística e refinamento visual emitido via `/impeccable`.

### [Fase 5: Operacionalização e Entrega Contínua (Operations)](file:///c:/Users/Marcelo%20Maymone/Documents/antigravity_projetos/minitela_positivo/docs/bmad/5-operacionalizacao)
* **Papéis:** Gerente de Operações e Orquestrador BMAD.
* **Artefatos Gerados:**
  - `walkthrough.md`: Roteiro de evidências, validação física no hardware e medições de desempenho/consumo de memória.

