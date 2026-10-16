# FinTrack

Projeto de portfólio educacional de finanças pessoais para aprender Full Stack/Backend e AI Engineering.

**Estado: planejamento e preparação inicial. Nenhuma funcionalidade do MVP implementada.**

O repositório contém documentação e diretórios reservados. Ainda não existem dependências, comandos de execução, aplicação, banco, testes, Docker ou CI/CD configurados.

- [Comece pelo mapa do projeto](docs/Inicio.md).
- [Contexto e fontes](docs/project-context/Contexto.md).
- [MVP: 5 épicos e 19 histórias aprovadas](docs/product/MVP.md).
- [Microtarefas e fluxo](docs/backlog/Setup.md).
- [Arquitetura futura](docs/architecture/Visao.md).
- [Regras para agentes](AGENTS.md).

## Estrutura

```text
apps/api/   # reservado para NestJS + TypeScript
apps/web/   # reservado para Next.js + React + TypeScript + Tailwind
docs/       # fonte de contexto versionada e vault Obsidian
```

Monorepo simples, sem Nx/Turborepo ou workspaces avançados. As tecnologias serão introduzidas gradualmente após revisão humana.

## Consultar a documentação

No GitHub, use os links Markdown do mapa. No Obsidian, selecione **Abrir pasta como vault** e escolha a pasta `docs/` deste repositório. Abra `Inicio.md` e a visualização de grafo para navegar pelas conexões `[[wikilinks]]`. Não é necessário instalar plugins. A instalação ou abertura do Obsidian não foi verificada nesta preparação.

A visibilidade pública foi escolhida pelo usuário. Use apenas exemplos fictícios; não envie segredos ou dados financeiros pessoais.
