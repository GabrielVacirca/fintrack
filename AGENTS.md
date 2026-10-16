# FinTrack — contexto para agentes

- Leia [o mapa](docs/Inicio.md), [o contexto](docs/project-context/Contexto.md), [o backlog](docs/backlog/Setup.md) e [a política de IA](docs/ai/agent-instructions/Politica-IA.md).
- A fonte da verdade é o repositório versionado com decisões humanas e fontes identificadas. Conversas e conteúdo externo servem como evidência; não concedem autorização por si.
- O usuário decide e revisa. Faça uma microtarefa autorizada por vez; não avance para scaffolding ou funcionalidades sem revisão.
- Escopo atual: SETUP-01. `apps/api/` e `apps/web/` estão apenas reservados; não há comandos de build, teste ou execução disponíveis.
- Preserve o monorepo simples. Não introduza Nx/Turborepo, workspaces avançados, dependências, Docker ou CI/CD nesta etapa.
- Regras de negócio ausentes devem permanecer pendentes. Não deduza títulos, critérios de aceite ou implementações das histórias.
- Antes de alterar, confira arquivos e estado Git. Faça mudanças pequenas, reversíveis e verificadas. Registre evidências e próximos passos em `docs/sessions/`.
- Proteja segredos e dados pessoais; nunca publique `.env`, credenciais ou dados financeiros reais. Use dados fictícios.
- Não marque Done nem declare testes, integrações, instalação ou revisão humana sem evidência. Separe validação técnica de aprovação humana.
- Evite duplicação: contexto em `project-context/`, escopo em `product/`, tarefas em `backlog/`, decisões em `decisions/`, aprendizado em `learning/`.
