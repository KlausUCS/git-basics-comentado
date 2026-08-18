# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

Guarda temporariamente as alterações que ainda não quero commitar.
Deixa o projeto limpo para eu poder trocar de branch ou fazer outra coisa.

**Quando usar / observação:**

Quando começar uma alteração, mas precisa parar e trabalhar em outra coisa.

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

Recupera as alterações que foram guardadas no stash.
Depois de recuperar, remove essa alteração da lista de stash.

**Quando usar / observação:**

Quando quiser continuar o trabalho que tinha deixado de lado.

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

Mostra todas as alterações que estão guardadas no stash.

**Quando usar / observação:**

Quando existem vários trabalhos guardados e quiser saber o que existe lá.

---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

Apaga uma alteração que está guardada no stash.

**Quando usar / observação:**

Quando não precisar mais daquela alteração guardada.

---

## Checklist deste arquivo

- [x] 1. `git stash`
- [x] 2. `git stash pop`
- [x] 3. `git stash list`
- [x] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
