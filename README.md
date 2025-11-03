# 💰 Expense Tracker

Aplicação desktop em JavaFX para controle financeiro pessoal, permitindo registrar, visualizar, atualizar e excluir despesas em um banco de dados local.

<img src="documentacao/Captura.png" height="400" alt="img aplicação em execução"/>

---

## 🚀 Funcionalidades (Implementadas)

- Cadastro de despesas com descrição e valor

- Listagem completa de gastos

- Edição e exclusão de registros

- Cálculo e exibição do total de despesas

- Armazenamento local com banco de dados SQLite

---

## 🛠️ Tecnologias Utilizadas

- Java 21

- JavaFX

- logback — Ferramenta de registro (logging) em Java, utilizada para gerar logs de maneira flexível e eficiente.

- slf4j — (Simple Logging Facade for Java) API de abstração de logging que permite o uso intercambiável de diferentes frameworks.

- sqlite-jdbc — Driver JDBC que permite que aplicativos Java se conectem a bancos de dados SQLite.

---

## 🗄️ Banco de Dados Utilizado

SQLite — Sistema de gerenciamento de banco de dados relacional leve, embutido e autossuficiente, ideal para aplicações locais sem necessidade de servidor externo.

---

## ⚙️ Como Executar o Projeto

- Crie um novo projeto Java na sua IDE preferida.

- Substitua a pasta src pela deste repositório.

- Adicione as bibliotecas necessárias ao classpath: logback, slf4j, sqlite-jdbc.

- Compile e execute o projeto.

- Caso utilize outro banco de dados, modifique a classe DB conforme necessário.

