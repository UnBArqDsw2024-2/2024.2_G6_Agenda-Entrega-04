# Representação Arquitetural

## Introdução

A Representação Arquitetural descreve como a arquitetura do sistema é organizada e representada, utilizando diferentes visões para capturar os aspectos significativos do sistema. Para o projeto da Agenda Genérica, a arquitetura é representada através de visões como a Visão de Casos de Uso, Visão Lógica, Visão de Processos, Visão de Implementação e Visão de Implantação.

### **Principais Conceitos**

- **Visão de Casos de Uso**: Descreve como os principais cenários de uso do sistema são suportados pela arquitetura.
- **Visão Lógica**: Mostra a estrutura do sistema em termos de componentes e suas interações.
- **Visão de Processos**: Descreve a divisão do sistema em processos e threads.Visão de Processos: Descreve a divisão do sistema em processos e threads.
- **Visão de Implementação**: Mostra como o sistema é organizado em módulos e pacotes.
- **Visão de Implantação**: Descreve como o sistema será implantado em hardware.

## Resultados

### Visão de Casos de Uso

Com base nos diagramas de casos de uso e cenários desenvolvidos na segunda entrega, os principais casos de uso são:

- **Agendar Compromisso**: O usuário pode agendar um novo compromisso na agenda.
- **Visualizar Compromissos**: O usuário pode visualizar os compromissos agendados.
- **Editar Compromisso**: O usuário pode editar um compromisso existente.
- **Excluir Compromisso**: O usuário pode excluir um compromisso da agenda.

Esses casos de uso são suportados por componentes como a **Camada de Apresentação**, **Camada de Negócio** e **Camada de Dados**.

### Visão Lógica

A **Visão Lógica** é representada pelo **Diagrama de Classes** e **Diagrama de Componentes** desenvolvidos na segunda entrega. A arquitetura da Agenda Genérica é dividida em três camadas principais:

- **Camada de Apresentação**: Responsável pela interface com o usuário (UI).
- **Camada de Negócio**: Contém as regras de negócio e a lógica de aplicação.
- **Camada de Dados**: Responsável pela persistência dos dados, como compromissos e usuários.

### Visão de Processos

Os principais processos do sistema incluem:

- **Processo de Interface do Usuário**: Responsável por capturar as entradas do usuário e exibir as informações.
- **Processo de Negócio**: Responsável por executar as regras de negócio, como validação de compromissos.
- **Processo de Persistência**: Responsável por salvar e recuperar dados do banco de dados.

### Visão de Implementação

A implementação da Agenda Genérica é organizada em pacotes como:

- **apresentacao**: Contém as classes relacionadas à interface do usuário.
- **negocio**: Contém as classes de regras de negócio.
- **dados**: Contém as classes de acesso a dados.

### Visão de Implantação

A implantação pode ser feita em um servidor web, com o front-end rodando no navegador do usuário e o back-end rodando em um servidor de aplicação.


## Breve explicação


## Referências

> <a>1.</a> <br>
> <a>2.</a>  <br>


## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 31/01/2025  | Versão inicial do artefato. | [Bianca](https://github.com/BiancaPatrocinio7) | 20/11/2024 |  |
