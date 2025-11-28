## 🖥️ PHP
Implementação da linguagem PHP no projeto Dr. Peanut, com foco no processamento das informações do sistema e na criação de páginas dinâmicas que respondem às ações do usuário.
O objetivo é permitir:
Processamento de informações no lado do servidor


Integração com HTML e páginas dinâmicas


Manipulação de dados enviados pelos usuários


Execução de regras, validações e fluxos lógicos

## 🏗️  Estrutura do Sistema
'conexao.php' — Responsável por conectar o sistema ao MySQL e definir o charset padrão.

---

### 🔐 Autenticação

- *fazer_login.php* → Valida credenciais e cria a sessão do usuário  
- *sair.php* → Encerra a sessão ativa e redireciona para o login  

---

### 👤 Usuários

- *salvar_usuario.php* → Cadastro de novos usuários no sistema  

---

### 🏢 Fornecedores

- *salvar_fornecedor.php* → Cadastro de fornecedores  
- *delete_fornecedor.php* → Exclusão de fornecedores pelo ID  

---

### 📦 Produtos

- *salvar_produto.php* → Cadastro de produtos + upload de imagens  
- *delete_produto.php* → Exclusão de produtos pelo ID



# 🎯 Objetivos do Sistema

- ➕ Cadastrar novos usuários, fornecedores e produtos  
- ✏️ Editar registros existentes  
- 🗑️ Excluir informações do banco  
- 🔗 Relacionar fornecedores com produtos  
- 🔐 Autenticar usuários com login e sessão  
- 🖼️ Fazer upload de imagens para produtos  
- 🌐 Gerar páginas dinâmicas com PHP



O PHP é responsável por:
- ⚙️ Processar os dados
- 📦 Manipular registros no banco
- 📤 Receber formulários
- 🔄 Executar lógicas de validação
- 🔐 Gerenciar sessões de login
- 🌐 Construir páginas dinâmicas

---

