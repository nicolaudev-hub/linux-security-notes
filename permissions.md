# Principais Comandos Linux

```bash
ls --> Lista o conteúdo do diretório
ls -l --> Lista os arquivos por linha 
ls -r --> inverte a ordem de seleção 
ls -a --> Lista os arquivos ocultos 
ls|more --> Lista pausadamente os arquivos
ls *.extensão_do_arquivo --> Lista somente arquivos com uma extensão
cd nome_da_pasta --> abre uma pasta ou diretorio
cd .. --> volta um diretório 
cd / --> volta ao diretório padrão (/)
clear --> limpa terminal
pwd --> mostra caminho completo do diretório
mkdir nome_da_pasta --> cria pasta (diretório)
rmdir nome_da_pasta --> apaga uma pasta (diretório). OBS: apaga somente diretórios vazios
cat nome_do_arquivo --> visualiza o arquivo

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
