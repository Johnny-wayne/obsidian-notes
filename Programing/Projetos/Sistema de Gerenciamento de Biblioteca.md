#### Linguagens: [[C-Sharp#]] - [[Python]] - [[SQL]] - [[React]]
---
### Descrição:

O objetivo desse projeto é desenvolver um sistema de gerenciamento de biblioteca que permita aos usuários realizar operações como adicionar livros, pesquisar livros, verificar disponibilidade, realizar empréstimos, devoluções, entre outras funcionalidades. O sistema será composto por uma aplicação desktop em C# para a interface do usuário, um script Python para manipulação e análise de dados e um banco de dados SQL para armazenar informações dos livros e usuários.

---
#### Funcionalidades sugeridas:

1. Cadastro de Livros: Permite ao usuário adicionar novos livros ao sistema, informando título, autor, ano de publicação, gênero, ISBN, etc.
    
2. Pesquisa de Livros: Permite ao usuário pesquisar livros por título, autor, gênero, ISBN, etc.
    
3. Empréstimo de Livros: Usuários registrados podem solicitar empréstimos de livros disponíveis. O sistema deve controlar as datas de empréstimo e devolução.
    
4. Devolução de Livros: Usuários registrados podem devolver os livros emprestados.
    
5. Relatórios: Geração de relatórios com informações como livros mais populares, livros emprestados, histórico de empréstimos de um usuário específico, etc.

---
## Tecnologias:

1. Front-End com [[React]]:
    - Utilize o React para criar a interface do usuário do sistema de gerenciamento de biblioteca. Isso incluiria as telas para cadastro de livros, pesquisa, empréstimo, devolução e outros recursos necessários.
    - Crie componentes reutilizáveis no React para garantir que a interface seja modular e fácil de manter.
    - Conecte o front-end React ao back-end (C# e Python) para enviar e receber dados, através de APIs RESTful ou outras formas de comunicação.
	
2. Back-End com [[C-Sharp#]] e [[Python]]:
    - Continue usando C# para o desenvolvimento do aplicativo desktop, gerenciando a lógica do sistema e a comunicação com o banco de dados SQL.
    - Use Python para escrever scripts que manipulam dados e geram relatórios mais complexos, se necessário.
    
3. Banco de Dados SQL:
    
    - Mantenha o banco de dados SQL para armazenar informações sobre livros, usuários, empréstimos, etc. O React e o C#/Python devem interagir com o banco de dados para buscar e persistir dados.
