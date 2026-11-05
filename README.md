[README_estilizado.md](https://github.com/user-attachments/files/34444982/README_estilizado.md)
<div align="center">

# 💻 Portfolio em C

**Projetos e programas desenvolvidos em linguagem C durante a
faculdade.**

![Linguagem](https://img.shields.io/badge/Linguagem-C-00599C?style=for-the-badge&logo=c)
![Compilador](https://img.shields.io/badge/Compilador-GCC-2C8EBB?style=for-the-badge&logo=gnu)
![Plataformas](https://img.shields.io/badge/Plataformas-Windows%20%7C%20Linux%20%7C%20macOS-555?style=for-the-badge)

</div>

------------------------------------------------------------------------

## 📌 Sobre o repositório

Este repositório reúne programas e projetos desenvolvidos em **C**
durante o curso de faculdade, colocando em prática conceitos
fundamentais da linguagem por meio de aplicações simples e interativas.

## 📂 Projetos

### 01 · Validador de CPF

📄 Arquivo: `cpf.c`

Programa que verifica se um número de CPF brasileiro é válido.

**Funcionalidades** - Extrai somente os números digitados, aceitando CPF
com ou sem formatação. - Verifica se o CPF possui 11 dígitos. -
Identifica CPFs inválidos formados pelo mesmo dígito repetido. - Calcula
e confere os dois dígitos verificadores. - Solicita confirmação antes de
encerrar.

**Como executar**

``` bash
gcc cpf.c -o cpf
./cpf
```

**Formatos aceitos** - Com formatação: `123.456.789-00` - Sem
formatação: `12345678900`

------------------------------------------------------------------------

### 02 · Jogo de Adivinhação

📄 Arquivo: `adivinhacao.c`

Jogo interativo no qual o computador escolhe um número aleatório e o
jogador tenta descobri-lo.

**Funcionalidades** - Gera um número aleatório. - Permite que o jogador
tente adivinhar o número. - Fornece dicas indicando se o número
escolhido é maior ou menor. - Informa a quantidade de tentativas
realizadas. - Oferece a opção de jogar novamente.

**Como executar**

``` bash
gcc adivinhacao.c -o adivinhacao
./adivinhacao
```

Siga as instruções exibidas na tela para jogar!

------------------------------------------------------------------------

### 03 · Sistema de Cadastro

📄 Arquivo: `cadastro.c`

Programa para cadastrar e listar pessoas, mantendo os dados armazenados
em memória durante a execução.

**Funcionalidades** - Cadastra código, nome, idade, telefone e e-mail. -
Valida o código e a idade informados. - Permite cadastrar até 100
pessoas por execução. - Gera um relatório geral ao final dos cadastros.

**Como executar**

``` bash
gcc cadastro.c -o cadastro
./cadastro
```

------------------------------------------------------------------------

## 🛠️ Requisitos

Para compilar e executar os projetos, você precisa de:

- **Compilador:** GCC ou qualquer compilador compatível com a linguagem
  C.
- **Sistema operacional:** Windows, Linux ou macOS.

### Instalação do GCC

| Sistema               | Instrução                                      |
|-----------------------|------------------------------------------------|
| Windows               | Instale o [MinGW](https://www.mingw-w64.org/). |
| Linux (Debian/Ubuntu) | Execute `sudo apt-get install gcc`.            |
| macOS                 | Execute `xcode-select --install`.              |

------------------------------------------------------------------------

## 🗂️ Estrutura do projeto

``` text
portfolio-c/
├── cpf.c                    # Validador de CPF
├── adivinhacao.c            # Jogo de Adivinhação
├── cadastro.c               # Sistema de Cadastro
├── README.md                # Documentação do repositório
└── .vscode/                 # Configurações do VS Code
```

------------------------------------------------------------------------

## ⚙️ Como compilar

Você pode compilar os programas pelo terminal ou utilizar o Visual
Studio Code.

### Opção 1 — Pelo terminal

Execute os comandos abaixo na pasta do projeto:

``` bash
gcc cpf.c -o cpf
gcc adivinhacao.c -o adivinhacao
gcc cadastro.c -o cadastro
```

### Opção 2 — Pelo Visual Studio Code

1.  Abra o arquivo `.c` desejado.
2.  Pressione `Ctrl+Shift+B` ou utilize a tarefa de compilação
    configurada.

> Para essa opção, utilize o VS Code com a extensão **C/C++**.

------------------------------------------------------------------------

## 🧠 Aprendizados

Os projetos permitem praticar conceitos fundamentais da linguagem C:

- Entrada e saída de dados (`scanf`, `printf`).
- Estruturas de controle (`if`, `while`, `for`).
- Arrays e strings.
- Funções.
- Validação de dados.
- Geração de números aleatórios.

------------------------------------------------------------------------

## 👤 Autor

**Nicollas Trovão**

- ✉️ E-mail: nictrova200o@gmail.com
- 🐙 GitHub: [Nicollas-Trovao](https://github.com/Nicollas-Trovao)

------------------------------------------------------------------------

## 📄 Licença

Este projeto possui finalidade **educacional** e é de **código aberto**.
Sinta-se à vontade para utilizar, modificar e distribuir seu conteúdo.

------------------------------------------------------------------------

## 🤝 Contribuições

Sugestões de melhorias são bem-vindas! Para contribuir, abra uma *issue*
ou envie um *pull request*.

------------------------------------------------------------------------

<div align="center">

**Última atualização:** 24/08/2026

</div>
