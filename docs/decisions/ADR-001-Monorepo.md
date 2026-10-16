# ADR-001 — Monorepo simples

Status: **Aceita pelo usuário**. Registrada em 15/10/2026.

Contexto: projeto educacional com frontend e backend; preferência expressa em FT-003.3.4 e confirmada no pedido de execução atual.

Decisão: manter `apps/api/`, `apps/web/` e `docs/` no mesmo repositório, sem Nx, Turborepo ou workspaces avançados por enquanto. Nesta etapa, as aplicações são apenas diretórios reservados.

Consequências: contexto e histórico ficam juntos; ferramentas, scripts e dependências serão introduzidos em microtarefas futuras. Escolhas de gerenciador de pacotes, versões e orquestração não foram feitas aqui.

[Contexto e fonte](../project-context/Contexto.md) · [Arquitetura futura](../architecture/Visao.md)

[[project-context/Contexto]] · [[architecture/Visao]]
