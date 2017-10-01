# MINI PROJETO 6

A ideia desse desafio é estimular o estudo de novas tecnologias e acabar ou pelo menos diminuir o preconceito que muitos têm com a linguagem **Ruby**.

----------

Linguagem Ruby
--------

**Ruby** ([https://www.ruby-lang.org/][1]) Ruby é uma linguagem com um cuidadoso equilíbrio. O seu criador, Yukihiro "Matz" Matsumoto, uniu partes das suas linguagens favoritas (Perl, Smalltalk, Eiffel, Ada e Lisp) para formar uma nova linguagem que equilibra a programação funcional com a programação imperativa.

Desde que foi tornado público em 1995, o Ruby arrastou consigo programadores devotos em todo o mundo. Em 2006, o Ruby atingiu aceitação massiva, com a formação de grupos de usuários em todas as principais cidades do mundo e com as conferências sobre Ruby com lotação esgotada.

Ruby está posicionado no top 10 da maioria dos índices que medem o crescimento da popularidade de linguagens de programação pelo mundo todo (tais como o índice TIOBE). Muito deste crescimento é atribuído à popularidade de softwares escritos em Ruby, em particular o framework de desenvolvimento web Ruby on Rails.

O Ruby também é totalmente livre. Não somente livre de custos, mas também livre para utilizar, copiar, modificar e distribuir..

Ruby é utilizada em diversos projetos como:

- **GitHub** (Dispensa apresentações)
- **Airbnb** (Airbnb é um mercado comunitário confiável para pessoas anunciarem, descobrirem e reservarem acomodações únicas ao redor do mundo);
- **Ask.fm** (Rede social que permite que os usuários façam ou recebam perguntas, anônimas ou não, de outros usuários ou de pessoas não cadastradas);
- **Basecamp** (Software para gerenciamento de projetos);
- **Dribbble** (Rede social para designers exporem seus projetos);
- **Groupon** (Um dos maiores portais do mundo de compras coletivas);
- **SlideShare** (Repositório de slides muito utilizado em todo o mundo);
- **Strava** (Rede Social para amantes de corridas e Ciclismo);
- **ThemeForest** (Um dos maiores sites do mundo de venda de templates);
- **Zendesk** (Ferramenta para atendimento de clientes e suporte por Tickets);
- **SASS** (Sass é uma nova forma de trabalhar com CSS, onde nos temos mais liberdade para tratar os estilos aplicando conceitos de programação OO);

Confira também o [Manual da linguagem][2]

----------

Desafio
--------

Crie um aplicativo console em Ruby (ou Web, com o Rails) para gerenciamento de Ordens de Serviço para uma empresa qualquer. 

O aplicativo deverá ter opções para:

- Cadastrar, Editar, Buscar e Excluir Clientes (Apenas dados básicos como NOME, DOCUMENTO, TELEFONE e EMAIL);
- Cadastrar, Editar, Buscar e Excluir Funcionários (Apenas dados básicos como NOME, DOCUMENTO, TELEFONE e EMAIL);
- Cadastrar, Editar, Buscar, Ver e Excluir Ordens de Serviço (NÚMERO DA OS, CLIENTE, FUNCIONÁRIO, DESCRIÇÃO DO SERVIÇO, DATA DE SOLICITAÇÃO, PREVISÃO DE CONCLUSÃO);

> **Observações:**

> - Os dados deverão ser persistidos em um banco sqlite
> - Opcionalmente você pode criar um sistema de login e senha para proteger o seu sistema
> - O sistema deverá ter validação. Todos os campos de todas as telas são obrigatórios. O campo E-mail deve conter um e-mail válido e o campo documento deve conter apenas números
> - Na tabela de Ordens de Serviço, o NÚMERO DA OS deverá ser a chave primária da tabela e os campos CLIENTE e FUNCIONÁRIO devem receber apenas o ID do cliente e funcionário respectivamente
> - Não existe prazo limite para conclusão, a ideia é que você tenha uma experiência diferente.
> - Ao finalizar o seu projeto, publique-o no Github e envie o link para bugginhodeveloper@gmail.com

----------

[1]: https://www.ruby-lang.org/pt
[2]: https://www.ruby-lang.org/pt/documentation/
