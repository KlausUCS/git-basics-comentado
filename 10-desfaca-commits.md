# 10. Desfaça commits

> Apague enganos e crie um histórico substituto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)

---

## Comandos desta seção (2)

### 1. `git reset [commit]`

```bash
git reset [commit]
```

**O que faz:**

Volta o ponteiro da branch para um commit anterior, mas mantém as alterações dos arquivos.

**Quando usar / observação:**

É útil quando quiser desfazer um commit sem perder o que foi alterado.

---

### 2. `git reset --hard [commit]`

```bash
git reset --hard [commit]
```

**O que faz:**

Volta para um commit anterior e descarta as alterações feitas depois dele.

**Quando usar / observação:**

As alterações que não foram salvas em outro lugar podem ser perdidas.

---

## Checklist deste arquivo

- [x] 1. `git reset [commit]`
- [x] 2. `git reset --hard [commit]`

---

[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)
