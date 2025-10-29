# cadastro-escolar-
# 🎓 Sistema de Gestão Escolar — Banco de Dados

## 📘 Descrição do Projeto
O **Sistema de Gestão Escolar** tem como objetivo facilitar o controle e a organização de informações de **alunos, cursos e turmas** em uma instituição de ensino.  
O projeto foi desenvolvido como parte das atividades práticas de **Banco de Dados**, envolvendo **modelagem conceitual, lógica e scripts SQL (CREATE, INSERT e SELECT)**.

---

## 🧩 Problema
As escolas frequentemente enfrentam dificuldades para organizar e atualizar as informações dos alunos, cursos e turmas de forma integrada.  
A ausência de um sistema centralizado dificulta o controle de matrículas e a visualização das relações entre alunos e cursos.

---

## 🎯 Objetivo
Desenvolver um sistema de banco de dados que:
- Centralize as informações da escola;
- Permita gerenciar alunos, cursos e turmas de forma eficiente;
- Garanta integridade e consistência nas relações entre os dados.

---

## ⚙️ Funcionalidades Principais
1. Cadastro e listagem de alunos (dados pessoais e do responsável);  
2. Registro de cursos e turmas (nome, turno e ano letivo);  
3. Associação de alunos aos cursos e turmas.  

---

## 🧠 Modelagem do Banco de Dados

### 🧾 Entidades Principais
- **Aluno:** armazena os dados pessoais e do responsável.  
- **Curso:** representa os cursos disponíveis na instituição.  
- **Turma:** identifica as turmas com turno e ano letivo.  
- **Cursa:** relaciona alunos aos cursos.  
- **Esta:** relaciona alunos às turmas.

### 🧩 Diagrama Entidade-Relacionamento (DER)
O DER foi desenvolvido no https://app.brmodeloweb.com/ e está disponível na pasta `/documentacao`.

**Arquivo:** `documentacao/DER_final.png`


## 🗂️ Estrutura do Projeto
---

## 💾 Scripts SQL

### 📄 01_create_tables.sql
Contém a criação das tabelas:
- `Aluno`
- `Curso`
- `Turma`
- `Cursa`
- `Esta`

Com suas **chaves primárias (PK)** e **estrangeiras (FK)** devidamente definidas.

### 📄 02_insert_data.sql
Contém a **inserção de dados de exemplo** (alunos, cursos e turmas) e suas associações.

### 📄 03_select_queries.sql
Inclui **consultas SQL (SELECT)** para buscar:
- Todos os alunos;  
- Alunos de um curso específico;  
- Alunos por turma;  
- Alunos com curso e turma correspondentes.

---

## 🧱 Tecnologias Utilizadas
- **Modelagem:** Brmodelo
- **Banco de Dados:** MySQL  
- **Controle de Versão:** Git e GitHub  
- **Documentação:** Google Docs / Markdown  
