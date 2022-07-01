# Olá! Bora tomar um café? ☕

## Me chamo Gabriel!

Sou Dev com foco no Back-end (com conhecimento no Front-end também) e me aventuro nos mais diversos projetos. 🤘

Entre em contato.

---

## Contato

<a href="https://www.linkedin.com/in/gabriel-matheus-silva-9a19a086/">
<img width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" />

</a>

---

## Linguagens

<table>
<thead>
    <tr>
        <th>BACK-END</th>
        <th>FRONT-END</th>
        <th>FRAMEWORKS</th>
        <th>BANCO DE DADOS</th>
        <th width="50">CONTAINERS E ORQUESTRADORES</th>
    </tr>
</thead>
<tbody>
    <tr align="center">
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-plain-wordmark.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original-wordmark.svg" />
        </td>
    </tr>
    <tr align="center">
        <td></td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original-wordmark.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original-wordmark.svg" />
        </td>
        <td></td>
    </tr>
    <tr align="center">
        <td></td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" />
        </td>
        <td>
            <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original-wordmark.svg" />
        </td>
        <td></td>
    </tr>
</tbody>
</table>

---

## Experiência

### 💻 Back-end:

- Linguagem: PHP;
- Framework: [Laravel](https://laravel.com/);
- Banco de dados MySQL, PostgreSQL (inclusive para multitenants) e Redis;

### 🎨 Front-end:

- HTML, CSS, JS;
- Pré-processadores: LESS e SASS (SCSS);
- Frameworks CSS: Bootstrap e Tailwindcss;
- Libs JS: React e Vuejs (este último mais usado nos projetos em que trabalhei);

### 📊 Infra/DevOps:

- Docker (ultimamente desenvolvo meus projetos com as "camadas" de banco SQL, cache, servidor, aplicação e etc. em
  containers separados);
- Mensageria (estudando RabbitMQ);

### 📂 Portfolio:

Segue abaixo alguns projetos nos quais trabalhei - do mais recente ao mais antigo:

1. **Aplius OKR:**
    - 🔗 Links:
        - 🏢 Site Comercial < https://aplius.com.br >
        - 💻 Sistema < http://nomedocliente.okr.aplius.com.br >
    - 💼 Descrição: Sistema de acompanhamento, gestão e auxílio de execução de metas baseado em OKR (Objective Key
      Result). O OKR é uma metodologia ágil que tem sido muito utilizada pelas empresas como uma forma de engajar seus
      colaboradores e mensurar o quão perto estão de seus objetivos;
    - 🧩 Funcionalidades:
        - [x] Mensuração de objetivos (separados por ciclos) com base em seus resultados-chaves (KRs);
        - [x] Kanbam (VueJS) para gestão de tarefas vinculadas aos seus KRs;
        - [x] Transparência entre a equipe, facilitando a ajuda entre os membros;
        - [x] Feedbacks individuais entre a equipe e seus líderes;
        - [x] Painel de elogios, com múltiplos adjetivos e funcionalidade semelhantes as redes sociais (likes e
          comentários da equipe);
        - [x] Relatório baseado nas iniciativas, podendo ser filtrado por diretoria, setor, usuário e seus respectivos
          KRs;
        - [x] Dashboard com resumo dos dados do usuário logado + dados gerais do andamento das metas da empresa como um
          todo;
        - [ ] _(em andamento)_ Dashboard comparativo entre filiais da empresa e ranking de meta das mesmas;
    - 👨‍💻 Resumo técnico: criei este software baseando-o no modelo _multi tenant_ em _multi database._ Ao cadastrar um
      cliente na base principal, automaticamente é criado um novo `Schema` na base de dados e um novo subdomínio. No
      painel do cliente, ele pode criar uma ou mais filiais e vincular seus funcionários a elas. Apesar de cada empresa
      possuir seu banco de dados, em seu painel há ainda uma subdivisão de acesso por filial, ou seja, o modelo de
      _multi tenant_ em _single database_. Em suma, além de cada empresa possuir sua base independente de outra, ela
      ainda conta com a vantagem de poder cadastrar e mensurar as metas de suas filiais. Toda atualização dos _tenants_
      é automatizada por linha de comando sem a necessida de verificação e atualização manual das bases de dados.
    - 🔨 Tecnologias utilizadas: Git (usando GitFlow pra separar as features em desenvolvimento da branch principal)
      PHP (Laravel), JS (mix entre JS puro, jQuery e VueJs), CSS (SCSS com Bootstrap) e DB relacional.

2. **Residente:**
    - 🔗 Links:
        - 🏢 Site Comercial < https://residente.com.br >
        - 💻 Sistema < https://ceplastica.residente.com.br >
    - 💼 Descrição: sistema (patenteado) de controle de procedimentos cirúrgicos realizados por residentes da área da
      medicina e medicina veterinária;
    - 🧩 Funcionalidades:
        - [x] Registro com imagens das etapas cirúrgicas dos pacientes e informações como intercorrências (por etapa) e
          o acompanhamento pós operatório (consultas de retorno com a descrição do resumo da consulta, cadastro de
          complicações e imagens);
        - [x] Registro de feedbacks de professores e diretores aos residentes;
        - [x] Cadastro de RNCs (Registro de Não Conformidade);
        - [x] Avaliação de professores e diretores por procedimento cirúrgico;
        - [x] Avaliação de residentes em relação aos seus superiores;
        - [x] Relatório geral de cirurgias realizadas e relatório por médico residente.
    - 👨‍💻 Resumo técnico: quando comecei a trabalhar neste projeto, o mesmo já havia sido iniciado por outro
      desenvolvedor. Os cadastros básicos como Usuário, paciente, procedimentos e etc estavam quase todos finalizados. O
      que implementei foi o módulo das etapas cirúrgicas, retornos de consulta, relatórios e etc. Em breve, este sistema
      receberá a atualização para a estrutura de _multi tenant_ em _multi database_.
    - 🔨 Tecnologias utilizadas: Git (usando GitFlow pra separar as features da branch principal) PHP (Laravel), JS (mix
      entre JS puro e jQuery), CSS (SCSS com Tailwindcss) e DB relacional.

3. **ADXMail:**
    - 🔗 Links:
        - 💻 Sistema < descontinuado >
    - 💼 Descrição: sistema usado internamente para montar **layout de email de e-commerces** e exportar seu HTML direto
      para a ferramenta de email marketing (RD Station, Active Campaign e etc);
    - 🧩 Funcionalidades:
        - [x] Criação de template (manualmente) de acordo com o modelo passado pelo designer da empresa;
        - [x] Busca de dados no **XML Google Merchant/Shopping** do e-commerce do cliente;
        - [x] Criação do layout do email baseado no template desenvolvido e nos produtos selecionados;
        - [x] Histórico de layouts criados de acordo com o cliente selecionado e código HTML gerado para inserir nas
          ferramentas de disparo.
    - 👨‍💻 Resumo técnico: apesar da dificuldade em trabalhar com front-end, consegui "me virar" com esse sistema. Para
      me ajudar na parte de montar o template do email, usei o editor de texto [TinyMCE](https://www.tiny.cloud/) e
      ensinei a equipe a manusea-lo. Eu mesmo apenas montava os templates com o editor HTML e a inserção de produtos
      ficava por conta do time. Fiz a instalação de um sistema gerenciador de arquivos
      da [UniSharp](https://unisharp.github.io/laravel-filemanager/) e lá fazíamos os uploads das imagens de fundo,
      banners específicos para os emails promocionais e qualquer outra imagem relacionada ao template daquele cliente.
      Diariamente era executada uma CRON que buscava os dados do XML das lojas, armazenava no banco somente os dados que
      seriam usados (link da imagem do produto, valor, valor promocional e link do produto na loja) e então a equipe que
      montava o layout apenas selecionava o template, os produtos e o HTML era gerado. Todos os emails ficavam salvos,
      mantendo assim o histórico de criação.
    - 🔨 Tecnologias utilizadas: Git (usando GitFlow pra separar as features da branch principal) PHP (Laravel), JS (mix
      entre JS puro e jQuery), CSS (SCSS com Bootstrap) e DB relacional.

4. **Rclip Memórias:**
    - 🔗 Links:
        - 💻 Sistema < usado internamente >
    - 💼 Descrição: sistema de armazenamento de campanhas promocionais/institucionais legadas.
    - 🧩 Funcionalidades:
        - [x] Criação de diretórios + upload e exclusão dos arquivos e pastas.
    - 👨‍💻 Resumo técnico: aqui foi onde eu aprendi um pouco mais sobre recursividade. O dono da agência na época me
      pediu pra desenvolver este sistema para que ele pudesse fazer o upload dos arquivos de promoções antigas dos
      clientes. Até aqui, OK! Porém, uma das exigências era que ___"assim como o visual na web iria mostrar o nome de
      uma pasta/diretório com seus arquivos, isso deveria estar refletindo a hierarquia de pastas no servidor."___
      Então a partir daí aprendi recursividade. A única funcionalidade que não foi implementada foi a de "editar nome de
      diretório", já que o servidor disponibilizado para esta aplicação era uma REVENDA! Rsrs...
    - 🔨 Tecnologias utilizadas: Git, PHP (Laravel), JS (mix entre JS puro e jQuery), CSS (LESS com Bootstrap) e DB
      relacional.

### ⭐ Repositórios

Repositórios de cursos e entrevistas feitos por mim ao longo do tempo

<a href="https://github.com/gabrielmath/address-list">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=address-list&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/ecommerce_tallstack">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=ecommerce_tallstack&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/teste_menu_infinito">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=teste_menu_infinito&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/exercicio_img_docker_laravel_devops">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=exercicio_img_docker_laravel_devops&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/pwa">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=pwa&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/rocketseat-backend">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=rocketseat-backend&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/rocketseat-frontend">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=rocketseat-frontend&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/larablog">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=larablog&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/ci_doctrine_twig">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=ci_doctrine_twig&theme=tokyonight" />
</a>
<a href="https://github.com/gabrielmath/painelci">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=gabrielmath&repo=painelci&theme=tokyonight" />
</a>

### 🖥 Sites Comercias

Listagem de sites que desenvolvi enquanto trabalhava em agência de publicidade ou freelas.
**Aqui varia entre PHP puro, Wordpress (com [ElementorPRO](https://elementor.com/))
, [Codeigniter](https://codeigniter.com/) e Laravel**

- [Instituto Davantel](https://institutodavantel.com.br)
- [Alphamaster Colchões](https://alphamastercolchoes.com.br/)
- [Fosferpet](https://www.fosferpet.com.br/)
- [Grupo Athia](http://grupoathia.com/index.php)
- [Hidraumais](http://hidraumais.com.br/)

Aqui deixei somente os links de sites que ainda permanecem com o visual de quando eu desenvolvi pela agência (lembrando
que eu não sou designer, mas me esforço, afinal houve evolução com o tempo).

### 📚 Assinaturas / Cursos

Segue abaixo lista de sites de cursos que sou assinante ou que comprei em algum momento

- [EspecializaT.I](https://academy.especializati.com.br/) - Foco em Laravel, microsserviços e VueJS;
- [Code.Education](https://code.education/) - Foco em sistemas PHP com Laravel;
- [FullCycle](https://fullcycle.com.br/) - Foco em microsserviços e arquitetura de software (DDD, Clean Architeture,
  SOLID, Hexagonal Architeture, Clean Code);
- [School of Net](https://www.schoolofnet.com/) - Diversos mini-cursos nas mais diversas tecnologias
- [Upinside](https://www.upinside.com.br/) - Faço parte da turma do curso **Agência de Valor**

---

### ⚡ OBSERVAÇÕES:
Os gráficos abaixo não refletem os projetos citados acima e a quantidade real de projetos realizados, 
pois a grande maioria dos quais participei estão em outros serviços de versionamento de código (Gitlab e Bitbucket) em
repositórios privados, devido as cláusulas de _NDA ("Non-Disclosure Agreement" - confidencialidade com o cliente)_, os quais não permite que eu apresente o código.


Se interessou? **Então vamos tomar um café e falar de negócios** 😎

Me chama no [Linkedin](https://www.linkedin.com/in/gabriel-matheus-silva-9a19a086/) 😉

---
<div>
<img height="150em" src="https://github-readme-stats.vercel.app/api?username=gabrielmath&show_icons=true&theme=tokyonight&locale=pt-br"/>

<img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs?username=gabrielmath&show_icons=true&theme=tokyonight&layout=compact&locale=pt-br"/>
</div>

---
