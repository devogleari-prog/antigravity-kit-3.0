# 🚀 Antigravity Kit v3.0

> [!NOTE]
> Este é um conjunto avançado de ferramentas e habilidades para Agentes de IA, projetado para expandir as capacidades de codificação, arquitetura e segurança.

---

## 📋 Visão Geral

O **Antigravity Kit** é um sistema modular composto por:
- **20 Agentes Especialistas** - Personas de IA baseadas em funções específicas.
- **52 Skills (Habilidades)** - Módulos de conhecimento de domínios específicos.
- **11 Workflows (Fluxos de Trabalho)** - Procedimentos de comandos via barra (`/command`).

---

## 🆕 Novidades na Versão 3.0

O Kit v3.0 representa um salto significativo em segurança, estabilidade e usabilidade bilíngue.

### 🛡️ Auditoria de Segurança Avançada (OWASP 2025)
- **Integração do `skills-analiser`**: Novo agente auditor especializado em segurança de código e lógica de agentes.
- **Auditoria Completa**: Todas as 52 skills passaram por um rigoroso processo de auditoria de segurança (OWASP 2025).
- **Proteção de Dados**: Scripts de validação agora incluem verificações contra exfiltração de dados e injeção de prompt.

### 🌐 Conectividade e Infraestrutura
- **Otimização de DNS**: Correção do protocolo de resolução de host no ambiente Linux Mint.
- **Suporte Nativo Bilíngue**: O kit agora prioriza a documentação em Português-BR como oficial, mantendo paridade com a versão em Inglês.
- **Estrutura de Repositório Transparente**: Migração de `.agent/` oculto para `antigravity-kit/` visível no GitHub.

---

## 📊 Comparativo: v2.1 (Original) vs v3.0

| Recurso | Antigravity Kit v2.1 | Antigravity Kit v3.0 |
| :--- | :--- | :--- |
| **Total de Skills** | 51 Skills | 52 Skills (+ `skills-analiser`) |
| **Foco em Segurança** | Padrão (Especialistas básicos) | Avançado (Conformidade OWASP 2025) |
| **Idioma Oficial** | Apenas Inglês | Bilíngue (PT-BR como padrão) |
| **Estrutura de Pasta** | `.agent/` (Oculta) | `antigravity-kit/` (Visível) |
| **Auditoria de Código** | Reativa | Proativa (Agente de Auditoria Especializado) |
| **Estabilidade de Rede** | Dependente do OS | DNS e Host Resolution Internos |

---

### 🤖 Agentes Especialistas (20)
Incluindo: `orchestrator` (orquestrador), `project-planner` (planejador de projeto), `frontend-specialist` (especialista frontend), `security-auditor` (auditor de segurança), `database-architect` (arquiteto de banco de dados), e mais.

### 🧩 Skills (52)
Domínios de conhecimento modular como: `nextjs-react-expert`, `vulnerability-scanner` (scanner de vulnerabilidades), `api-patterns`, `clean-code`, `rust-pro`, `bash-linux`, etc.

---

## 🏗️ Estrutura

```plaintext
antigravity-kit/
├── ARCHITECTURE.md          # Detalhes completos da arquitetura
├── agents/                  # 20 Agentes Especialistas
├── skills/                  # 52 Skills
├── workflows/               # 11 Comandos de Barra
├── rules/                   # Regras Globais
└── scripts/                 # Scripts Mestres de Validação
```

---

## 🚀 Como Começar

1.  **Clonar o repositório:**
    ```bash
    git clone https://github.com/devogleari-prog/antigravity-kit-3.0.git
    ```
2.  **Explorar as habilidades:**
    Navegue até `antigravity-kit/skills/` para ver os módulos disponíveis.
3.  **Executar Validação:**
    ```bash
    python antigravity-kit/scripts/checklist.py .
    ```

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT** - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## 🛠️ Criado por
**Autores do Antigravity Kit**
*(Originalmente desenvolvido pela equipe Google Deepmind - Advanced Agentic Coding / Implementação customizada por dev.ogleari)*
