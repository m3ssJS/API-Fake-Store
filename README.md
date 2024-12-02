# Painel de Controle - Loja Online 🛒

Este projeto é um painel de controle desenvolvido para gerenciar e monitorar informações de uma loja online utilizando os dados fornecidos pela [Fake Store API](https://fakestoreapi.com/). Com ele, você pode visualizar, adicionar, editar e remover produtos, pedidos e usuários, além de acessar relatórios e métricas.

---

## 📋 Funcionalidades Principais

### 🛍️ Produtos
- Listar todos os produtos.
- Visualizar detalhes de um produto específico.
- Filtrar e ordenar produtos por preço ou classificação.
- Adicionar, atualizar e remover produtos.

### 📂 Categorias
- Listar e filtrar produtos por categoria.

### 🛒 Carrinhos (Pedidos)
- Listar todos os pedidos.
- Visualizar os detalhes de um pedido (produtos e quantidades).
- Filtrar pedidos por data e/ou usuário.
- Adicionar, atualizar e remover itens do carrinho.

### 👥 Usuários
- Listar todos os usuários.
- Visualizar os detalhes de um usuário específico.
- Adicionar, atualizar e remover usuários.

### 🔐 Autenticação
- Tela de login para acesso ao painel.
- Validação de credenciais com feedback de erro em caso de login inválido.

### 📊 Painel Inicial
- Exibição de indicadores:
  - Total de produtos.
  - Número de categorias.
  - Quantidade de pedidos.
  - Número total de usuários.

---

## 🛠️ Tecnologias Utilizadas

- **Vue.js 3**: Framework principal para desenvolvimento do front-end.
- **Vue Router**: Gerenciamento de rotas para navegação entre páginas.
- **Axios**: Consumo de dados da API.
- **Vuex/Composition API**: Gerenciamento de estado compartilhado entre componentes.
- **CSS Responsivo**: Layout adaptado para desktop e dispositivos móveis.

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_PROJETO>

2. **Instale as dependências**:

    npm install

3. **Inicie o servidor de desenvolvimento**:

    Abra um novo terminal no VSCode: Terminal > New Terminal.
    Execute o comando
    npm run server
    Pressione Ctrl e clique no primeiro link exibido no terminal para abrir o painel no navegador.

4. **Acesse o painel**:

    Insira as credenciais de login para acessar o painel de controle.

🖥️ Estrutura do Projeto
    - src/components: Componentes reutilizáveis (e.g., tabelas, modais); Páginas principais (Produtos, Usuários, Carrinhos, Login).
    - src/store: Configuração do Vuex/Composition API.
    - src/router: Configuração de rotas do Vue Router.
    - src/assets: Arquivos estáticos (imagens, estilos).

🔍 Critérios de Avaliação
    - Código organizado e de fácil manutenção.
    - Integração eficiente da API Fake Store.
    - Experiência do usuário agradável e intuitiva.
    - Layout responsivo e visualmente atraente.
    - Tratamento de erros com mensagens claras ao usuário.

📞 Suporte
    Se você encontrar algum problema ou tiver dúvidas, entre em contato com >> bruno.messias@fatec.sp.gov.br <<

👨‍💻 Desenvolvido por **Bruno Henrique Messias**
