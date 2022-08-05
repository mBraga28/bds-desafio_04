## Desafio 04: MovieFlix domínio e autorização - Bootcamp DevSuperior
O sistema MovieFlix consiste em um banco de filmes, os quais podem ser listados e avaliados pelos usuários. Usuários podem ser visitantes (VISITOR) e membros (MEMBER). Apenas usuários membros podem inserir avaliações no sistema.

Ao acessar o sistema, o usuário deve fazer seu login. Apenas usuários logados podem navegar nos filmes. Logo após fazer o login, o usuário vai para a listagem de filmes, que mostra os filmes de forma paginada, ordenados alfabeticamente por título. O usuário pode filtrar os filmes por gênero.

Ao selecionar um filme da listagem, é mostrada uma página de detalhes, onde é possível ver todas informações do filme, e também suas avaliações. Se o usuário for MEMBER, ele pode ainda registrar uma avaliação nessa tela.

Um usuário possui nome, email e senha, sendo que o email é seu nome de usuário. Cada filme possui um título, subtítulo, uma imagem, ano de lançamento, sinopse, e um gênero. Os usuários membros podem registrar avaliações para os filmes. Um mesmo usuário membro pode deixar mais de uma avaliação para o mesmo filme.


<h3>Modelo conceitual</h3>
<img align="center" height="250" width="500" src="https://user-images.githubusercontent.com/92943261/182980359-e3ab90bd-366c-4aaf-8315-135af15eb15f.png">

<h3>Requisitos do seed para os testes passarem: </h3>
   Seu seed deve conter dois usuários: 
   <ul>
       <li>Usuário somente com perfil VISITOR: 
	  <ul>
	      <li>email: bob@gmail.com </li>
              <li>senha: 123456 </li>
	  </ul>
       </li>
   </ul>			
   <ul>
       <li>Usuário com perfil MEMBER:
	  <ul>
	      <li>email: ana@gmail.com </li>
	      <li>senha: 123456 </li>
	  </ul>
       </li>
   </ul>	
   
<h3>Collection do Postman:</h3>
https://www.getpostman.com/collections/72a46c64473b7611a021
