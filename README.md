# Guia de Comandos do Git

Este é um guia rápido dos principais comandos do Git para auxiliá-lo em seu fluxo de trabalho de desenvolvimento.

## Slides complementares 



## Configuração Inicial

Antes de começar a utilizar o Git, é necessário fazer uma configuração inicial com suas informações de usuário.

```shell
$ git config --global user.name "Seu Nome"
$ git config --global user.email "seuemail@example.com"
```

## Comandos Básicos

Aqui estão alguns dos comandos mais utilizados no Git:

### git init

Inicializa um repositório Git em um diretório vazio.

```shell
$ git init
```

### git clone

Cria uma cópia local de um repositório remoto.

```shell
$ git clone <URL_do_repositório_remoto>
```

### git add

Adiciona arquivos ao índice para serem commitados.

```shell
$ git add <nome_do_arquivo>
```

### git commit

Registra as mudanças realizadas no repositório.

```shell
$ git commit -m "Aqui vai a mensagem do seu commit"
```

### git status

Mostra o estado atual do repositório, indicando arquivos modificados, adicionados ou excluídos.

```shell
$ git status
```

### git push

Envia as alterações locais para um repositório remoto.

```shell
$ git push origin <nome_da_branch>
```

### git pull

Baixa as alterações do repositório remoto para o repositório local.

```shell
$ git pull origin <nome_da_branch>
```

### git branch

Cria, lista ou exclui branches (ramificações).

```shell
$ git branch
$ git branch <nome_da_branch>
$ git branch -d <nome_da_branch>
```

### git checkout

Muda para uma branch específica.

```shell
$ git checkout <nome_da_branch>
$ git checkout -- <nome_do_arquivo>
```
### git log

Mostra o histórico de commits do repositório.

```shell
$ git log
```

## Considerações Finais

Este é apenas um guia básico dos principais comandos do Git. Existem muitos outros recursos e comandos disponíveis que podem aprimorar seu fluxo de trabalho.

 informações, consulte a documentação oficial do Git.

