# git rm --cached

### 📘 Descrição
Remove arquivos do controle do Git sem deletá-los do seu diretório local, útil para parar de rastrear arquivos que já foram commitados.

---

### 🧩 Exemplos práticos

#### Remover um arquivo específico do versionamento:
```bash
git rm --cached caminho/do/arquivo.ext
git commit -m "Remove arquivo do versionamento"
```

#### Remover todos os arquivos de uma pasta do versionamento:
```bash
git rm --cached -r pasta/
git commit -m "Remove pasta do versionamento"
```

⚠️ Observações

O arquivo permanece no seu computador, apenas o Git deixa de rastreá-lo.
Combine com .gitignore para que o Git nunca mais rastreie o arquivo.
Se o arquivo já foi enviado ao repositório remoto, faça git push para atualizar o repositório.
