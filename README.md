# Minishell

## Descrição
O **Minishell** é um projeto colaborativo desenvolvido como parte do programa da 42. O objetivo é criar uma shell mínima que implemente funcionalidades básicas de um terminal, como execução de comandos, redirecionamento de entrada/saída e suporte a pipes.

## Instalação

Certifique-se de que sua máquina possui a biblioteca `readline` instalada antes de compilar o projeto.

### Passos para Instalar:

#### Ubuntu/Debian
```bash
sudo apt update
sudo apt install libreadline-dev
```

#### Fedora
```bash
sudo dnf install readline-devel
```

#### Arch Linux
```bash
sudo pacman -S readline
```

### Compilação
Após instalar as dependências, use o `Makefile` para compilar o projeto:
```bash
make
```

## Uso
Após a compilação, execute o Minishell com:
```bash
./minishell
```

## Funcionalidades
- (60%) ✅ Execução de comandos simples (ex.: `ls`, `echo`, etc.).
- 🚧 Redirecionamento de entrada/saída (`>`, `<`, `>>`).
- 🚧 Suporte a pipelines (`|`).
- 🚧 Variáveis de ambiente básicas (`export`, `unset`, etc.).
- 🚧 Histórico de comandos (usando `readline`).










