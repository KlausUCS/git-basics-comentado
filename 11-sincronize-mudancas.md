# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

Busca as novidades do repositório remoto sem alterar minha branch atual.

**Quando usar / observação:**

Para verificar o que mudou no GitHub antes de decidir o que fazer com essas mudanças.

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

Junta as alterações de uma branch remota com a branch em que estou.

**Quando usar / observação:**

Quando quiser trazer as mudanças de outra branch para a minha.

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

Envia meus commits locais para o repositório remoto.

**Quando usar / observação:**

Para mandar minhas alterações para o GitHub.

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

Baixa as alterações do repositório remoto e tenta juntá-las com a minha branch atual.

**Quando usar / observação:**

Para atualizar minha branch com o que já foi enviado para o GitHub.

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
