# Projeto de Avaliação - CRUD de Produtos (Vue.js + Express + MySQL)

Vitor Rodrigo Fraille Pereira -
Bruno Borcardt

Este projeto implementa um sistema completo de gestão de produtos, utilizando autenticação Google e um fluxo CRUD.

## 📋 Requisitos para Execução

Para rodar o projeto localmente, você precisará ter:  
1.  **Node.js (versão 18+)**
2.  **MySQL Server** (Recomendamos MySQL 8.0)
3.  **Cliente MySQL** (DBeaver, MySQL Workbench, etc.)

---

## ⚙️ 1. Configuração do Backend (API REST)

### 1.1. Configuração do Banco de Dados

Crie o banco de dados e a tabela no seu cliente MySQL.

**Ajuste de Autenticação (Obrigatório para MySQL 8+):**
Execute o seguinte comando SQL, substituindo `[SUA SENHA]` pela senha do seu usuário `root` no MySQL:
```sql
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '[SUA SENHA]';
FLUSH PRIVILEGES;
