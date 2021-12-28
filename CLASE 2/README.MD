
## GIT LOG ##

```sh
git log
```

### MUESTRA LOS LOG EN UNA LINEA

```sh
git log --oneline
```

### PARA FILTRAR POR FECHA

```sh
git log --since="AAAA-MM-DD"
```

```sh
git log --after o before="AAAA-MM-DD"
```

### PARA VER LOS ULTIMOS

```sh
git log -x # DONDE X ES EL NUMERO DE LOS COMMIT QUE QUEREMOS VER
```

```sh
git log --oneline --decorate --all --graph
```