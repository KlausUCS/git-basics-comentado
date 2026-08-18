# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

Mostra como estão os arquivos do projeto e quais foram alterados.
Também mostra quais arquivos estão preparados para commit.

**Quando usar / observação:**

Antes de fazer um commit para conferir o que mudou.

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Mostra as alterações que foram feitas nos arquivos, mas ainda não foram adicionadas ao commit.

**Quando usar / observação:**

Para conferir exatamente o que foi alterado antes de usar git add.

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

Coloca o arquivo na área de preparação para o próximo commit.

**Quando usar / observação:**

Usar antes de realizar um commit.
Posso escolher exatamente quais arquivos quero colocar no próximo commit.

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

Mostra as alterações que já foram adicionadas para o próximo commit.

**Quando usar / observação:**

Quando quiser conferir o que realmente vai entrar no commit.

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

Tira o arquivo da área de preparação sem apagar as alterações feitas nele.

**Quando usar / observação:**

Quando colocar um arquivo no git add por engano.

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Salva as alterações preparadas como um novo commit no histórico do Git.

**Quando usar / observação:**

Quando quiser salvar alterações no código.
A mensagem deve explicar de forma curta o que foi alterado.

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
