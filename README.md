## Desafio 04: MovieFlix domínio e autorização - Bootcamp DevSuperior
O sistema MovieFlix consiste em um banco de filmes, os quais podem ser listados e avaliados pelos usuários. Usuários podem ser visitantes (VISITOR) e membros (MEMBER). Apenas usuários membros podem inserir avaliações no sistema.

Ao acessar o sistema, o usuário deve fazer seu login. Apenas usuários logados podem navegar nos filmes. Logo após fazer o login, o usuário vai para a listagem de filmes, que mostra os filmes de forma paginada, ordenados alfabeticamente por título. O usuário pode filtrar os filmes por gênero.

Ao selecionar um filme da listagem, é mostrada uma página de detalhes, onde é possível ver todas informações do filme, e também suas avaliações. Se o usuário for MEMBER, ele pode ainda registrar uma avaliação nessa tela.

Um usuário possui nome, email e senha, sendo que o email é seu nome de usuário. Cada filme possui um título, subtítulo, uma imagem, ano de lançamento, sinopse, e um gênero. Os usuários membros podem registrar avaliações para os filmes. Um mesmo usuário membro pode deixar mais de uma avaliação para o mesmo filme.


- Modelo conceitual
![image](https://user-images.githubusercontent.com/92943261/182980359-e3ab90bd-366c-4aaf-8315-135af15eb15f.png)

- Requisitos do seed para os testes passarem: </br>
    Seu seed deve conter dois usuários: </br>
	      a.	Usuário somente com perfil VISITOR: </br>
            i.	email: bob@gmail.com </br>
            ii.	senha: 123456 </br>
        b.	Usuário com perfil MEMBER:</br>
            i.	email: ana@gmail.com </br>
            ii.	senha: 123456 </br>

