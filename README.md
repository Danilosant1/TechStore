# Documentação do Sistema de Gerenciamento de Produtos - TechStore

## Visão Geral
O sistema **TechStore** é uma aplicação web desenvolvida para gerenciar produtos de uma loja virtual, permitindo realizar operações de **CRUD** (Criar, Ler, Atualizar e Deletar) em produtos.

---

## Tecnologias Utilizadas

- **Linguagem**: Python 3
- **Framework**: Flask
- **Banco de Dados**: SQLite
- **Frontend**: HTML, CSS e Bootstrap
- **Gerenciamento de Dependências**: Virtual Environment (venv) e pip
- **Controle de Versão**: Git e GitHub

---

## Como Executar o Projeto

### **1. Clonar o Repositório**

```bash
git clone https://github.com/seuusuario/techstore.git
cd techstore
```

### **2. Criar e Ativar o Ambiente Virtual**

**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/Mac:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### **3. Instalar as Dependências**

```bash
pip install -r requirements.txt
```

### **4. Executar a Aplicação**

```bash
python app.py
```

### **5. Acessar no Navegador**

Abra o navegador e acesse: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## Estrutura do Projeto

```
techdrop/
│-- .idea/            # Arquivos de configuração do PyCharm
│-- templates/        # Arquivos HTML da aplicação
│-- .gitignore        # Arquivos e pastas ignorados pelo Git
│-- app.py            # Arquivo principal da aplicação Flask
│-- requirements.txt  # Dependências do projeto

```

---

## Possíveis Melhorias Futuras

✅ **Autenticação de Usuários** - Implementar login e controle de acesso.
✅ **Melhoria no Design** - Criar um layout mais moderno e responsivo.
✅ **Banco de Dados SQL mais robusto** - Migrar de SQLite para PostgreSQL.
✅ **API REST** - Criar endpoints para permitir integrações externas.
✅ **Filtros de Pesquisa** - Implementar pesquisa por nome, preço e estoque.

---

## Autor
- **Danilo Santiago**  
- **Email: danilo.santiago5050@gmail.com**  
- **GitHub: [Danilosant1](https://github.com/Danilosant1)**

