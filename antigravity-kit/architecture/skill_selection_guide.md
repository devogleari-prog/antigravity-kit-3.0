# Skill Selection Guide: Anthropic vs. Antigravity Kit 2.1

Este guia serve como referência para decidir qual versão de uma habilidade (*skill*) utilizar quando houver sobreposição entre o repositório da Anthropic e o Antigravity Kit 2.1.

> [!IMPORTANT]
> Apenas as três habilidades abaixo possuem versões em ambos os repositórios. Para todas as outras (como `pdf`, `docx`, `xlsx`, etc.), utilizamos as versões migradas da Anthropic que agora residem permanentemente no Kit 2.1.

---

## 1. Frontend Design (`frontend-design`)

| Usar Versão **Anthropic** | Usar Versão **Kit 2.1** |
| :--- | :--- |
| **Foco:** Estética radical, artesanal e memorável. | **Foco:** UX baseada em dados, performance e acessibilidade. |
| **Quando optar:** Briefings abertos, landing pages de alto impacto, componentes visuais experimentais. | **Quando optar:** Aplicações SaaS complexas, dashboards de alta densidade, sistemas que exigem consistência rigorosa. |
| **Diretiva:** "Fuja do comum, use tipografias únicas." | **Diretiva:** "Siga as leis da UX (Hick, Fitts), use o Grid de 8 pontos." |

---

## 2. MCP Builder (`mcp-builder`)

| Usar Versão **Anthropic** | Usar Versão **Kit 2.1** |
| :--- | :--- |
| **Foco:** Workflow de produto e validação de LLM. | **Foco:** Arquitetura técnica e padrões de segurança. |
| **Quando optar:** Integração de novas APIs complexas que exigem testes de "entendimento" da IA via XML de avaliação. | **Quando optar:** Implementação técnica pura, padrões de transporte (SSE/Stdio), segurança de tokens e segredos. |
| **Stack:** TypeScript (SDK oficial) como primeira opção. | **Stack:** Arquitetura agnóstica de linguagem com foco em padrões de ferramentas. |

---

## 3. Web App Testing (`webapp-testing`)

| Usar Versão **Anthropic** | Usar Versão **Kit 2.1** |
| :--- | :--- |
| **Foco:** Operação tática e resolução de bugs de UI. | **Foco:** Estratégia de qualidade e auditoria sistêmica. |
| **Quando optar:** Captura rápida de screenshots, inspeção dinâmica do DOM em apps complexos, debug de seletores. | **Quando optar:** Auditoria de acessibilidade, testes visuais de regressão, organização da suíte de testes (Pirâmide). |
| **Método:** Reconhecimento -> Ação (Playwright dinâmico). | **Método:** Auditoria Automatizada -> Relatório (Scripts de auditoria). |

---

## Como aplicar no Planejamento
Sempre que uma tarefa envolver um destes três temas, a seção de "Seleção de Skill" no plano de implementação deve indicar a escolha baseada nestes critérios.
