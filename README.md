# Projeto: Blog de Jornal Regional - Sapucaia do Sul

## Descrição
Este projeto visa desenvolver o **front-end de um blog** para o jornal regional da cidade de Sapucaia do Sul. O blog deve ser **funcional e esteticamente agradável**, oferecendo uma plataforma para a publicação de notícias locais. O design deve ser **acessível**, garantindo uma boa experiência para usuários em desktops.

### O blog incluirá:
- **Página Inicial**: Listagem das manchetes recentes.
- **Páginas de Artigos**: Conteúdo completo dos artigos (Pode ser artigos fictícios ou reais - não esquecer de inserir imagem/foto no artigo).
- **Categorias**: Seção para diferentes categorias de notícias, como notícias da cidade, trânsito, e comunidade jovem.
- **Contato**: Área para os leitores entrarem em contato com a equipe do jornal.

__Os desenvolvedores têm a liberdade de expandir as categorias de notícias conforme necessário, para melhor atender às necessidades da comunidade de Sapucaia do Sul.__ <br>
__Inventar um logotipo para o jornal (Se desejar use o site Canva) e caso queiram podem dar um novo nome para o jornal local.__


## Requisitos do Projeto

### 1. Página Inicial
- Exibir uma lista de manchetes recentes.
- Cada manchete deve ser um link para a página do artigo completo.
- Incluir uma barra de navegação com links para:
  - Página inicial
  - Categorias (ex.: Cidade, Trânsito, Comunidade Jovem)
  - Contato
- Estrutura da página:
  - **Cabeçalho** com o título do jornal e a barra de navegação.
  - **Seção principal** contendo os artigos com título, resumo e link para o artigo completo.
  - **Rodapé** com informações de copyright.

### 2. Página de Artigo
- Estrutura da página:
  - **Cabeçalho** com o título do jornal e a barra de navegação.
  - **Título do artigo**.
  - **Data de publicação**.
  - **Nome do autor**.
  - **Conteúdo completo do artigo**.
  - Navegação para o artigo anterior e próximo.
  - **Rodapé** com informações de copyright.

### 3. Página de Categorias
- Exibir uma lista de categorias de artigos, como:
  - **Notícias da Cidade**
  - **Notícias do Trânsito**
  - **Comunidade Jovem**
- Cada categoria deve ser um link que leva a uma página listando todos os artigos dessa categoria.
- Estrutura da página:
  - **Cabeçalho** com o título do jornal e a barra de navegação.
  - **Seção principal** com a lista de categorias.
  - **Rodapé** com informações de copyright.

### 4. Página de Contato
- **Formulário de contato** com os seguintes campos:
  - **Nome** (campo de texto)
  - **E-mail** (campo de texto)
  - **Mensagem** (área de texto)
- **Botão para enviar o formulário**.
- Estrutura da página:
  - **Cabeçalho** com o título do jornal e a barra de navegação.
  - **Seção principal** contendo o formulário de contato.
  - **Rodapé** com informações de copyright.

## Estilo e Design
- Utilizar **CSS** para estilização das páginas.
- O design deve ser **limpo e moderno**, utilizando cores suaves e tipografia legível. (**Livre escolha**)
- O site deve funcionar bem em dispositivos desktops.
- Incluir classes CSS para os seguintes elementos:
  - **Cabeçalho** (`header`) 
  - **Barra de navegação** (`nav`)
  - **Lista de navegação** (`nav ul`)
  - **Itens da lista de navegação** (`nav ul li`)
  - **Links de navegação** (`nav ul li a`)
  - **Seção principal** (`main`)
  - **Artigos** (`article`)
  - **Rodapé** (`footer`)
  - **Formulário de contato** (`form`)
  - **Campos do formulário** (`input`, `textarea`, `button`)

## Pesquisa Deverá ser Feita para Enriquecer o Presente Projeto
- **TAGs Semânticas**
- **IDs e Classes**
- **Estilização de barra de navegação**

## Tecnologias Utilizadas
- HTML5
- CSS3

## Modelo Sugerido no GitHub
- Você deverá **clonar esse repositório** e, a partir deste ponto, fazer as modificações de livre escolha respeitando o que foi sugerido, como por exemplo: cores suaves.

## Como Clonar:

```bash
git clone https://github.com/usuario/repositorio.git

```



## Estrutura de Arquivos

```plaintext
Projeto/
│
├── index.html         # Página inicial
├── article.html       # Página de artigo individual
├── categories.html    # Página de categorias
├── contact.html       # Página de contato
├── styles.css         # Arquivo de estilos CSS
└── README.md          # Instruções e requisitos do projeto
