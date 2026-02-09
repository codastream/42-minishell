# MiniShell

_This is a project from 42 common core developed with [Djo-msv](https://github.com/Djo-msv)_ 

## Developed skills

| Skill | Wiki Link |
| :--- | :--- |
| [![Bash](https://img.shields.io/badge/Gnu_Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://github.com/codastream/42-minishell/wiki/Bash) | [Bash](https://github.com/codastream/42-minishell/wiki/Bash) |
| [![Makefile](https://img.shields.io/badge/GNU_Makefile-013243?style=for-the-badge&logo=gnu-make&logoColor=white)](https://github.com/codastream/42-minishell/wiki/Makefile) | [Makefile](https://github.com/codastream/42-minishell/wiki/Makefile) |
| [![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)](https://github.com/codastream/42-minishell/wiki/C_language) | [C](https://github.com/codastream/42-minishell/wiki/C_language) |
| [![IPC](https://img.shields.io/badge/IPC_Pipes-C0392B?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/codastream/42-minishell/wiki/IPC) | [Inter-process Communication](https://github.com/codastream/42-minishell/wiki/IPC) |
| [![Tokenization](https://img.shields.io/badge/Tokenization-5C2D91?style=for-the-badge&logo=target&logoColor=white)](https://github.com/codastream/42-minishell/wiki/Tokenization) | [Lexical Analysis / Tokenization](https://github.com/codastream/42-minishell/wiki/Tokenization) |

## Requirements

This projects aims at replicating a very basic shell with :
- basic interactive display with history
- interpretation and execution of commands (with name or absolute path)
- interpretation of variables
- interpretation of wildcard `*` for the current directory
- handling of single and double quotes
- handling of redirections and heredoc (`<`, `<<`, `>>`, `>`)
- handling of pipes
- handling of execution status
- handling of EOF and signals SIGINT, SIGQUIT

A few builtin commands with no options were also implemented :
- `cd`
- `pwd`
- `export`
- `unset`
- `env`
`echo` with option n was also implemeted.

## Program Flow

![overview](minishell.png)

## Setup

```bash
make
./minishell
```
