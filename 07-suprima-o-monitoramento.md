# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

Define quais arquivos e pastas o Git deve ignorar e não mostrar como alterações.

**Quando usar / observação:**

É útil para ignorar arquivos temporários, logs, pastas de build e arquivos que não precisam ir para o GitHub.

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

Mostra arquivos que estão sendo ignorados pelo Git.

**Quando usar / observação:**

Para conferir se o .gitignore está funcionando como esperado.

---

## Checklist deste arquivo

- [x] 1. Arquivo `.gitignore`
- [x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
