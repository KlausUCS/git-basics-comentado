# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**
Mostra o histórico de commits do projeto.

**Quando usar / observação:**

Para ver o que foi feito e quem fez cada commit.

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

Mostra o histórico de alterações de um arquivo específico.

**Quando usar / observação:**

O --follow também consegue acompanhar o arquivo quando ele foi renomeado.

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

Mostra as diferenças entre duas branches.

**Quando usar / observação:**

Uso para comparar o que mudou entre duas linhas de trabalho antes de fazer um merge.

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

Mostra os detalhes de um commit específico e as alterações feitas nele.

**Quando usar / observação:**

Quando quiser saber exatamente o que foi alterado em determinado commit.
---

## Checklist deste arquivo

- [x] 1. `git log`
- [x] 2. `git log --follow [arquivo]`
- [x] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [x] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
