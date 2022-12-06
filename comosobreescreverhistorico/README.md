# Como sobreescrever um histórico no GitHub

> Ação destrutiva

> Forçar histórico local no remoto
```bash
git push -f <remote> <branch>
```

> Pode ser restaurado com `git reset --hard <codigoCommit>` e ao realizar o comando acima será imputado o histórico local para o remoto.