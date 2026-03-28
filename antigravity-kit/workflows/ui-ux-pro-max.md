---
description: AI-powered design system generation and implementation using web-artifacts-builder and theme-factory.
---

# /ui-ux-pro-max - Premium Design Workflow

Este comando ativa o modo de design de alta performance, utilizando o ecossistema de artefatos avançados e o motor de temas do Antigravity Kit.

---

## 🎨 Design Stack

Sempre utilize as seguintes skills em conjunto para resultados premium:

- `web-artifacts-builder`: Para criação de componentes complexos (React + Tailwind + shadcn/ui).
- `theme-factory`: Para aplicação de paletas cromáticas e tipografia profissional.
- `brand-guidelines`: Para garantir conformidade com a identidade visual da Anthropic/Antigravity.
- `nextjs-react-expert`: Para otimização de performance e Core Web Vitals.

---

## 🛠️ Workflow Steps

### Passo 1: Definição Estética (Theme Factory)
Antes de gerar código, escolha ou gere um tema base:
- Utilize a skill `theme-factory` para selecionar um dos 10 temas pré-definidos (ex: `glassmorphism`, `minimalist-dark`, `neo-brutalism`).
- Defina a paleta primária, secundária e a escala tipográfica.

### Passo 2: Construção de Componentes (Web Artifacts Builder)
Com o tema definido, proceda para a montagem da interface:
- Utilize `web-artifacts-builder` para gerar arquivos `.tsx` multi-componente.
- Garanta o uso de `shadcn/ui` para componentes de complexidade (modais, tabelas, formulários).
- **Regra de Ouro**: Evite arquivos únicos gigantes; prefira uma estrutura modular.

### Passo 3: Refinamento e Micro-interações
- Adicione transições suaves com Tailwind (`transition-all duration-300`).
- Garanta os estados de `hover` em todos os elementos clicáveis (`cursor-pointer`).
- Utilize a skill `nextjs-react-expert` para garantir que não haja "waterfalls" de renderização.

---

## 📑 Iconografia e Ativos
- **NÃO use emojis como ícones.**
- Use `lucide-react` ou `heroicons`.
- Para logos de marcas, consulte `brand-guidelines`.

---

## 📋 Checklist de Entrega Premium

### Visual & Marca
- [ ] O tema aplicado via `theme-factory` está consistente em todas as páginas?
- [ ] A paleta de cores respeita os contrastes de acessibilidade (WCAG AA)?
- [ ] Os ícones são vetoriais (SVG/Lucide) e possuem tamanhos consistentes?

### Interatividade
- [ ] Todos os elementos interativos possuem feedback visual ao passar o mouse?
- [ ] As animações são sutis (entre 150ms e 300ms)?
- [ ] O layout é totalmente responsivo (Mobile-first)?

### Código & Performance
- [ ] O código utiliza componentes `shadcn/ui` onde aplicável?
- [ ] Não há "hardcoded colors"; todas as cores vêm do sistema de temas?
- [ ] O bundle foi otimizado seguindo as regras da skill `nextjs-react-expert`?

---

## 🚀 Exemplo de Prompt para o Agente

> "Use a skill **theme-factory** para aplicar o tema 'Modern Dashboard Dark' e depois a skill **web-artifacts-builder** para criar uma página de analíticos com gráficos responsivos e um sidebar colapsável, garantindo que o design siga as **brand-guidelines**."