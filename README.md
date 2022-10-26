# Sobre o projeto
Trata-se de um desafio do bootcamp DevSuperior, neste desafio implementamos o modelo conceitual proposto (movieflix).
Incluímos também a infraestrutura de exceções, validação e segurança ao projeto.

## Modelo conceitual:
<div>
 <img src="https://user-images.githubusercontent.com/85883895/198030703-1e2dc0d0-06e2-4688-b13b-1d38f865b44b.png" width="500px" height="250px" /> <br/>
</div>

## Seed do banco de dados:
Nosso seed contém 2 usuários: <br/>
Usuário somente com perfil VISITOR: <br/>
email: bob@gmail.com <br/>
senha: 123456 <br/>
Usuário com perfil MEMBER: <br/>
email: ana@gmail.com <br/>
senha: 123456 

## Endpoint:
- GET /users/profile: <br/>
Obtém o perfil do usuário logado. O usuário logado só poderá buscar pelo seu próprio perfil. 
