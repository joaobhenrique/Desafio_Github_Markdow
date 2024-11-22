# Desafio_Github_Markdown


# Treinamento GitHub e Comandos Git

Este repositório foi criado para fins de treinamento e aprendizado sobre o uso de GitHub e comandos Git. Ao longo deste projeto, serão abordados os principais conceitos do Git e como utilizá-los eficientemente no GitHub para controle de versão e colaboração.

## Objetivo

O objetivo deste projeto é familiarizar-se com as ferramentas essenciais do Git e GitHub, incluindo:

- Criação de repositórios.
- Clonagem de repositórios.
- Criação de branches e gerenciamento de alterações.
- Comandos básicos do Git para controle de versão.
- Colaboração e criação de Pull Requests.

## Comandos Git Utilizados no Projeto

Aqui estão alguns dos comandos Git fundamentais que você aprenderá e utilizará durante este treinamento:

### 1. **Inicializando um Repositório Git**
Para iniciar um novo repositório Git em seu diretório local:

```bash
git init
```

### 2. **Clonando um Repositório**
Para clonar um repositório do GitHub para seu computador:

```bash
git clone <URL do repositório>
```

Exemplo:

```bash
git clone https://github.com/usuario/nome-do-repositorio.git
```

### 3. **Verificando o Status**
Para ver o status atual do seu repositório local, incluindo arquivos modificados ou não rastreados:

```bash
git status
```

### 4. **Adicionando Arquivos ao Staging**
Para adicionar arquivos para serem rastreados pelo Git:

```bash
git add <nome-do-arquivo>
```

Ou para adicionar todos os arquivos modificados:

```bash
git add .
```

### 5. **Commitando Alterações**
Após adicionar os arquivos, é necessário fazer um commit para salvar as mudanças no histórico do Git:

```bash
git commit -m "Mensagem do commit"
```

### 6. **Visualizando o Histórico de Commits**
Para ver o histórico de commits realizados:

```bash
git log
```

### 7. **Criando uma Nova Branch**
Para criar uma nova branch e alternar para ela:

```bash
git checkout -b nome-da-branch
```

### 8. **Mudando de Branch**
Para alternar para uma branch existente:

```bash
git checkout nome-da-branch
```

### 9. **Fazendo Pull e Push para o GitHub**
Após realizar commits no repositório local, envie as alterações para o repositório remoto no GitHub com os seguintes comandos:

```bash
git push origin nome-da-branch
```

E para baixar as últimas alterações do repositório remoto:

```bash
git pull origin nome-da-branch
```

### 10. **Criando um Pull Request**
Após fazer alterações em uma branch e empurrá-las para o GitHub, é possível criar um Pull Request (PR) para integrar as mudanças na branch principal (geralmente `main` ou `master`).

### 11. **Resolvendo Conflitos de Merge**
Ao combinar branches, podem ocorrer conflitos. Você deverá resolvê-los manualmente nos arquivos indicados pelo Git.

