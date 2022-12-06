# Deletar último commit sem deletar modificações nos arquivos

> Verificar o status
```bash
git status
```
> Retorna um commit sem desfazer as alterações
```bash
git reset --soft HEAD~1
```
> Adiciona as novas modificações no Stage
```bash
git add .
```
> Salva as alterações
```bash
git commit -m 'alteração'
```
> Envia para o repositório remoto
```bash
git push
```