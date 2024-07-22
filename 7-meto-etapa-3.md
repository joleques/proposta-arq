# Análise de Casos de Uso

A terceira etapa do processo de desenvolvimento de software é a "Análise de Casos de Uso". Nesta fase, a equipe se concentra em detalhar e compreender as diferentes ações e interações que o software deve suportar. Essas ações são representadas por meio de casos de uso, que descrevem como os usuários irão interagir com o software para alcançar seus objetivos. Os casos de uso ajudam a traduzir os requisitos funcionais em cenários práticos e fornecem uma visão mais concreta das funcionalidades que o software precisa oferecer.

Durante a análise de casos de uso, a equipe identifica os fluxos de interação entre o usuário e o sistema, definindo passo a passo como as tarefas serão realizadas. Isso inclui a entrada de dados, a resposta do sistema e as condições de exceção, proporcionando uma visão detalhada das operações do software. A análise de casos de uso também permite a identificação de possíveis lacunas ou ambiguidades nos requisitos, o que é essencial para garantir a integridade e a precisão do sistema.

À medida que os casos de uso são analisados, surgem histórias de usuário, que são descrições de funcionalidades do ponto de vista do usuário final. Cada história de usuário segue um formato simples e claro, geralmente estruturado da seguinte maneira: "Como [tipo de usuário], eu quero [ação] para [benefício/resultado desejado]." Isso ajuda a capturar as necessidades e expectativas dos usuários de forma compreensível e orientada a objetivos.

O aprofundamento desses casos de uso gera cenários de testes dessas histórias. Um cenário de teste é uma descrição detalhada de uma situação específica em que o software será usado, incluindo as condições iniciais, os passos que serão seguidos e os resultados esperados. Esses cenários de testes são essenciais para validar se o software atende aos requisitos especificados e se comporta conforme o esperado em diversas situações. Os cenários de testes se transformam, posteriormente, em testes funcionais, que verificam se cada função do software está operando conforme o esperado.

Além disso, algumas histórias de usuário podem se enquadrar em testes de produto. Os testes de produto são responsáveis por validar a integração e interação entre todos os serviços e componentes que compõem o produto final. Eles garantem que o sistema como um todo funcione de maneira adequada e atenda aos requisitos e expectativas globais do usuário. Embora em menor quantidade em comparação com os testes de unidades e casos de uso, os testes de produto são essenciais para garantir a funcionalidade completa e a qualidade geral do produto entregue.

Uma vez que os casos de uso tenham sido definidos e analisados, eles servem como base para o desenvolvimento posterior. Eles ajudam os desenvolvedores a entender o comportamento esperado do software e a criar um design que atenda às necessidades dos usuários. Além disso, os casos de uso são uma ferramenta valiosa para validar o software junto ao cliente, pois eles representam situações reais de uso que podem ser revisadas e aprovadas.

Em resumo, a terceira etapa do desenvolvimento de software, a análise de casos de uso, desempenha um papel fundamental na tradução dos requisitos em cenários práticos e na definição das interações entre o usuário e o sistema. Isso contribui para uma compreensão mais clara do que o software precisa fazer e facilita o desenvolvimento subsequente, garantindo que o produto final atenda às expectativas do cliente.

A seguir, um diálogo entre a equipe de desenvolvimento e o cliente com o objetivo de entender os casos de uso, seguido pela identificação das histórias de usuário e os cenários de testes.

---

***Cliente:*** Olá, equipe de desenvolvedores! Estamos empolgados para começar a trabalhar na nossa aplicação de gerenciamento de APIs fictícias com base nos requisitos atualizados. Vamos discutir os casos de uso em detalhes.

***Desenvolvedor 1:*** Claro, estamos aqui para ajudar. Por favor, siga em frente.

***Cliente:*** Ótimo. Primeiramente, os usuários poderão cadastrar uma Web Hooks Fakes. Precisamos coletar informações como nome, alias e descrição durante o cadastro.

***Desenvolvedor 2:*** Anotado. E quanto à edição de APIs já existentes, quais campos devem ser editáveis?

