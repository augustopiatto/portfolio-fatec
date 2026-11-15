<h1 align="center">🚀 API 6º Semestre - 02/2026</h1>

<p align="center">
  <a href="https://github.com/Pragma-Co/indice" target="_blank">
    <img src="https://img.shields.io/badge/🔗 Repositório-555555?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

<p align="center">
  🎓 <strong>Parceiro Acadêmico:</strong><br>
  FATEC São José dos Campos - Prof. Jessen Vidal <br><br>
  🤝 <strong>Empresa Parceira:</strong><br>
  Akaer
</p>

---

## 📌 Resumo do Projeto

> Desenvolvimento da plataforma **Índice** para a Akaer. A solução tem como objetivo otimizar a busca e o acesso a documentos e normas técnicas da empresa, que atualmente se encontram dispersos em um sistema onde os usuários consomem muito tempo até encontrar o documento que realmente atende sua demanda — muitas vezes sendo necessário ler páginas de diversos arquivos antes de identificar o correto. Por meio do uso de Inteligência Artificial e Machine Learning, o Índice estabelece correlações entre a pesquisa do usuário e os documentos que possam corresponder ao desejado, agilizando e tornando mais precisa a localização da informação. A plataforma conta com tela de pesquisa (campo textual e filtros pré-determinados), fluxo de upload de documentos em três etapas, listagens de documentos do usuário e do sistema, visualização de detalhes com controle de permissão de acesso, fluxo de nova revisão de documentos e telas administrativas para controle de permissões e de usuários. Dessa forma, além de acelerar a consulta, o Índice garante segurança e autorização no acesso aos documentos, permitindo que perfis autorizados decidam quem pode visualizar cada documento e estabeleçam a relação entre as áreas da empresa, apoiando a gestão documental e a tomada de decisão.

---

## ⚠️ Problema

> A Akaer possui um sistema com diversos documentos e normas que seus usuários podem acessar. O problema atual está no tempo que os clientes demoram realizando buscas até chegar aos documentos que realmente precisam — muitas vezes é necessário ler páginas de diversos documentos até descobrir se aquele é o documento que vai atender sua demanda. Além disso, hoje os documentos não possuem segurança e autorização para serem visualizados, o que pode acarretar em problemas de segurança.

---

## 💡 Solução

> Utilizando IA e machine learning, o sistema **Índice** monta correlações entre a pesquisa do usuário e os documentos que possam corresponder ao desejado. A plataforma dispõe de:
>
> - Uma **tela de pesquisa** com campo de pesquisa textual e filtros pré-determinados;
> - Um **fluxo de upload de documentos**;
> - **Login com diferentes perfis de usuário**, de forma que alguns perfis possam controlar os demais e decidir níveis de autorização (quem pode ver qual documento) e a relação entre as áreas da empresa.

---

## 🛠 Tecnologias Adotadas

<p>
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</p>

- **Vue 3 (JavaScript)**: Framework web utilizado para construir o frontend da plataforma, com foco na interatividade das telas de pesquisa, listagens e visualização de documentos.
- **Vite**: Ferramenta de build e servidor de desenvolvimento utilizada no frontend, proporcionando maior velocidade no desenvolvimento e no carregamento da aplicação.
- **Vitest**: Framework de testes utilizado no frontend para garantir a qualidade dos componentes e da lógica da interface.
- **Django**: Framework web em Python utilizado no backend para desenvolvimento da API, responsável pela lógica de negócio, autenticação, controle de permissões e gerenciamento dos documentos.
- **Pytest**: Framework de testes utilizado no backend para validação das regras de negócio e dos endpoints da API.
- **PostgreSQL**: Banco de dados relacional utilizado para armazenar os dados estruturados da plataforma, como usuários, permissões e metadados dos documentos.
- **MongoDB**: Banco de dados NoSQL utilizado para armazenar os documentos e conteúdos não estruturados, apoiando a busca e a correlação feita pela IA.
- **Docker**: Plataforma de containerização utilizada para padronizar o ambiente de desenvolvimento e facilitar o deploy da aplicação.
- **Figma**: Ferramenta de design utilizada para prototipação e validação da interface com o cliente.
- **Git**: Sistema de controle de versionamento distribuído utilizado para gerenciar o código-fonte do projeto, permitindo rastreamento de alterações, trabalho em paralelo por meio de branches e colaboração eficiente entre os membros da equipe.
- **GitHub**: Plataforma de hospedagem de repositórios Git utilizada para armazenar o código-fonte do projeto, gerenciar issues, pull requests e revisões de código, além de possibilitar o acompanhamento do progresso da equipe.

---

## 👨‍💻 Contribuições Individuais

Atuei como **desenvolvedor full-stack** neste projeto, contribuindo tanto no frontend quanto no backend, além de realizar **code review** constante das entregas do time. Minha atuação foi fundamental para garantir a qualidade do código, a consistência visual da plataforma e a segurança no acesso aos documentos.

