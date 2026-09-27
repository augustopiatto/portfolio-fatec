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
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
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
- **Swagger**: Documentação interativa da API, facilitando o entendimento e teste dos endpoints.

---

## 👨‍💻 Contribuições Individuais

Atuo como **desenvolvedor full-stack** neste projeto, contribuindo tanto no frontend quanto no backend, além de realizar **code review** constante das entregas do time. Minha atuação tem sido fundamental para garantir a qualidade do código, a consistência visual da plataforma e a segurança no acesso aos documentos.

<details>
  <summary>📄 <b>Visualização de Documentos</b></summary>
  <br>
  Implementei a funcionalidade de visualização de detalhes do documento, permitindo a exibição de arquivos nos formatos PDF, DOCX e JPEG diretamente na plataforma. A visualização só é exibida caso o usuário tenha permissão de acesso ao documento, garantindo a segurança da informação.
</details>

<details>
  <summary>🎨 <b>Melhorias Visuais e de UX</b></summary>
  <br>
  Realizei ajustes e sugestões de melhorias visuais e de experiência do usuário (UX) na plataforma, contribuindo para uma interface mais intuitiva e agradável.
</details>

<details>
  <summary>🔍 <b>Tela de Filtragem Simples</b></summary>
  <br>
  Montei a tela inicial de filtragem simples, com campo de pesquisa textual e filtros pré-determinados, sendo o ponto de entrada do usuário para a busca de documentos.
</details>

<details>
  <summary>🔀 <b>Code Review</b></summary>
  <br>
  Atuo constantemente na revisão de código do time, garantindo qualidade, padronização e boas práticas de desenvolvimento.
</details>

<details>
  <summary>🚧 <b>Contribuições Futuras (TODO)</b></summary>
  <br>
  Como o projeto ainda está em andamento, novas contribuições estão previstas, com destaque para a atuação na parte de **permissionamento** de usuários e documentos.
</details>

---

## ⚙️ Funcionamento

> ⚠️ *O projeto ainda está em desenvolvimento. As descrições abaixo refletem o que foi planejado pelo time. Imagens e vídeos serão adicionados futuramente, pois muitas telas ainda sofrerão alterações.*

### Tela Inicial e Pesquisa

A tela inicial conta com um campo de pesquisa aberto e filtros simples. Abaixo do campo de busca, é exibido o histórico das últimas mudanças realizadas pelo usuário logado no sistema — geralmente relacionadas ao upload de documentos.

### Fluxo de Upload de Documentos

O upload de documentos é realizado em **três passos**:

1. **Passo 1**: Upload de um ou mais documentos;
2. **Passo 2**: Preenchimento das informações a respeito dos documentos;
3. **Passo 3**: Revisão das informações para conferência antes da conclusão.

### Listagens de Documentos

- **Tela de listagem de documentos do usuário**: exibe todos os documentos que o próprio usuário fez upload;
- **Tela de listagem de documentos do sistema**: exibe todos os documentos disponíveis no sistema.

### Detalhes e Permissões

Ao tentar acessar o detalhe de um documento (em qualquer uma das telas de listagem), a visualização só é exibida caso o usuário tenha permissão de acesso. Caso tenha, ele pode visualizar as imagens e também clicar no botão **"Nova Revisão"**, onde poderá anexar novos documentos para gerar uma nova revisão daquele documento.

### Telas Administrativas

- **Tela de controle de permissões**: acessível apenas por usuários com permissão adequada, permite permitir ou negar a visualização de um usuário a um documento que foi previamente solicitado;
- **Tela de controle de usuários**: permite controlar a área do usuário, bem como ativar ou inativar usuários.

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
   <tr>
    <td>Swagger</td>
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