***Cliente:*** Todos os campos devem ser editáveis, com a exceção do alias, que deve permanecer único e inalterável.

***Desenvolvedor 3:*** Entendi. E em relação à exclusão de APIs, existem restrições ou autorizações específicas necessárias para excluir uma API?

***Cliente:*** Não é necessário.

***Desenvolvedor 1:*** Perfeito. Agora, para a definição do conteúdo e código de status da resposta da Web Hooks Fakes, os usuários podem especificar essas informações por solicitação, correto?

***Cliente:*** Exato, os usuários devem ser capazes de definir o corpo da resposta e o código de status HTTP.

***Desenvolvedor 2:*** Ótimo. E em relação à lista de todas as APIs cadastradas, você deseja algum filtro ou classificação específica para exibi-las?

***Cliente:*** Apenas uma lista simples por enquanto.

***Desenvolvedor 3:*** Entendido. E para a busca de informações sobre uma API específica, é necessário que o usuário conheça o alias dessa API, correto?

***Cliente:*** Sim, apenas com o alias será possível encontrar informações sobre uma API específica.

Agora, passando para os requisitos do Relatório de Interação:

***Desenvolvedor 1:*** Os usuários podem buscar um relatório contendo todas as interações realizadas pelos consumidores da API cadastrada, certo?

***Cliente:*** Sim, isso mesmo. O relatório deve incluir informações como data e hora da chamada, IP do consumidor, endpoint da API chamada e o resultado da chamada.

***Desenvolvedor 2:*** Perfeito. E quanto à busca de um registro específico no relatório, os usuários podem pesquisar pelo IP do consumidor ou pelo endpoint da API chamada, correto?

***Cliente:*** Exatamente.

***Desenvolvedor 3:*** Serviços poderão consumir a Web Hooks Fakes. Precisamos adicionar autenticação e autorização para os serviços que desejam consumir a Web Hooks Fakes, correto?

***Cliente:*** Não precisa por enquanto.

***Desenvolvedor 1:*** Ótimo, estamos alinhados com os requisitos. Vamos começar a trabalhar e manteremos você atualizado ao longo do processo. Se tiver mais alguma pergunta ou precisar de esclarecimentos adicionais, não hesite em entrar em contato. Estamos aqui para ajudar.

---

Com base no diálogo, aqui estão os casos de uso levantados para a aplicação de gerenciamento de APIs fictícias, juntamente com as histórias de usuário e cenários de testes:

## Casos de Uso para gestão da Web Hooks Fakes:

### Cadastrar Web Hooks Fakes:
- **Ator:** Usuário
- **Descrição:** O usuário pode cadastrar uma nova Web Hooks Fakes com informações como nome, alias e descrição.

#### História de Usuário:
- **Como** um usuário,
- **Eu quero** cadastrar uma nova Web Hooks Fakes,
- **Para** poder gerenciar notificações automáticas.

#### Cenário de Teste:
- **Dado** que o usuário está na tela de cadastro de Web Hooks Fakes,
- **Quando** ele preencher os campos nome, alias e descrição,
- **Então** a Web Hooks Fakes deve ser cadastrada com sucesso e aparecer na lista de APIs.

### Editar Web Hooks Fakes:
- **Ator:** Usuário
- **Descrição:** O usuário pode editar todos os campos de uma Web Hooks Fakes já existente, exceto o alias, que deve permanecer único e inalterável.

#### História de Usuário:
- **Como** um usuário,
- **Eu quero** editar uma Web Hooks Fakes existente,
- **Para** atualizar suas informações sem alterar o alias.

#### Cenário de Teste:
- **Dado** que o usuário está na tela de edição de Web Hooks Fakes,
- **Quando** ele modificar os campos permitidos (nome e descrição),
- **Então** as mudanças devem ser salvas com sucesso e refletidas na lista de APIs.

### Excluir Web Hooks Fakes:
- **Ator:** Usuário
- **Descrição:** O usuário pode excluir uma Web Hooks Fakes, sem restrições ou autorizações específicas.

