# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

Remove o arquivo do computador e também avisa ao Git que ele deve ser removido do repositório.

**Quando usar / observação:**

Quando quiser apagar um arquivo que já está sendo controlado pelo Git.

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

Remove o arquivo do controle do Git, mas deixa o arquivo no computador.

**Quando usar / observação:**

Quando não quero mais que um arquivo seja versionado, mas ainda quero mantê-lo na pasta.

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

Renomeia ou move um arquivo e já registra essa mudança no Git.

**Quando usar / observação:**

É melhor usar esse comando do que renomear o arquivo manualmente quando ele já está sendo controlado pelo Git.

---

## Checklist deste arquivo

- [x] 1. `git rm [arquivo]`
- [x] 2. `git rm --cached [arquivo]`
- [x] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
