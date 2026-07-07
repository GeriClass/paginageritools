# paginageritools

Ferramentas e skills para criação de páginas web (GeriClass).

## Skills de frontend instaladas

As skills abaixo ficam em `.claude/skills/` e são carregadas automaticamente pelo Claude Code em qualquer sessão neste repositório. São as skills oficiais da Anthropic (fonte: [anthropics/skills](https://github.com/anthropics/skills)).

| Skill | Para que serve |
| --- | --- |
| `frontend-design` | Direção visual e estética para interfaces web — tipografia, paleta, layout — evitando visual genérico/"template". |
| `web-artifacts-builder` | Construção de páginas e apps web elaborados com React, Tailwind CSS e shadcn/ui (estado, rotas, componentes). |
| `theme-factory` | Aplicação de temas visuais prontos (ou criação de temas sob medida) para páginas, landing pages e apresentações. |
| `webapp-testing` | Teste de páginas e apps web no navegador via Playwright — capturas de tela, verificação de fluxos e depuração. |

## Como usar

Basta pedir em uma sessão do Claude Code neste repositório, por exemplo:

- "Crie uma landing page para o Pós Geriatria" → usa `frontend-design` + `web-artifacts-builder`
- "Aplique um tema mais sóbrio nessa página" → usa `theme-factory`
- "Teste se o formulário da página funciona" → usa `webapp-testing`
