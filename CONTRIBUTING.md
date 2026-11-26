# Guia de contribuição — ALFAS

## Branches
- `main`: código revisto e estável; **proteger no GitHub** contra pushes diretos.
- `develop`: integração das tarefas da sprint.
- `feature/US_A002-use-cases` / `feature/US_A004-dominio` / `feature/US_A006-repositorio`: novas funcionalidades/documentação.
- `fix/<descricao-curta>`: correção.

## Processo de PR
1. Criar issue com US, critérios de aceitação, responsável e estimativa.
2. Criar branch a partir de `develop`, alterar e testar localmente.
3. Abrir Pull Request para `develop` e preencher template.
4. Pedir pelo menos **1 revisão de outro elemento**; corrigir comentários e resolver conversas.
5. Exigir verificações automáticas quando aplicável; fazer squash merge após aprovação.
6. Para entregas, abrir PR de `develop` para `main` e criar tag `sprint-a`.

## Convenções
Commits sugeridos: `docs:`, `feat:`, `fix:`, `test:`, `chore:`. Usar descrições claras e referenciar a issue, ex.: `docs: atualizar README (#12)`.

## Configurações manuais no GitHub
Em Settings > Branches / Rulesets: proteger `main`, exigir PR, pelo menos uma aprovação e checks quando existentes, impedir force push e eliminar branches depois de merge. Em Settings > Collaborators: adicionar colegas e orientador com permissões adequadas. Estas ações **não podem ser executadas por um ficheiro ZIP**.
