
# Capítulo 3: Gerenciamento de Arquivos e Diretórios

## 3.1 Navegação

Navegar pelo sistema de arquivos é uma habilidade fundamental ao usar o terminal. Os comandos principais para navegação incluem:

- `pwd`: Exibe o diretório atual.
  ```bash
  pwd
  ```

- `cd`: Altera o diretório atual.
  ```bash
  cd /caminho/para/diretorio
  ```

- `ls`: Lista arquivos e diretórios no diretório atual.
  ```bash
  ls
  ```

## 3.2 Manipulação de Arquivos

Manipular arquivos é uma tarefa comum no terminal. Aqui estão alguns comandos essenciais:

- `cp`: Copia arquivos de um local para outro.
  ```bash
  cp arquivo_origem.txt destino/
  ```

- `mv`: Move ou renomeia arquivos.
  ```bash
  mv arquivo_origem.txt destino/
  ```

- `rm`: Remove arquivos.
  ```bash
  rm arquivo.txt
  ```

- `touch`: Cria um novo arquivo vazio.
  ```bash
  touch novo_arquivo.txt
  ```

## 3.3 Manipulação de Diretórios

Manipular diretórios é essencial para organizar o sistema de arquivos. Comandos importantes incluem:

- `mkdir`: Cria um novo diretório.
  ```bash
  mkdir novo_diretorio
  ```

- `rmdir`: Remove um diretório vazio.
  ```bash
  rmdir diretorio_vazio
  ```

- `rm -r`: Remove um diretório e seu conteúdo de forma recursiva.
  ```bash
  rm -r diretorio_com_conteudo
  ```

## 3.4 Permissões de Arquivos e Diretórios

As permissões controlam o acesso a arquivos e diretórios. Comandos para gerenciar permissões incluem:

- `chmod`: Altera as permissões de um arquivo ou diretório.
  ```bash
  chmod 755 arquivo.txt
  ```

- `chown`: Altera o proprietário de um arquivo ou diretório.
  ```bash
  chown usuario:grupo arquivo.txt
  ```

- `chgrp`: Altera o grupo proprietário de um arquivo ou diretório.
  ```bash
  chgrp grupo arquivo.txt
  ```

Permissões comuns:
- `r` (read): Permissão de leitura.
- `w` (write): Permissão de escrita.
- `x` (execute): Permissão de execução.
