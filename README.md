<p align="center">
 <img src="https://user-images.githubusercontent.com/22691244/85969179-4b25e480-b99d-11ea-90cf-bf50b805a626.jpg"  width="150"/>
<br />
  <h1 align="center">:brazil: +500 Comandos Linux :brazil:</h1></br>
</p>

## ➤ Tabela de comandos

| Comando | Descrição |
|---------|--------|
|`[qualquer_comando] -help` | *descrição do comando* |
| `man [qualquer_comando`] | *manual do comando* |
| `ls` | *listar arquivos / diretórios* |
| `ls -la` | *listar arquivos / diretórios incluindo ocultos* |
| `cd [diretorio]` | *mudar para o diretório especificado* |
| `cd` | *mudar para o diretório **/home*** |
| `pwd` | *exibe o diretório atual* |
| `mkdir [nome_diretorio]` | *criar um diretório* |
| `rm [nome_arquivo]` | *remover um arquivo* |
| `rm -r [nome_diretorio]` | *remover um diretório* |
| `rm -f [nome_arquivo]` | *forçar remoção de um arquivo* |
| `rm -rf [nome_diretorio]` | *forçar remoção de um diretório* |
| `cp -r [nome_arquivo_1] [nome_arquivo_2]` | *copiar o **arquivo 1** para o **arquivo 2*** |
| `cp -r [nome_diretorio_1] [nome_diretorio_2]` | *copiar o **diretório 1** para o **diretório 2**; cria o **diretório 2** caso não exista.* |
| `mv [nome_arquivo_1] [nome_arquivo_2]` | *renomear / mover **arquivo 1** para o **arquivo 2*** |
| `ln -s [nome_arquivo] [nome_link]` | *criar um link(atalho) simbólico para o arquivo* |
| `touch [nome_arquivo]` | *criar / atualizar o arquivo* |
| `cat > [nome_arquivo]` | *direcionar a entrada padrão para um arquivo* |
| `more [nome_arquivo]` | *exibir o conteúdo de um arquivo* |
| `head [nome_arquivo]` | *exibir as **primeiras** 10 linhas de um arquivo* |
| `tail [nome_arquivo]` | *exibir as **últimas** 10 linhas de um arquivo* |
| `tail -f [nome_arquivo]` | *exibir o conteúdo de um arquivo enquanto ele é atualizado, iniciando com as últimas 10 linhas* |
| `ps` | *exibir processos dos usuários ativos* |
| `top` | *exibir todos os processos* |
| `kill [pid]` | *matar um processo específico pelo ID* |
| `killall [nome_processo]` | *matar todos os processos com o nome especificado* |
| `bg` | *listar trabalhos parados / segundo plano* |
| `fg` | *traz o trabalho mais recente para o primeiro plano* |
| `fg [nome_processo]` | *traz o trabalho para o primeiro plano* |
| `chmod [valores_octal] [nome_arquivo]` | *mudar as permissões de um arquivo* <details><summary>📖 saber mais</summary><br />

## ➤ Tabela

* [➤ Tabela 1](#-installation)

</details> |

## ➤ Exemplos do modo octal

| Valor Octal | Valor Binário rwx | Caracteres | Significado |
|---------|--------|--------|--------|
| 0 | 000 | --- | *nenhuma permissão de acesso* |
| 1 | 001 | --x | *permissão de execução* |
| 2 | 010 | -w- | *permissão de gravação* |
| 3 | 011 | -wx | *permissão de gravação e execução* |
| 4 | 100 | r-- | *permissão de leitura* |
| 5 | 101 | r-x | *permissão de leitura e execução* |
| 6 | 110 | rw- | *permissão de leitura e gravaço* |
| 7 | 111 | rwx | *permissão de leitura, gravação e execução* |

## ➤ Referências

- [chmod | Guia Linux](https://guialinux.uniriotec.br/chmod/)
