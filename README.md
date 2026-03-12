# Gerenciador de Tarefas

Sistema web simples para gerenciamento de tarefas desenvolvido com **Spring Boot** e **Thymeleaf**.
A aplicação permite criar, visualizar, editar, excluir e alterar o status de tarefas, além de filtrar tarefas por status.

## Funcionalidades

* Criar nova tarefa
* Listar todas as tarefas
* Editar tarefas existentes
* Excluir tarefas
* Alternar status da tarefa (pendente / concluída)
* Filtrar tarefas:

  * Todas
  * Pendentes
  * Concluídas
* Contador de tarefas (total, pendentes e concluídas)

## Tecnologias utilizadas

* Java
* Spring Boot
* Thymeleaf
* HTML / CSS
* Maven

## Estrutura do Projeto

O projeto segue o padrão **MVC (Model - View - Controller)**:

* **Model**: representa os dados da aplicação (Tarefa)
* **Repository**: responsável por armazenar e recuperar as tarefas
* **Service**: contém a lógica de negócio
* **Controller**: recebe as requisições HTTP e controla o fluxo da aplicação
* **View**: interface web desenvolvida com Thymeleaf

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

### 2. Abrir o projeto na IDE

Abra o projeto utilizando uma IDE Java, como:

* IntelliJ IDEA
* Eclipse
* VS Code

### 3. Executar a aplicação

Localize a classe principal do Spring Boot (geralmente `TarefasApplication`) e execute a aplicação.

### 4. Acessar no navegador

Após iniciar o servidor, acesse:

```
http://localhost:8080/tarefas
```

## Filtros de Tarefas

A aplicação permite filtrar tarefas através da URL:

* Todas as tarefas

```
/tarefas
```

* Apenas tarefas pendentes

```
/tarefas?filtro=pendentes
```

* Apenas tarefas concluídas

```
/tarefas?filtro=concluidas
```

## Autor

Willian Quincozes
Engenharia de Software
