# Carta de Fundação do Escritório de Dados e IA

Documentação corporativa gerada a partir do Corporate Docs Factory para formalizar a missão, estrutura, papéis, modelo operacional e matriz RACI do Escritório de Dados e Inteligência Artificial.

## Execução local

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

Acesse `http://localhost:8000`.

## Build

```bash
mkdocs build
```

## Deploy

O deploy está configurado via GitHub Actions em `.github/workflows/deploy.yml`.

Ao publicar na branch `main`, o workflow instala MkDocs e executa:

```bash
mkdocs gh-deploy --force
```

O site é publicado no branch `gh-pages`.
