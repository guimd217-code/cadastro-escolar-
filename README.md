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
O DER foi desenvolvido no [app.diagrams.net](https://app.diagrams.net/) e está disponível na pasta `/documentacao`.

**Arquivo:** `documentacao/DER_final.png`

---

## 🗂️ Estrutura do Projeto
