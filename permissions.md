# Permissões Linux

## Visualizar permissões

```bash
ls --> Lista o conteúdo do diretório
ls -l --> Lista os arquivos por linha 
ls -r --> inverte a ordem de seleção 
ls -a --> Lista os arquivos ocultos 
ls|more --> Lista pausadamente os arquivos
ls *.extensão_do_arquivo --> Lista somente arquivos com uma extensão
```

## Alterar permissões

```bash
chmod 755 arquivo
```

## Alterar proprietário

```bash
chown usuario:grupo arquivo
```

## Valores

| Valor | Permissão |
|---------|---------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |
