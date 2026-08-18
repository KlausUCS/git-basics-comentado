# 02. Configure a ferramenta

> Configure informações de usuário para todos os repositórios locais.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)

---

## Comandos desta seção (2)

### 1. `git config --global user.name "[nome]"`

```bash
git config --global user.name "[nome]"
```

**O que faz:**

Define o nome que vai aparecer como autor dos commits.
Quando utilizado como global, a configuração vale para todos os repositórios do computador.

**Quando usar / observação:**

É configurado uma vez e depois o Git utiliza esse nome nos próximos commits.

---

### 2. `git config --global user.email "[endereco-de-email]"`

```bash
git config --global user.email "[endereco-de-email]"
```

**O que faz:**

Define o email associado aos commits realizados.

**Quando usar / observação:**

É configurado uma vez e depois o Git utiliza esse nome nos próximos commits.

---

## Checklist deste arquivo

- [x] 1. `git config --global user.name "[nome]"`
- [x] 2. `git config --global user.email "[endereco-de-email]"`

---

[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)