<details>
  <summary>🔐 <b>Permissionamento de Documentos</b></summary>
  <br>
  Atuei na implementação do permissionamento dos documentos, contemplando os níveis <b>público</b>, <b>confidencial</b> e <b>sigiloso</b>, garantindo que cada usuário visualize apenas os documentos aos quais tem direito de acesso.
</details>

<details>
  <summary>📄 <b>Visualização e Detalhes do Documento</b></summary>
  <br>
  Implementei a tela de detalhes do documento e a funcionalidade de visualização de arquivos nos formatos PDF, DOCX e JPEG diretamente na plataforma, condicionada à permissão de acesso do usuário.
</details>

<details>
  <summary>🔒 <b>Segurança da Informação</b></summary>
  <br>
  Implementei logs de segurança para registrar tentativas de cópia, impressão e outras ações indevidas sobre os documentos. Também realizei a anonimização do usuário no momento da deleção da conta, preservando a privacidade dos dados.
</details>

<details>
  <summary>🔍 <b>Busca e Resultados</b></summary>
  <br>
  Montei a tela inicial de busca (filtragem simples) e o front do sumário da tela de resultados. Também criei o endpoint de filtros e melhorei a lógica do resumo gerado por IA sobre os resultados e termos pesquisados.
</details>

<details>
  <summary>⭐ <b>Funcionalidades do Usuário</b></summary>
  <br>
  Desenvolvi o front das notificações, da solicitação de acesso a documentos, da tela de favoritos e da tela de perfil do usuário.
</details>

<details>
  <summary>🔧 <b>Ajustes Técnicos e Infraestrutura</b></summary>
  <br>
  Realizei ajustes de chamadas duplicadas, correção de padrões incorretos de endpoints, implementação de endpoints faltantes e correção de rotas do frontend. Também ampliei as informações da seed que popula o banco vazio do projeto, facilitando os testes e a validação da aplicação.
</details>

<details>
  <summary>🎨 <b>Melhorias Visuais e de UX</b></summary>
  <br>
  Realizei ajustes e sugestões de melhorias visuais e de experiência do usuário (UX) na plataforma, contribuindo para uma interface mais intuitiva e agradável.
</details>

<details>
  <summary>🔀 <b>Code Review</b></summary>
  <br>
  Atuei constantemente na revisão de código do time, garantindo qualidade, padronização e boas práticas de desenvolvimento.
</details>

---

## ⚙️ Funcionamento

A plataforma **Índice** possui **três níveis de acesso**, que definem o que cada usuário pode visualizar e executar:

- **Admin**: responsável pela administração geral da plataforma;
- **Gestor**: responsável pela gestão dos documentos e colaboradores da sua área;
- **Autor**: responsável pelo upload e gerenciamento dos documentos que produz.

Abaixo estão descritas as telas e fluxos da plataforma, indicando quais perfis têm acesso a cada um.

### Tela de Início (Pesquisa Simples)

Acessível a **gestor** e **autor**. Permite realizar filtros por data, área, tipo de documento e termo de busca. Para o perfil **autor**, a tela também exibe atalhos para o fluxo de upload de arquivos e para a listagem de documentos.

### Fluxo de Upload

Acessível ao **autor**. O usuário adiciona documentos nos formatos **PDF, DOCX, JPEG ou PNG**. A IA faz uma sugestão de disciplina, tipo de documento e áreas relacionadas ao arquivo, e o usuário deve preencher:

- Projeto associado;
- Título;
- Descrição;
- Confidencialidade do documento (**público**, **confidencial** ou **sigiloso**).

Para documentos **confidenciais**, é possível relacionar **grupos de acesso** que poderão visualizá-lo. Para documentos **sigilosos**, devem ser selecionados **usuários específicos** da base para permitir a visualização. Por fim, o usuário pode modificar as sugestões feitas pela IA.

### Tela de Resultados

Acessível a **gestor** e **autor**. Possui filtros avançados por tipo de documento, área, disciplina, status, data de emissão e termo de busca. Quando há uso de termo de busca, a tela exibe um **resumo gerado por IA** sobre os resultados e os termos pesquisados. Os resultados exibidos variam conforme o nível de acesso do usuário logado (documentos públicos, confidenciais ou sigilosos). Nesta tela, o usuário pode:

- **Favoritar** documentos (que passam a aparecer na tela de favoritos);
- **Solicitar uma nova revisão** do documento.

### Tela de Detalhes do Documento

Acessível a **gestor** e **autor**. Permite visualizar os detalhes do documento, sua imagem e documentos relacionados (por projeto, disciplina ou área). A tela exibe o **histórico de versões** do documento e permite solicitar uma nova revisão. Por se tratar de dados sensíveis, a tela **impede** que o usuário tire print, faça download ou compartilhe o documento. Dependendo do grupo de acesso ou da área do usuário, ele pode estar restrito de visualizar os detalhes e, nesse caso, pode **solicitar acesso ao gestor**, que verá o pedido na tela de revisões.

