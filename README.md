# Cadastro de Aluno

Aplicativo Android para cadastro, consulta e gerenciamento de alunos utilizando Java/Kotlin, padrão MVC e persistência local.

## Funcionalidades

- Cadastro de alunos com RA e nome
- Validação de campos obrigatórios
- Verificação de duplicidade de RA
- Listagem de todos os alunos cadastrados
- Persistência local dos dados

## Tecnologias Utilizadas

- **Linguagens:** Java, Kotlin
- **Framework:** Android SDK
- **Persistência:** SQLite (via DAO)
- **Build:** Gradle

## Estrutura do Projeto

src/ └── main/ ├── java/ │ └── com/example/cadastroaluno/ │ ├── controller/ # Lógica de controle (ex: AlunoController) │ ├── dao/ # Acesso a dados (ex: AlunoDao) │ └── model/ # Modelos de dados (ex: Aluno) └── res/ # Recursos (layouts, strings, etc)

## Instalação e Execução

1. Clone o repositório:
    ```bash
    git clone https://github.com/paulohpssantos/CadastroAlunoApp.git

2. Abra o projeto no Android Studio.
3. Conecte um dispositivo ou inicie um emulador.
4. Clique em **Run** para compilar e executar o app.

## Como Usar

- Preencha o RA e o nome do aluno e clique em **Salvar**.
- O app valida os campos e impede cadastros duplicados.
- Consulte a lista de alunos cadastrados na tela principal.

**Autor:** Paulo Henrique P. dos Santos  