#### História de Usuário:
- **Como** um usuário,
- **Eu quero** excluir uma Web Hooks Fakes,
- **Para** remover APIs que não são mais necessárias.

#### Cenário de Teste:
- **Dado** que o usuário está na tela de listagem de Web Hooks Fakes,
- **Quando** ele selecionar uma Web Hooks Fakes e clicar em excluir,
- **Então** a Web Hooks Fakes deve ser removida da lista de APIs.

### Listar Todas as APIs Cadastradas:
- **Ator:** Usuário
- **Descrição:** O usuário pode acessar uma lista simples de todas as APIs fictícias cadastradas.

#### História de Usuário:
- **Como** um usuário,
- **Eu quero** ver uma lista de todas as Web Hooks Fakes cadastradas,
- **Para** poder gerenciá-las facilmente.

#### Cenário de Teste:
- **Dado** que o usuário está na tela principal,
- **Quando** ele acessar a seção de Web Hooks Fakes,
- **Então** ele deve ver uma lista de todas as APIs cadastradas.

### Buscar Informações sobre uma API Específica:
- **Ator:** Usuário
- **Descrição:** O usuário pode buscar informações sobre uma Web Hooks Fakes específica, desde que conheça o alias dessa API.

#### História de Usuário:
- **Como** um usuário,
- **Eu quero** buscar informações sobre uma Web Hooks Fakes específica,
- **Para** ver detalhes sobre sua configuração e status.

#### Cenário de Teste:
- **Dado** que o usuário está na tela de busca,
- **Quando** ele inserir o alias de uma Web Hooks Fakes,
- **Então** as informações detalhadas dessa API devem ser exibidas.

## Casos de Uso para o Relatório de Interação:

### Buscar Relatório de Interação:
- **Ator:** Usuário
- **Descrição:** O usuário pode buscar um relatório contendo todas as interações realizadas pelos consumidores da API cadastrada, com informações como data e hora da chamada, IP do consumidor, endpoint da API chamada e o resultado da chamada.

#### História de Usuário:
- **Como** um usuário,
- **Eu quero** buscar um relatório de interações,
- **Para** monitorar o uso e desempenho das APIs cadastradas.

#### Cenário de Teste:
- **Dado** que o usuário está na tela de relatórios,
- **Quando** ele solicitar o relatório de interações,
- **Então** ele deve ver uma lista detalhada de todas as interações realizadas.

### Buscar Registro Específico no Relatório:
- **Ator:** Usuário
- **Descrição:** O usuário pode buscar um registro específico no relatório da API cadastrada, com base no IP do consumidor ou no endpoint da API chamada.

#### História de Usuário:
- **Como** um usuário,
- **Eu quero** buscar um registro específico no relatório,
- **Para** analisar interações específicas baseadas em critérios como IP ou endpoint.

#### Cenário de Teste:
- **Dado** que o usuário está na tela de relatórios,
- **Quando** ele usar o filtro de IP ou endpoint,
- **Então** ele deve ver os registros específicos que correspondem aos critérios de busca.

## Casos de Uso para o Consumo de API:

### Consumir Web Hooks Fakes:
- **Ator:** Serviço
- **Descrição:** Serviços podem consumir a Web Hooks Fakes. Não é necessária autenticação ou autorização para o consumo no momento.

#### História de Usuário:
- **Como** um serviço,
- **Eu quero** consumir uma Web Hooks Fakes,
- **Para** receber respostas automatizadas conforme configurado.

#### Cenário de Teste:
- **Dado** que o serviço está configurado para consumir uma Web Hooks Fakes,
- **Quando** ele fizer uma solicitação à Web Hooks Fakes,
- **Então** ele deve receber a resposta configurada, incluindo o corpo e o código de status HTTP.

---

Esses são os casos de uso, histórias de usuário e cenários de testes levantados com base no diálogo atualizado, cobrindo o CRUD da Web Hooks Fakes, o relatório de interação e o consumo de API por serviços. Eles servirão como guia para o desenvolvimento da aplicação.

- [Voltar](7-metodologia.md)