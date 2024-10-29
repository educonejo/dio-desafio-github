# Git e GitHub
#### CLI (CommandLine Interface)
##### Linux
- **cd**
- **ls**
- **mkdir**
- **rm -rf**
- **clear**
 
##### Windows
- **cd**
- **dir**
- **mkdir**
- **del**  (somente arquivos)
- **rmdir** (tudo)

### GIT
##### SHA1
- Secure Hash ALgorithms (SHA)
- Algorimo de encriciptação (NSA)
- 40 digitos

```sh
echo "olá mundo" | openssl sha1
```
```sh
openssl sha1 texto.txt
```
#### Sistemas Distribuidos
##### OBJETOS
- BLOBS
- TREES (armazena BLOBS)
- COMMITS (junta tudo, aponta para -> arvore / parente /autor)

```sh
echo 'conteudo' | git hash-object --stdin
echo -e 'blob 9\0conteudo' | openssl sha1
```

- Untracked
- Unmodified
- Modified
- Staged



