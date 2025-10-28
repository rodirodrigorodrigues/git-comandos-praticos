# git commit --amend

### 📘 Descrição
Permite **modificar o último commit** sem criar um novo, útil para corrigir mensagens ou adicionar arquivos esquecidos.

---

### 🧩 Exemplos práticos

#### Corrigir a mensagem do último commit:
```bash
git commit --amend -m "Nova mensagem corrigida"

git add arquivo_esquecido.js
git commit --amend
```

⚠️ Observações

Use somente antes do git push.
Após o push, o comando altera o histórico e exige git push --force (evite em repositórios compartilhados).
