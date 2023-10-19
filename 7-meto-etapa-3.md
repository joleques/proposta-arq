# Análise de Casos de Uso

A terceira etapa do processo de desenvolvimento de software é a "Análise de Casos de Uso". Nesta fase, a equipe se concentra em detalhar e compreender as diferentes ações e interações que o software deve suportar. Essas ações são representadas por meio de casos de uso, que descrevem como os usuários irão interagir com o software para alcançar seus objetivos. Os casos de uso ajudam a traduzir os requisitos funcionais em cenários práticos e fornecem uma visão mais concreta das funcionalidades que o software precisa oferecer.

Durante a análise de casos de uso, a equipe identifica os fluxos de interação entre o usuário e o sistema, definindo passo a passo como as tarefas serão realizadas. Isso inclui a entrada de dados, a resposta do sistema e as condições de exceção, proporcionando uma visão detalhada das operações do software. A análise de casos de uso também permite a identificação de possíveis lacunas ou ambiguidades nos requisitos, o que é essencial para garantir a integridade e a precisão do sistema.

Uma vez que os casos de uso tenham sido definidos e analisados, eles servem como base para o desenvolvimento posterior. Eles ajudam os desenvolvedores a entender o comportamento esperado do software e a criar um design que atenda às necessidades dos usuários. Além disso, os casos de uso são uma ferramenta valiosa para validar o software junto ao cliente, pois eles representam situações reais de uso que podem ser revisadas e aprovadas.

Em resumo, a terceira etapa do desenvolvimento de software, a análise de casos de uso, desempenha um papel fundamental na tradução dos requisitos em cenários práticos e na definição das interações entre o usuário e o sistema. Isso contribui para uma compreensão mais clara do que o software precisa fazer e facilita o desenvolvimento subsequente, garantindo que o produto final atenda às expectativas do cliente.

A seguir, um diálogo entre a equipe de desenvolvimento e o cliente com o objetivo de entender os casos de uso.

***Cliente:*** Olá, equipe de desenvolvedores! Estamos empolgados para começar a trabalhar na nossa aplicação de gerenciamento de APIs fictícias com base nos requisitos atualizados. Vamos discutir os casos de uso em detalhes.

***Desenvolvedor 1:*** Claro, estamos aqui para ajudar. Por favor, siga em frente.

***Cliente:*** Ótimo. Primeiramente, os usuários poderão cadastrar uma Web Hooks Fakes. Precisamos coletar informações como nome, alias e descrição durante o cadastro.

***Desenvolvedor 2:*** Anotado. E quanto à edição de APIs já existentes, quais campos devem ser editáveis?

***Cliente:*** Todos os campos devem ser editáveis, com a exceção do alias, que deve permanecer único e inalterável.

***Desenvolvedor 3:*** Entendi. E em relação à exclusão de APIs, existem restrições ou autorizações específicas necessárias para excluir uma API?

***Cliente:*** Não é necessario.

***Desenvolvedor 1:*** Perfeito. Agora, para a definição do conteúdo e código de status da resposta da Web Hooks Fakes, os usuários podem especificar essas informações por solicitação, correto?

***Cliente:*** Exato, os usuários devem ser capazes de definir o corpo da resposta e o código de status HTTP.

***Desenvolvedor 2:*** Ótimo. E em relação à lista de todas as APIs cadastradas, você deseja algum filtro ou classificação específica para exibi-las?

***Cliente:*** Apenas uma lista simples por enquanto.

***Desenvolvedor 3:*** Entendido. E para a busca de informações sobre uma API específica, é necessário que o usuário conheça o alias dessa API, correto?

***Cliente:*** Sim, apenas com o alias será possível encontrar informações sobre uma API específica.

Agora, passando para os requisitos do Relatório de Interação:

***Desenvolvedor 1:*** Os usuários podem buscar um relatório contendo todas as Interação realizadas pelos consumidores da API cadastrada, certo?

***Cliente:*** Sim, isso mesmo. O relatório deve incluir informações como data e hora da chamada, IP do consumidor, endpoint da API chamada e o resultado da chamada.

***Desenvolvedor 2:*** Perfeito. E quanto à busca de um registro específico no relatório, os usuários podem pesquisar pelo IP do consumidor ou pelo endpoint da API chamada, correto?

***Cliente:*** Exatamente.

***Desenvolvedor 3:*** Serviços poderão consumir a Web Hooks Fakes. Precisamos adicionar autenticação e autorização para os serviços que desejam consumir a Web Hooks Fakes, correto?

***Cliente:*** Não precisa por enquanto.

***Desenvolvedor 1:*** Ótimo, estamos alinhados com os requisitos. Vamos começar a trabalhar e manteremos você atualizado ao longo do processo. Se tiver mais alguma pergunta ou precisar de esclarecimentos adicionais, não hesite em entrar em contato. Estamos aqui para ajudar.

Com base no diálogo, aqui estão os casos de uso levantados para a aplicação de gerenciamento de APIs fictícias:

## Casos de Uso para gestão da Web Hooks Fakes:

### Cadastrar Web Hooks Fakes:
- Ator: Usuário
- Descrição: O usuário pode cadastrar uma nova Web Hooks Fakes com informações como nome, alias e descrição.

### Editar Web Hooks Fakes:
- Ator: Usuário
- Descrição: O usuário pode editar todos os campos de uma Web Hooks Fakes já existente, exceto o alias, que deve permanecer único e inalterável.

### Excluir Web Hooks Fakes:
- Ator: Usuário
- Descrição: O usuário pode excluir uma Web Hooks Fakes, sem restrições ou autorizações específicas.

### Listar Todas as APIs Cadastradas:
- Ator: Usuário
- Descrição: O usuário pode acessar uma lista simples de todas as APIs fictícias cadastradas.

### Buscar Informações sobre uma API Específica:
- Ator: Usuário
- Descrição: O usuário pode buscar informações sobre uma Web Hooks Fakes específica, desde que conheça o alias dessa API.

## Casos de Uso para o Relatório de Interação:

### Buscar Relatório de Interação:
- Ator: Usuário
- Descrição: O usuário pode buscar um relatório contendo todas as Interação realizadas pelos consumidores da API cadastrada, com informações como data e hora da chamada, IP do consumidor, endpoint da API chamada e o resultado da chamada.

### Buscar Registro Específico no Relatório:
- Ator: Usuário
- Descrição: O usuário pode buscar um registro específico no relatório da API cadastrada, com base no IP do consumidor ou no endpoint da API chamada.

## Casos de Uso para o Consumo de API:

### Consumir Web Hooks Fakes:
- Ator: Serviço
- Descrição: Serviços podem consumir a Web Hooks Fakes. Não é necessária autenticação ou autorização para o consumo no momento.

Esses são os casos de uso levantados com base no diálogo atualizado, cobrindo o CRUD da Web Hooks Fakes, o relatório de Interação e o consumo de API por serviços. Eles servirão como guia para o desenvolvimento da aplicação.

- [Voltar](7-metodologia.md)