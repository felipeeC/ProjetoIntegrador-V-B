# Projeto PrimeFlix


Introdução:
O sistema é uma API desenvolvida utilizando a linguagem Java e o framework Spring Boot. Ele tem como objetivo fornecer funcionalidades relacionadas a uma biblioteca de filmes, permitindo interações como adicionar filmes, remover filmes, editar informações de filmes, adicionar filmes à lista pessoal e visualizar listas de filmes básicas e detalhadas. Neste documento, iremos explicar o funcionamento básico do sistema e as tecnologias utilizadas durante seu desenvolvimento.

Funcionamento básico:
O sistema é uma API que possibilita aos usuários interagir com uma biblioteca de filmes. As principais funcionalidades do sistema são:

1. Adicionar filme: Os usuários podem adicionar novos filmes à biblioteca fornecendo informações como nome, descrição, data de lançamento, atores, diretor, entre outros detalhes relevantes.
2. Remover filme: Os usuários têm a capacidade de remover filmes existentes da biblioteca. Ao fornecer o identificador único do filme, o sistema remove o filme correspondente da coleção.
3. Editar filme: É possível editar as informações de filmes existentes na biblioteca. Os usuários podem modificar dados como nome, descrição, data de lançamento, atores, diretor, etc., fornecendo o identificador único do filme e as informações atualizadas.
4. Adicionar filmes à minha lista (my list): Os usuários podem adicionar filmes de seu interesse a uma lista pessoal chamada "Minha Lista" (ou "My List"). Essa lista permite que os usuários salvem filmes que desejam assistir posteriormente ou que consideram favoritos.
5. Ver lista de filmes básica: Os usuários podem visualizar uma lista básica de filmes disponíveis na biblioteca. Essa lista contém informações como nome e descrição dos filmes.
6. Ver lista de filmes detalhada: Além da lista básica, os usuários podem acessar uma lista de filmes detalhada. Essa lista inclui informações mais completas sobre os filmes, como nome, descrição, data de lançamento, atores, diretor e outros detalhes relevantes.
7. Ver minha lista: Os usuários podem visualizar a lista pessoal "Minha Lista" (ou "My List"), que contém os filmes que eles adicionaram anteriormente. Essa lista permite aos usuários acompanhar os filmes que desejam assistir ou que já assistiram.

Tecnologias utilizadas:
O sistema foi desenvolvido utilizando as seguintes tecnologias:

1. Java: A linguagem de programação Java foi escolhida como base para o desenvolvimento do sistema devido à sua ampla adoção e suporte para o desenvolvimento de aplicativos corporativos robustos.
2. Spring Boot: O sistema utiliza o framework Spring Boot, que simplifica o desenvolvimento de aplicativos Java, fornecendo recursos poderosos e uma configuração mínima. Ele facilita a criação de APIs RESTful e oferece uma arquitetura flexível para o desenvolvimento do sistema.
3. Banco de dados: O sistema faz uso de um banco de dados MySql para armazenar as informações dos filmes e das listas pessoais dos usuários.
4. APIs RESTful: O sistema foi projetado seguindo a arquitetura REST (Representational State Transfer), utilizando verbos HTTP (GET, POST, PUT, DELETE) para as diferentes operações disponíveis. Isso permite que os clientes interajam com o sistema de forma fácil e eficiente.

Conclusão:
O sistema é uma API de biblioteca de filmes desenvolvida em Java com o uso do Spring Boot. Ele oferece funcionalidades básicas para gerenciar uma coleção de filmes, permitindo aos usuários adicionar, remover e editar informações de filmes, além de fornecer recursos para criar uma lista pessoal de filmes. O sistema utiliza tecnologias modernas e robustas para garantir a eficiência, escalabilidade e facilidade de uso. Com essas funcionalidades, os usuários podem desfrutar de uma experiência completa ao explorar e gerenciar uma biblioteca de filmes.
