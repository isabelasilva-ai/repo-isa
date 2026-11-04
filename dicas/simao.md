# git blame

Mostra, linha a linha, quem foi o último a alterar cada linha de um ficheiro, em que commit e quando. Serve para perceber de onde veio uma alteração e a quem perguntar sobre ela.

## Exemplo

```
git blame DreamTeam-Simao.txt
```

Cada linha aparece com o hash do commit, o autor, a data e o conteúdo:

```
16e0220a (simaomonteiro18 2026-11-04 14:02) Capitão: Humberto Coelho
```

Para ver só um intervalo de linhas:

```
git blame -L 3,5 DreamTeam-Simao.txt
```

No VS Code, a mesma informação aparece na barra de estado quando pões o cursor numa linha, e na Timeline do ficheiro.