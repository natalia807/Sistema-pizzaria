# Controle de Pedidos

### - Tecnologias Utilizadas

* HTML5
* CSS3
* JS
* PHP7
* MYSQL5
* Foundation Framework 6

---
### - Estrutura do Projeto

O projeto possui a seguinte organização de arquivos.

* index.html
* painel.php
* / admin           -> Pasta referente a as funções do administrador.
* / client          -> Pasta referente a as funções do cliente.
* / stock           -> Pasta referente a as funções do estoque/produtos.
* / css             -> Pasta com arquivos de estilo e fontes
* / img             -> Imagens do projeto
* / js              -> Arquivos JavaScript
* / php             -> Arquivos PHP para conecção com o banco de dados
  * / admin           -> Arquivos PHP para o administrador intermediarios com o banco de dados
  * / client          -> Arquivos PHP para o cliente intermediarios com o banco de dados
  * / stock           -> Arquivos PHP para o estoque intermediarios com o banco de dados
* / screenshots     -> Capturas de tela
* / scriptSQL        -> Script de criação do banco de dados do sistema

Para cada área do painel adminstrativo é feita uma pasta para acomodar os arquivos de cada função, e para a conexão com o banco de dados apara cada função também é criada outra pasta de mesmo nome na pasta PHP. Como por exemplo a pasta admin, com os arquivos de formulários das funções do painel e uma na pasta PHP para agir como intermediário ao banco de dados.

