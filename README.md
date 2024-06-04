## Catálogo de livros para o Challenge LiterAlura referente ao programa ONE - Oracle Next Education.<br><br>

O projeto LiterAlura foi desenvolvido em Java com Spring Boot e PostgreSQL, utilizando a IDE IntelliJ IDEA Community Edition.<br>

São utilizados os dados da API https://gutendex.com/ e realizadas ações de acordo com as escolhas do usuário.<br><br><br>

Ao iniciar o programa, uma lista de opções é exibida:<br>

<img src="readme/opcoes.png" alt="Imagem da tela de início do programa.">

Ao escolher a opção 1, poderá ser realizada uma busca online na API com base no nome inserido e uma prévia dos dados será exibida.<br>

<img src="readme/opcao-1.png" alt="Imagem da busca.">

Caso nada seja encontrado o programa irá avisar ao usuário.<br>

<img src="readme/opcao-1-sem-resultados.png" alt="Imagem da busca sem resultados.">

A opção 2 exibe todos os livros salvos no banco de dados, o nome dos autores são exibidos no padrão brasileiro.
Exemplo: "Marx, Karl" é exibido como "Karl Marx".<br>

<img src="readme/opcao-2.png" alt="Imagem da lista de livros salvos no bando de dados.">

A opção 3 permite ao usuário exibir os livros encontrados pelo título ou parte do título digitado.<br>

<img src="readme/opcao-3.png" alt="Imagem da lista de livros encontrada por título.">

Caso nada seja encontrado, o programa irá avisar ao usuário.<br>

<img src="readme/opcao-3-nao-encontrado.png" alt="Imagem de nada encontrado.">

A opção 4 exibe todos os autores salvos no banco de dados, o nome dos autores também são exibidos no padrão brasileiro.<br>

<img src="readme/opcao-4.png" alt="Imagem da lista de autores.">

A opção 5 permite ao usuário procurar por autores vivos com base no ano que o usuário escolher.<br>

<img src="readme/opcao-5.png" alt="Imagem da lista de autores vivos com base ano que o usuário digitou.">

Caso nada seja encontrado, o programa irá avisar ao usuário.<br>

<img src="readme/opcao-5-nada-encontrado.png" alt="Imagem de nada encontrado.">

Caso a opção digitada sejá inválida, o programa irá avisar ao usuário.<br>

<img src="readme/opcao-5-opcao-invalida.png" alt="Imagem de opção inválida.">

A opção 6 exibe todos os livros salvos no banco de dados por idioma.<br>

<img src="readme/opcao-6.png" alt="Imagem da lista de todos os livros por idioma.">

A opção 7 permite ao usuário procurar por livros com base no código do idioma que o usuário escolher.
A lista de códigos é gerada com base nos idiomas presentes no banco de dados.<br>

<img src="readme/opcao-7.png" alt="Imagem da lista de códigos e busca de livros por idioma.">

Caso o código seja inválido, o programa irá avisar ao usuário.<br>

<img src="readme/opcao-7-opcao-invalida.png" alt="Imagem de opção inválida.">

A opção 8 exibe os top 10 livros mais baixados em ordem decrescente.<br>

<img src="readme/opcao-8.png" alt="Imagem do top 10 livros por download.">

Caso o banco de dados esteja vázio, todas as opções exceto a 1 irão avisar ao usuário.

<img src="readme/opcao-db-vazio.png" alt="Imagem do aviso de banco de dados vazio.">

<br>
<br>

### Autores:
<a href="https://github.com/jhonathan-p" target="_blank">Jhonathan Pfeiffer Urbainski</a>