# Definição de Linguagem Ubíqua e Contextos de Negócio

A segunda etapa do processo de desenvolvimento de software é a "Definição de Linguagem Ubíqua e Contextos de Negócio". Nessa fase, após o levantamento de requisitos na primeira etapa, a equipe se concentra em estabelecer uma comunicação eficaz entre todos os envolvidos no projeto, incluindo os desenvolvedores e o cliente. Isso é feito através da criação de uma "***linguagem ubíqua***", que consiste em um conjunto de conceitos e terminologias claramente definidos que todos compreendem e utilizam de forma consistente. Essa linguagem unificada ajuda a evitar mal-entendidos e ambiguidades, garantindo que todos falem a mesma língua.

Além disso, na segunda etapa, a equipe explora a fundo o negócio do cliente, fazendo uma distinção entre o "***core***" e os "***contextos auxiliares***". O "***core***" representa a parte mais essencial do serviço ou produto, ou seja, as funcionalidades e características que são críticas para atender aos objetivos principais. Os "***contextos auxiliares***" são aquelas funcionalidades que auxiliam o "***core***" a alcançar seus objetivos, mas não são consideradas tão cruciais. Essa diferenciação é crucial para alinhar as expectativas e direcionar o desenvolvimento de software para o que realmente importa.

Nessa etapa, a equipe trabalha em estreita colaboração com o cliente para definir e documentar esses conceitos, garantindo que haja um entendimento comum sobre o escopo do projeto. A clareza na definição da linguagem ubíqua e na distinção entre o core e os contextos auxiliares ajuda a concentrar os esforços no que é mais importante, economizando tempo e recursos no desenvolvimento subsequente.

Em resumo, a segunda etapa do desenvolvimento de software se concentra na criação de uma ***linguagem compartilhada*** e na definição de conceitos de negócios essenciais, incluindo a distinção entre o core e os contextos auxiliares. Essas ações são cruciais para garantir a compreensão comum e o foco no desenvolvimento do software, alinhando-o às metas e objetivos do cliente.

A seguir, um diálogo entre a equipe de desenvolvimento e o cliente com o objetivo de definir uma linguagem unica.

# Dialogo

- ***Desenvolvedor 1:*** Olá cliente, antes de prosseguirmos com o desenvolvimento da API fictícia, gostaríamos de sugerir a definição de uma linguagem ubíqua para o projeto. Isso nos ajudará a garantir que todos tenham uma compreensão comum dos termos e conceitos que usaremos durante o desenvolvimento. O que acha disso?

- ***Cliente:*** Isso parece uma ótima ideia. Vamos definir essa linguagem comum.

- ***Desenvolvedor 2:*** Ótimo! Comecemos com algo básico. Como gostaria que nos referíssemos aos endpoints fictícios que estamos criando?

- ***Cliente:*** "Web Hooks Fakes" me parece um termo adequado. Reflete bem o propósito de criar pontos de integração falsos para simular os endpoints dos nossos clientes.

- ***Desenvolvedor 1:*** Gostamos da sugestão. "Web Hooks Fakes" é uma escolha clara e precisa. E quanto aos detalhes de cada "Web Hook Fake", como o conteúdo da resposta que pode ser definido?

Cliente:*** Podemos chamar isso de "Especificação de Resposta". Assim, quando falarmos sobre a configuração de um "Web Hook Fake", podemos mencionar a "Especificação de Resposta" que ele deve ter.

- ***Desenvolvedor 2:*** "Especificação de Resposta" soa bem. E o código de status HTTP?

- ***Cliente:*** "Código de Status HTTP" é um termo adequado e amplamente reconhecido.

- ***Desenvolvedor 1:*** Concordamos com "Código de Status HTTP". E quanto aos relatórios de chamadas?

- ***Cliente:*** Podemos chamá-los de "Registro de Interações". Reflete bem a natureza das informações coletadas.

- ***Desenvolvedor 2:*** "Registro de Interações" é uma ótima escolha. E para a lista de todos os "Web Hooks Fakes" configurados?

- ***Cliente:*** "Catálogo de Integrações" parece apropriado. Sugere uma lista organizada de "Web Hooks Fakes".

- ***Desenvolvedor 1:*** Gostamos da ideia de "Catálogo de Integrações". E para buscar informações específicas sobre um "Web Hook Fake"?

- ***Cliente:*** Podemos usar "Consulta de Integração". Isso reflete bem o ato de obter informações detalhadas sobre um "Web Hook Fake" específico.

- ***Desenvolvedor 2:*** Perfeito! Acho que agora temos uma linguagem ubíqua sólida para o projeto. Isso tornará nossas comunicações mais claras e eficazes. Obrigado por considerar nossas sugestões, cliente!


Aqui está o glossário de linguagem ubíqua para o projeto da API fictícia:

- ***Web Hooks Fakes*** - Termo utilizado para se referir aos endpoints fictícios criados para simular os pontos de integração dos clientes.

- ***Especificação de Resposta*** - Refere-se aos detalhes da resposta que pode ser definida para um "Web Hook Fake".

- ***Código de Status HTTP*** - Termo utilizado para descrever o código de status HTTP que indica o resultado de uma solicitação feita a um "Web Hook Fake".

- ***Registro de Interações*** - Usado para se referir aos relatórios que contêm informações sobre as interações que ocorreram com os "Web Hooks Fakes".

