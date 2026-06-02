# Dartpedia

# Dartpedia

## Integrantes da Equipe

* Isaac Gonçalves da Silva Lima
* Guilherme Monteiro
* Bianca de Oliveira Almeida
* Giulia Melise

## Sobre o Projeto

O **Dartpedia** é um aplicativo de linha de comando (CLI) desenvolvido em Dart ao longo da disciplina, com o objetivo de praticar conceitos de programação, organização de projetos, criação de comandos personalizados e utilização de Git/GitHub para trabalho colaborativo.

Atualmente, o projeto implementa os comandos básicos desenvolvidos durante o semestre, como exibição de ajuda (`help`), versão do aplicativo (`version`) e a estrutura inicial para pesquisas (`search`).

## Como Executar o Projeto

1. Clone o repositório:

```bash
git clone (https://github.com/Binalmeida/Dartpedia)
```

2. Entre na pasta do projeto:

```bash
cd dartpedia
```

3. Execute o aplicativo:

```bash
dart run
```

## Comandos Disponíveis

### Exibir ajuda

```bash
dart run help
```

ou

```bash
dart run --help
```

### Exibir versão

```bash
dart run version
```

### Pesquisar (estrutura inicial)

```bash
dart run search <termo>
```

Exemplo:

```bash
dart run search dart
```

## Estrutura do Projeto

* `help` → Exibe informações sobre os comandos disponíveis.
* `version` → Mostra a versão atual do aplicativo.
* `search` → Estrutura inicial para realização de pesquisas.
* `command_runner` → Responsável pelo gerenciamento dos comandos e argumentos.

## Controle de Versão

O desenvolvimento do projeto foi realizado utilizando o GitHub, mantendo um histórico de commits que demonstra a evolução da aplicação e a participação individual de cada integrante da equipe.

