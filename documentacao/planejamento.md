# 🧭 Planejamento do Repositório

## Seções definidas

| Seção | Pasta | Objetivo |
|---|---|---|
| Site (GitHub Pages) | raiz (`index.html`, `assets/`) | Vitrine pública do portfólio |
| Projetos acadêmicos | `projetos-academicos/` | Trabalhos das disciplinas |
| Projetos pessoais | `projetos-pessoais/` | Projetos de estudo próprio |
| Documentação | `documentacao/` | Planejamento, slides, roteiro, integração |
| Histórico | `CHANGELOG.md` | Registro das versões |

## Convenções

- **Nomes de pastas:** minúsculas, sem acento, palavras separadas por hífen (`lista-de-tarefas`).
- **Um projeto = uma pasta**, sempre com `README.md`.
- **README de cada projeto:** título, descrição, link de demonstração, funcionalidades, tecnologias, como executar.

## Estratégia de versionamento

- Branch `main`: sempre estável — é a que o GitHub Pages publica.
- Novas funcionalidades em branches `feature/<nome>` e integradas por *pull request*.
- Mensagens no padrão Conventional Commits (`feat:`, `fix:`, `docs:`, `style:`, `chore:`).
- Versões marcadas com tags: `v1.0` (versão inicial), `v1.1` (alterações), …

## Colaboração

1. Colaborador faz *fork* ou cria uma branch.
2. Faz commits pequenos e descritivos.
3. Abre *pull request* descrevendo a mudança.
4. Revisão e *merge* na `main`.
