# README do Projeto de Filmes
## Tecnologias
O projeto utiliza as seguintes tecnologias:

React: Uma biblioteca JavaScript para construir interfaces de usuário.

React Router Dom: Uma biblioteca que permite a navegação entre diferentes componentes, alterando o URL do navegador, mantendo a interface do usuário sincronizada com o URL.

React Icons: Uma biblioteca que inclui uma coleção de ícones acessíveis, utilizáveis e personalizáveis para projetos React.

Vite: Uma ferramenta de construção moderna que oferece uma experiência de desenvolvimento mais rápida e enxuta.

APIs: O projeto utiliza várias APIs para buscar dados sobre filmes. As URLs dessas APIs são armazenadas como variáveis de ambiente.

CSS: Utilizado para estilizar os componentes da aplicação. Cada componente tem seu próprio arquivo CSS.

## Dependências
O projeto depende das seguintes bibliotecas:

react: ^18.0.0
react-dom: ^18.0.0
react-icons: ^4.4.0
react-router-dom: ^6.3.0

## Descrição

Este projeto é uma aplicação web para visualização de filmes. Ele apresenta um catálogo de filmes onde os usuários podem pesquisar filmes específicos e ver detalhes sobre eles. O projeto é construído usando React e inclui componentes como `MovieCard`, `Navbar`, `Home`, `Search` e `Movie`.

## Componentes

### MovieCard

O componente `MovieCard` é usado para exibir um cartão de filme individual no catálogo. Ele mostra o título do filme, a classificação média dos votos e um link para a página de detalhes do filme.

### Navbar

O componente `Navbar` é a barra de navegação na parte superior da aplicação. Ele inclui um campo de pesquisa onde os usuários podem pesquisar filmes específicos.

### Home

O componente `Home` é a página inicial da aplicação. Ele exibe os filmes mais bem avaliados.

### Search

O componente `Search` é usado para exibir os resultados da pesquisa de filmes.

### Movie

O componente `Movie` é usado para exibir os detalhes de um filme específico.

## Estilos

Os estilos do projeto são escritos em CSS. Isso inclui estilos para a barra de navegação, os cartões de filme e outros elementos da interface do usuário.

## Variáveis de Ambiente

As seguintes variáveis de ambiente são necessárias para o projeto:

- `VITE_API_KEY`: A chave da API para acessar os dados do filme.
- `VITE_API`: A URL base da API para buscar dados do filme.
- `VITE_SEARCH`: A URL da API para realizar pesquisas de filmes.
- `VITE_IMG`: A URL base para buscar imagens de filmes.

## Como usar
voce deve  criar uma conta no site tmdb para receber sua chave de Api
Para usar este projeto, você pode clonar o repositório e instalar as dependências usando `npm install`. Em seguida, você pode iniciar o servidor de desenvolvimento usando `npm start`.

## Contribuindo

Contribuições para este projeto são bem-vindas. Por favor, abra um problema ou faça um pedido de pull se você tiver algo que gostaria de adicionar ou alterar.

