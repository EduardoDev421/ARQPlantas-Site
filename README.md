# 🌙 TechMoon - E-commerce de Periféricos

Projeto final do curso desenvolvido para uma loja virtual especializada em periféricos de tecnologia (monitores,teclados, mouses, headsets e acessórios).

## 📋 Sobre o Projeto

O **TechMoon** é um e-commerce completo que oferece uma experiência de compra intuitiva para produtos de tecnologia. O projeto foi desenvolvido utilizando HTML5, CSS3 e JavaScript, focando em design responsivo e usabilidade.

### 🎯 Objetivos
- Criar uma interface moderna e atrativa
- Implementar sistema de autenticação de usuários
- Desenvolver carrinho de compras funcional
- Proporcionar experiência responsiva em diferentes dispositivos

## 🚀 Funcionalidades

### ✅ Implementadas
- **Catálogo de Produtos**: Navegação por categorias (Teclados, Mouses, Headsets, Acessórios)
- **Sistema de Autenticação**: Páginas de login e cadastro
- **Carrinho de Compras**: Adição e remoção de produtos
- **Página de Produto**: Detalhes, imagens e opções de pagamento
- **Área do Cliente**: Gerenciamento de dados pessoais, endereços e pedidos
- **Design Responsivo**: Adaptável para desktop e mobile

### 🔄 Em Desenvolvimento
- Validação de formulários com JavaScript
- Persistência de dados no localStorage
- Sistema de busca funcional
- Animações e transições

## 📁 Estrutura de Arquivos

```
projetofinal/
├── back/                 # Backend da aplicação
│   ├── api/
│   │   ├── controllers/
│   │   │   └── usuarioController.js
│   │   ├── routes.js
│   │   └── server.js
│   ├── bd/
│   │   └── conexao.js
│   ├── .env
│   ├── package.json
│   └── package-lock.json
├── front/                # Frontend da aplicação
│   ├── css/
│   │   ├── autenticacao/
│   │   │   ├── cadastro.css
│   │   │   ├── login.css
│   │   │   └── senha.css
│   │   ├── categorias/
│   │   │   ├── acessorio.css
│   │   │   ├── headset.css
│   │   │   ├── monitores.css
│   │   │   ├── mouse.css
│   │   │   ├── ofertas.css
│   │   │   └── teclado.css
│   │   ├── conta/
│   │   │   ├── conta.css
│   │   │   ├── dados.css
│   │   │   ├── endereco.css
│   │   │   ├── logout.css
│   │   │   ├── pagamento.css
│   │   │   └── pedidos.css
│   │   ├── pages/
│   │   │   ├── carrinho.css
│   │   │   ├── conta.css
│   │   │   ├── pagamento.css
│   │   │   └── produto.css
│   │   └── layout.css
│   ├── img/              # Imagens e ícones
│   │   ├── produtos/     # Imagens dos produtos
│   │   ├── ícones/       # Ícones da interface
│   │   └── fundos/       # Imagens de fundo
│   ├── js/
│   │   ├── core/         # Funcionalidades principais
│   │   │   ├── autenticacao.js
│   │   │   ├── busca.js
│   │   │   ├── carrinho.js
│   │   │   └── navegacao.js
│   │   ├── pages/        # Scripts específicos por página
│   │   │   ├── autenticacao/
│   │   │   │   ├── cadastro.js
│   │   │   │   ├── login.js
│   │   │   │   └── senha.js
│   │   │   ├── conta/
│   │   │   │   ├── dados.js
│   │   │   │   ├── pagamento.js
│   │   │   │   └── perfil.js
│   │   │   ├── pedidos/
│   │   │   │   └── pedidos.js
│   │   │   └── produto/
│   │   │       └── produto.js
│   │   └── api.js        # Comunicação com backend
│   └── pages/            # Páginas HTML
│       ├── autenticacao/
│       │   ├── cadastro.html
│       │   ├── login.html
│       │   └── senha.html
│       ├── carrinho/
│       │   ├── carrinho.html
│       │   └── pagamento.html
│       ├── categorias/
│       │   ├── acessorios.html
│       │   ├── headsets.html
│       │   ├── monitores.html
│       │   ├── mouses.html
│       │   ├── ofertas.html
│       │   └── teclados.html
│       ├── conta/
│       │   ├── dados.html
│       │   ├── enderecos.html
│       │   ├── formas-pagamento.html
│       │   ├── logout.html
│       │   ├── pedidos.html
│       │   └── perfil.html
│       ├── index.html    # Página inicial
│       └── produto.html
├── .gitignore
├── LICENSE
├── README.md
└── TABELA_SITE_MYSQL.sql # Estrutura do banco de dados
```