### Tela de Favoritos

Acessível a **gestor** e **autor**. Exibe os documentos que foram favoritados pelo usuário na tela de resultados.

### Tela de Documentos

Acessível ao **autor**. Exibe os documentos que foram enviados (upload) pelo próprio usuário.

### Notificações

Acessível a **gestor** e **autor**. Localizada na barra de navegação, exibe notificações relacionadas às atualizações dos documentos aos quais o usuário tem acesso, como novas revisões, acessos e aprovações. Ao clicar em uma notificação, o usuário é levado ao respectivo documento.

### Tela de Perfil

Acessível a **gestor** e **autor**. Exibe as informações do usuário logado e permite:

- Alterar nome, sobrenome e e-mail;
- Solicitar a exclusão da conta;
- Consultar o histórico de termos de adesão.

### Tela de Revisões

Acessível ao **gestor**. Possui **três abas**:

1. **Revisões técnicas pendentes**: exibe os documentos da área sob responsabilidade do gestor que estão aguardando aprovação da mudança de arquivo;
2. **Pedidos de acesso a documentos restritos**: exibe os documentos da área sob responsabilidade do gestor que estão aguardando acesso por parte de um usuário autor;
3. **Histórico**: exibe o histórico de alterações realizadas nas outras duas abas.

### Tela de Colaboradores

Acessível ao **gestor**. Exibe os autores pertencentes à sua área e permite realizar edições nesses autores.

### 🎬 Demonstração dos Fluxos

<details>
<summary>Clique para ver o vídeo do fluxo da visão de autor</summary>
<br>
<p align="center">
  <video src="" controls width="600"></video>
</p>
</details>

<details>
<summary>Clique para ver o vídeo do fluxo da visão de gestor</summary>
<br>
<p align="center">
  <video src="" controls width="600"></video>
</p>
</details>

---

## 📚 Aprendizados Efetivos

A atuação no projeto **Índice** tem proporcionado experiência prática em um ambiente corporativo real, com a parceira Akaer, envolvendo o desenvolvimento full-stack de uma plataforma com uso de Inteligência Artificial e Machine Learning para busca e correlação de documentos. O projeto tem aprofundado conhecimentos em segurança da informação, controle de permissões e experiência do usuário, além de reforçar a importância do code review e das boas práticas de desenvolvimento.

### 🧠 Hard Skills

<table align="center">
    <tr>
      <th width="270px">Tecnologia/Metodologia</th>
      <th width="85px">Nota</th>
      <th width="200px">Classificação</th>
    </tr>
   <tr>
    <td>Vue.js</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Django</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Git</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>PostgreSQL</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>JavaScript</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Vitest</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Pytest</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Figma</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Vite</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>MongoDB</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>Docker</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
</table>

---

### 🤝 Soft Skills

<table align="center">
    <tr>
      <th width="270px">Habilidade</th>
      <th width="280px">Descrição</th>
    </tr>
    <tr>
      <td>Trabalho em Equipe</td>
      <td>Colaborei ativamente com o time de desenvolvimento por meio de code reviews e sugestões de melhorias de UI, UX e arquitetura de código. Prestei auxílio rápido aos colegas, evitando atrasos e gargalos nas entregas do time.</td>
    </tr>
    <tr>
      <td>Comunicação</td>
      <td>Mantive alinhamento contínuo com os membros da equipe durante dailies e reuniões, esclarecendo dúvidas com o Product Owner, deixando claros os prazos a serem atingidos e as dependências entre tarefas, garantindo um fluxo de entrega contínuo.</td>
    </tr>
    <tr>
      <td>Resolução de Problemas</td>
      <td>Atuei na solução de gargalos técnicos que impactavam o ritmo dos demais membros, além de realizar otimizações de performance na plataforma.</td>
    </tr>
    <tr>
      <td>Proatividade e Iniciativa</td>
      <td>Antecipei necessidades do time e do projeto, sugerindo melhorias visuais, de usabilidade e de arquitetura antes mesmo que se tornassem problemas, além de me colocar à disposição para apoiar colegas em suas demandas.</td>
    </tr>
</table>

---

## 🔎 Navegação entre Projetos

* [1º Semestre: Calculadora Científica](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-1-semestre.md)
* [2º Semestre: Avaliador de Soft Skill](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-2-semestre.md)
* [3º Semestre: Sistema de Ponto e Geração de Relatórios](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-3-semestre.md)
* [4º Semestre: Monitoramente e resposta a Incidentes](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-4-semestre.md)
* [5º Semestre: Data Warehouse sobre Dados Operacionais da Empresa Parceira](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-5-semestre.md)
* [6º Semestre: Sistema Inteligente de Gestão e Consulta de Documentos Técnicos](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-6-semestre.md)

---

<p align="center">
  ✨ Desenvolvido durante a graduação em Banco de Dados
</p>
