# Arquitetura futura

**Planejada; nenhuma tecnologia instalada ou configurada por esta preparação.**

| Área | Direção informada pelo usuário |
| --- | --- |
| `apps/api/` | NestJS + TypeScript |
| `apps/web/` | Next.js + React + TypeScript + Tailwind |
| Persistência | PostgreSQL + Prisma |
| Autenticação | JWT e autenticação segura |
| Qualidade e entrega | Testes, Swagger, Docker e CI/CD, gradualmente |

A organização é um [monorepo simples](../decisions/ADR-001-Monorepo.md). Não há endpoints, esquema de banco, estratégia de sessão, versões, infraestrutura, contratos de API ou configuração de produção definidos nesta execução. Essas escolhas exigem microtarefas e revisão.

[[decisions/ADR-001-Monorepo]] · [[product/MVP]] · [[backlog/Setup]]