- ***Catálogo de Integrações*** - Refere-se a uma lista organizada de todos os "Web Hooks Fakes" configurados no projeto.

- ***Consulta de Integração*** - Termo utilizado para buscar informações detalhadas sobre um "Web Hook Fake" específico, permitindo obter informações específicas sobre ele.

Com este glossário de linguagem ubíqua, todos os membros da equipe terão uma compreensão comum dos termos e conceitos usados durante o desenvolvimento da API fictícia, garantindo uma comunicação mais clara e eficaz no projeto. Após isso começamos a etender os conceitos.

# Dialogo

- ***Desenvolvedor 1:*** Olá equipe, tivemos uma reunião com o cliente e discutimos a criação da API fictícia. O time expressou a necessidade de uma linguagem ubíqua para o projeto e também identificamos dois principais contextos: "Gestão de Web Hooks Fakes" e "Consumo dos Web Hooks Fakes". Vamos discutir e definir os conceitos que capturamos durante a conversa.

- ***Desenvolvedor 2:*** Ótimo, por onde começamos?

- ***Desenvolvedor 3:*** Vamos começar com o "Contexto: Gestão de Web Hooks Fakes". Aqui temos três conceitos fundamentais. O primeiro é "Web Hook Fake". Vamos definir isso.

- ***Desenvolvedor 1:*** Concordo. "Web Hook Fake" refere-se aos endpoints fictícios que criamos para simular os endpoints dos clientes, permitindo testes de integração sem depender dos clientes reais.

- ***Desenvolvedor 2:*** Certo, próximo conceito, "Especificação de Resposta". Vamos esclarecer isso.

- ***Desenvolvedor 3:*** "Especificação de Resposta" diz respeito aos detalhes da resposta que podem ser definidos para um "Web Hook Fake", incluindo o formato da resposta e seu conteúdo.

- ***Desenvolvedor 1:*** Ótimo, agora o último conceito neste contexto, "Código de Status HTTP". Vamos definir isso também.

- ***Desenvolvedor 2:*** Claro. "Código de Status HTTP" indica o código de status HTTP que será incluído na resposta de um "Web Hook Fake" para simular o comportamento da API.

- ***Desenvolvedor 3:*** Excelente, agora, adicionando o conceito de "Interação." O que isso significa?

- ***Desenvolvedor 1:*** "Interação" é o registro documentando uma chamada específica feita a um "Web Hook Fake." Cada interação captura informações sobre o método HTTP usado, os parâmetros enviados, a resposta recebida e outros detalhes relevantes. Esses registros são essenciais para análises, depuração e acompanhamento do comportamento dos "Web Hooks Fakes" durante os testes e a integração.

- ***Desenvolvedor 2:*** Perfeito. Agora, vamos passar para o "Contexto: Consumo dos Web Hooks Fakes". Aqui temos mais dois conceitos. O primeiro é "Registro de Interações." O que isso significa?

- ***Desenvolvedor 3:*** "Registro de Interações"(Interaction Log) refere-se aos registros que documentam as chamadas feitas aos "Web Hooks Fakes." Esses registros permitem análises e depuração das interações.

- ***Desenvolvedor 1:*** Ótimo, agora o último conceito neste contexto, "Catalogo de Integração" (Integration Catalog). Vamos definir isso.

- ***Desenvolvedor 2:*** Claro. "Catalogo de Integração" é o o conjunto de Registro de Interações.

- ***Desenvolvedor 3:*** Ótimo trabalho, equipe. Agora temos uma compreensão clara dos contextos e conceitos relacionados à API fictícia. Isso nos ajudará a avançar com o desenvolvimento e atender às necessidades do cliente de forma eficaz.


# Resumo

## Contextos

- ***Gestão de Web Hooks Fakes:*** Este contexto lida com a criação, configuração, edição, exclusão e listagem dos "Web Hooks Fakes". Envolve aspectos relacionados à administração e manutenção dos pontos de integração fictícios.

- ***Consumo dos Web Hooks Fakes:*** Neste contexto, concentra-se no uso e na interação com os "Web Hooks Fakes" criados. Isso abrange a realização de chamadas aos endpoints fictícios, a captura e análise de registros de interações e a busca de informações específicas sobre esses pontos de integração.

## Gestão de Web Hooks Fakes

- ***Web Hook Fake:*** Refere-se aos endpoints fictícios criados para simular os endpoints dos clientes, permitindo testes de integração sem depender dos clientes reais.

- ***Especificação de Resposta:*** Refere-se aos detalhes da resposta que pode ser definida para um "Web Hook Fake", incluindo o formato da resposta e seu conteúdo.

- ***Código de Status HTTP:*** Indica o código de status HTTP que será incluído na resposta de um "Web Hook Fake" para simular o comportamento da API.


## Consumo dos Web Hooks Fakes

- ***Interação:*** É o registro documentando uma chamada específica feita a um "Web Hook Fake." Cada interação captura informações sobre o método HTTP usado, os parâmetros enviados, a resposta recebida e outros detalhes relevantes. Esses registros são essenciais para análises, depuração e acompanhamento do comportamento dos "Web Hooks Fakes" durante os testes e a integração.

- ***Registro de Interações:*** São registros que documentam as chamadas feitas aos "Web Hooks Fakes", permitindo análises e depuração.

- ***Catalogo de Integração:*** É o conjunto dos Registro de Interações.


- [Voltar](7-metodologia.md)