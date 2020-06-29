<p align="center">
 <img src="https://user-images.githubusercontent.com/22691244/85969179-4b25e480-b99d-11ea-90cf-bf50b805a626.jpg"  width="150"/>
</p>
<h1 align="center">:brazil: +500 Comandos Linux :brazil:</h1>
<p align="center">
 <a href="https://github.com/carloskotacho/comandos-linux/blob/master/LICENSE">
  <img src="https://img.shields.io/github/license/carloskotacho/comandos-linux?color=%23fedb3d&label=licen%C3%A7a&style=flat-square" alt="Github License">
 </a>
 <a href="https://github.com/carloskotacho/comandos-linux/graphs/contributors">
  <img src="https://img.shields.io/github/stars/carloskotacho/comandos-linux?color=%23fedb3d&label=colaboradores&style=flat-square" alt="Github Contributors">
 </a>
 <a href="https://github.com/carloskotacho/comandos-linux/stargazers">
  <img src="https://img.shields.io/github/stars/carloskotacho/comandos-linux?color=%23fedb3d&style=flat-square" alt="Github Stars">
 </a>
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
| `chmod [valores_octal] [nome_arquivo]` | *mudar as permissões de um arquivo [➤ saber mais](#-exemplos-do-modo-octal)* |
| `ssh [nome_usuário]@host` | *conectar ao host como usuário* |
| `ssh -p [numero_porta] [nome_usuario]@host` | *conectar ao host na porta especificada* |
| `ssh-copy-id [nome_usuario@host]` | *adicionar a sua chave para o host e usuário daquele host; serve para ativar logins sem senha com uso de chaves* |
| `grep [sequencia_arquivos]` | *pesquisar pela sequência nos arquivos* |
| `grep -r [sequencia_diretorios]` | *pesquisar recursivamente pela sequência no diretório* |
| `[nome_comando] | grep [sequencia]` | *pesquisar pela sequência na saída do comando* |
| `locate [nome_arquivo]` | *encontrar instâncias de um arquivo* |
| `date` | *exibir hora / data atual* |
| `cal` | *exibir calendario do mês atual* |
| `uptime` | *exibir tempo de atividade do sistema* |
| `w` | *exibir quem está online* |
| `whoami` | *exibir como quem você está logado* |
| `finger` | *exibir informações do usuário* |
| `uname -a` | *exibir informações do kernel* |
| `cat /porc/cpuinfo` | *exibir informações CPU* |
| `cat /proc/meminfo` | *exibir informações da memória* |
| `df` | *exibir uso de disco* |
| `du` | *exibir uso do espaço em um diretório* |
| `free` | *exibir uso da memória e swap* |
| `whereis [nome_programa]` | *exibir localização do aplicativo* |
| `which [nome_programa]` | *exibe que a aplicação irá rodar por omissão* |
| `tar cf [nome_pacote.tar] [nome_arquivos]` | *criar pacote TAR com os arquivos especificados* |
| `tar xf [nome_pacote.tar]` | *extrair arquivos do pacote* |
| `tar czf [nome_pacote.tar.gz] [nome_arquivos]` | *criar um pacote TAR com compressão GZip* |
| `tar xzf [nome_pacote.tar.gz]` | *extrair um pacote TAR com compressão GZip* |
| `tar cjf [nome_pacote.tar.bz2]` | *criar um pacote TAR com compressão BZip2* |
| `tar xjf [nome_pacote.tar.bz2]` | *extrair um pacote TAR com compressão BZip2* |
| `gzip [nome_arquivo]` | *compactar um arquivo e o renomeia para nome_arquivo.gz* |
| `gzip -d [nome_arquivo.gz]` | *descompactar nome_arquivo.gz para um arquivo* |
| `ping [site_ou_numip]` | *envia um pacote ICMP para o host e exibe o resultado* |
| `whois [site_ou_numip]` | *retornar informações sobre o domínio* |
| `dig [site_ou_numip]` | *retornar informações de DNS para o domínio* |

## ➤ Exemplos do modo octal

| Valor Octal | Valor Binário rwx | Caracteres | Significado |
|---------|--------|--------|--------|
| 0 | 000 | --- | *nenhuma permissão de acesso* |
| 1 | 001 | --x | *permissão de execução* |
| 2 | 010 | -w- | *permissão de gravação* |
| 3 | 011 | -wx | *permissão de gravação e execução* |
| 4 | 100 | r-- | *permissão de leitura* |
| 5 | 101 | r-x | *permissão de leitura e execução* |
| 6 | 110 | rw- | *permissão de leitura e gravação* |
| 7 | 111 | rwx | *permissão de leitura, gravação e execução* |

## ➤ Referências

- [chmod | Guia Linux](https://guialinux.uniriotec.br/chmod/)
- [Guia comandos do Linux](https://www.linuxpro.com.br/dl/guia_500_comandos_Linux.pdf)

## ➤ License
	
Licença [MIT](https://github.com/carloskotacho/comandos-linux/blob/master/LICENSE).
