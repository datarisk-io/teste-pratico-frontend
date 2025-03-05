Criar uma aplicação utilizando React e typescript, a aplicação deve conter 3 páginas. dashboard, detalhes e de login.

## 1.	Sobre a página de login:
 
 -  A página de login deve ser um formulário que vai pedir 2 informações: Nome e uma imagem. Essas informações devem ser persistidas localmente.
 - Após a autenticação, o usuário deve ser direcionado a uma página onde deve ser implementado uma listagem
 - Se ao acessar a aplicação, não existir um usuário, o mesmo deve ser redirecionado para a página de login
 
## 2 - Sobre o Layout
  - O layout padrão da área logada vai consistir de um header onde informações do usuário devem ser exibidas. Um clique nas informações do usuário deve abrir um menu flutuante que dará a opção de logout.

## 3.	Sobre a página de listagem

 -	A listagem deve ser implementada com a api do Rick and Morty: https://rickandmortyapi.com/
 -  Deve ser listado para o usuário os personagens do show. Ao clicar no card do personagem deve ser aberto o detalhamento. 
 -	A paginação deve ser feita através de um scroll infinito. 

## 4.	Sobre a página de detalhes
 A página de detalhes do personagem especifico pode ser exibida de 2 maneiras:
 -	Através de rotas se jogada diretamente na URL, assim o detalhamento vai ser uma página.
 -	Através de um modal, quando clicado em um personagem na pagina de listagem


## 6. Sobre as tecnologias
 - Deve ser utilizado React e typescript, mas estilização e bibliotecas para chegar ao resultado, são de sua escolha. Não esqueça de deixar as páginas bem bonitas e com uma boa usabilidade.


## 5. Documentação
 Criar um readme explicando como rodar a aplicação e as libs utilizadas
