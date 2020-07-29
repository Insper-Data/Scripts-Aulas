# Capacitação Git/Github
Nesta capacitação aprenderemos a utilizar a tecnologia Git em conjunto com a plataforma Github para facilitar o ambiente de programação nos grupos.
![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1200px-Git-logo.svg.png)

## Crie uma conta no Github:\
https://github.com/

## Instalando o Git
##### Instale a última versão do Git no seu sistema operacional de escolha:\

* Para macOS recomendo utilizar a opção Bynary installer por ser mais simples
https://git-scm.com/download/mac

* Para Windows utilizar o installer disponível neste link:\
https://git-scm.com/download/win \
Durante a instalação selecionar "Use Git from the Windows Command Prompt".\
\
Obs: Não confunda Git com Github. Git é a tecnologia de gerenciamento de versões desenvolvida por Linus Torvals, Github é uma plataforma que faz uso da tecologia Git para criar um ambiente comum para desenvolvedores. 

## Configurando usuário:
##### Para começar abra o Terminal se você estiver num mac ou o Git Bash se você estiver num windows. 
##### Substitua suas informações pessoais nos campos necessários:
* git config --global user.name "SEU USERNAME"\
* git config --global user.email SEU EMAIL

## Comandos do Bash/Terminal de comando:
* **ls** - (List) - Lista arquivos contidos no diretório presente.\
* **cd** *NOME DO DIRETÓRIO* - (Change directory) - Acessa sub-diretório especificado no diretório presente.

## Comandos necessários do Git
* **git clone** *LINK DO REPOSITÓRIO* - Clona (faz download) do repositório da nuvem para o seu computador.\
\
* **git diff** - Informa quais mudanças foram feitas no código do repositório local.\
\
* **git add** *NOME DO ARQUIVO* - Adiciona mudanças feitas no arquivo à área de pré-processamento. Para adicionar todas as mudanças utilizar "git add -A\
\
* **git status** - Informa quais arquivos foram colocados na área de pré-processamente.\
\
* **git commit -m** **"** *mensagem explicando mudanças feitas* - Registra todas as mudanças contidas na área de pré-processamento no seu computador. É importante ser sempre bastante específico nos comentários.\
\
* **git push** - Atualiza o código armazenado na nuvem com as mudanças realizadas localmente.\
\
* **git pull** - "Puxa" o código da nuvem e atualiza o seu diretório local.\
\
* **git log** - Mostra últimos commits feitos, seus autores, horários, mensagens e código\
\
* **git revert** *CÓDIGO* - Reverte a mudança feita em determinado commit