## 💻 Arquivos JavaScript

### **Core (Funcionalidades Principais)**

#### **autenticacao.js**
- Gerenciamento de sessões de usuário
- Validação de tokens
- Controle de acesso às páginas
- Redirecionamento automático

#### **carrinho.js**
- Adição e remoção de produtos
- Cálculo de totais e subtotais
- Persistência no localStorage
- Atualização dinâmica da interface

#### **busca.js**
- Sistema de busca por produtos
- Filtros por categoria e preço
- Sugestões automáticas
- Resultados em tempo real

#### **navegacao.js**
- Menu responsivo mobile
- Navegação entre páginas
- Carregamento dinâmico de conteúdo
- Controle de histórico

### **Pages (Scripts Específicos)**

#### **Autenticação**
- **login.js**: Validação e autenticação de usuários
- **cadastro.js**: Validação de CPF, email e senhas
- **senha.js**: Recuperação e alteração de senhas

#### **Conta do Usuário**
- **dados.js**: Gerenciamento de dados pessoais
- **pagamento.js**: Formas de pagamento
- **perfil.js**: Configurações do perfil

#### **Produtos e Pedidos**
- **produto.js**: Galeria de imagens e detalhes
- **pedidos.js**: Histórico e acompanhamento

### **API**
#### **api.js**
- Comunicação com o backend
- Requisições HTTP (GET, POST, PUT, DELETE)
- Tratamento de erros
- Interceptadores de requisição

## 🛠️ Tecnologias Utilizadas

### **Frontend**
- **HTML5**: Estruturação semântica das páginas
- **CSS3**: Estilização e design responsivo
- **JavaScript (ES6+)**: Interatividade e funcionalidades dinâmicas
- **Font Awesome**: Ícones e elementos visuais

### **Backend**
- **Node.js**: Ambiente de execução JavaScript
- **Express.js**: Framework web para APIs
- **MySQL**: Banco de dados relacional
- **dotenv**: Gerenciamento de variáveis de ambiente

### **Ferramentas**
- **Git**: Controle de versão
- **XAMPP**: Servidor local de desenvolvimento
- **Postman**: Testes de API (desenvolvimento)

## 💻 Como Executar o Projeto

### **Pré-requisitos**
- Node.js (versão 14 ou superior)
- MySQL (ou XAMPP com MySQL)
- Navegador web moderno

### **Configuração do Backend**

1. **Clone o repositório**
   ```bash
   git clone https://github.com/davisouzafarias88-art/ProjetoFinal_Senac.git
   cd ProjetoFinal_Senac
   ```

2. **Configure o banco de dados**
   - Inicie o XAMPP e ative MySQL
   - Importe o arquivo `TABELA_SITE_MYSQL.sql` no phpMyAdmin
   - Crie um banco de dados chamado `ecommerce`

3. **Configure o backend**
   ```bash
   cd back
   npm install
   ```

4. **Configure as variáveis de ambiente**
   - Renomeie `.env.example` para `.env` (se existir)
   - Configure as credenciais do banco de dados

5. **Inicie o servidor**
   ```bash
   npm start
   ```

### **Execução do Frontend**

1. **Abra o arquivo principal**
   - Navegue até `front/pages/index.html`
   - Abra no navegador ou use um servidor local

2. **Navegação no Site**
   - **Página Inicial**: `front/pages/index.html`
   - **Login**: `front/pages/autenticacao/login.html`
   - **Cadastro**: `front/pages/autenticacao/cadastro.html`
   - **Produtos**: Navegue pelas categorias no menu
   - **Carrinho**: Ícone do carrinho no header

### 🔗 Estrutura de Navegação
```
Página Inicial (index.html)
├── Categorias
│   ├── Teclados
│   ├── Mouses
│   ├── Headsets
│   ├── Monitores
│   ├── Acessórios
│   └── Ofertas
├── Autenticação
│   ├── Login
│   ├── Cadastro
│   └── Recuperar Senha
├── Carrinho de Compras
│   ├── Visualizar Carrinho
│   └── Finalizar Pagamento
└── Área do Cliente
    ├── Perfil
    ├── Meus Dados
    ├── Endereços
    ├── Pedidos
    ├── Formas de Pagamento
    └── Logout
```

## 👥 Equipe de Desenvolvimento