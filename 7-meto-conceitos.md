# Exemplo

- Desenvolvedor 1: Olá equipe, tivemos uma reunião com o cliente e discutimos a criação da API fictícia. O time expressou a necessidade de uma linguagem ubíqua para o projeto e também identificamos dois principais contextos: "Gestão de Web Hooks Fakes" e "Consumo dos Web Hooks Fakes". Vamos discutir e definir os conceitos que capturamos durante a conversa.

- Desenvolvedor 2: Ótimo, por onde começamos?

- Desenvolvedor 3: Vamos começar com o "Contexto: Gestão de Web Hooks Fakes". Aqui temos três conceitos fundamentais. O primeiro é "Web Hook Fake". Vamos definir isso.

- Desenvolvedor 1: Concordo. "Web Hook Fake" refere-se aos endpoints fictícios que criamos para simular os endpoints dos clientes, permitindo testes de integração sem depender dos clientes reais.

- Desenvolvedor 2: Certo, próximo conceito, "Especificação de Resposta". Vamos esclarecer isso.

- Desenvolvedor 3: "Especificação de Resposta" diz respeito aos detalhes da resposta que podem ser definidos para um "Web Hook Fake", incluindo o formato da resposta e seu conteúdo.

- Desenvolvedor 1: Ótimo, agora o último conceito neste contexto, "Código de Status HTTP". Vamos definir isso também.

- Desenvolvedor 2: Claro. "Código de Status HTTP" indica o código de status HTTP que será incluído na resposta de um "Web Hook Fake" para simular o comportamento da API.

- Desenvolvedor 3: Excelente, agora, adicionando o conceito de "Interação." O que isso significa?

- Desenvolvedor 1: "Interação" é o registro documentando uma chamada específica feita a um "Web Hook Fake." Cada interação captura informações sobre o método HTTP usado, os parâmetros enviados, a resposta recebida e outros detalhes relevantes. Esses registros são essenciais para análises, depuração e acompanhamento do comportamento dos "Web Hooks Fakes" durante os testes e a integração.

- Desenvolvedor 2: Perfeito. Agora, vamos passar para o "Contexto: Consumo dos Web Hooks Fakes". Aqui temos mais dois conceitos. O primeiro é "Registro de Interações." O que isso significa?

- Desenvolvedor 3: "Registro de Interações"(Interaction Log) refere-se aos registros que documentam as chamadas feitas aos "Web Hooks Fakes." Esses registros permitem análises e depuração das interações.

- Desenvolvedor 1: Ótimo, agora o último conceito neste contexto, "Catalogo de Integração" (Integration Catalog). Vamos definir isso.

- Desenvolvedor 2: Claro. "Catalogo de Integração" é o o conjunto de Registro de Interações.

- Desenvolvedor 3: Ótimo trabalho, equipe. Agora temos uma compreensão clara dos contextos e conceitos relacionados à API fictícia. Isso nos ajudará a avançar com o desenvolvimento e atender às necessidades do cliente de forma eficaz.

# Resumo

## Contextos

- Gestão de Web Hooks Fakes: Este contexto lida com a criação, configuração, edição, exclusão e listagem dos "Web Hooks Fakes". Envolve aspectos relacionados à administração e manutenção dos pontos de integração fictícios.

- Consumo dos Web Hooks Fakes: Neste contexto, concentra-se no uso e na interação com os "Web Hooks Fakes" criados. Isso abrange a realização de chamadas aos endpoints fictícios, a captura e análise de registros de interações e a busca de informações específicas sobre esses pontos de integração.

## Gestão de Web Hooks Fakes

- Web Hook Fake: Refere-se aos endpoints fictícios criados para simular os endpoints dos clientes, permitindo testes de integração sem depender dos clientes reais.

- Especificação de Resposta: Refere-se aos detalhes da resposta que pode ser definida para um "Web Hook Fake", incluindo o formato da resposta e seu conteúdo.

- Código de Status HTTP: Indica o código de status HTTP que será incluído na resposta de um "Web Hook Fake" para simular o comportamento da API.


## Consumo dos Web Hooks Fakes

- Interação: É o registro documentando uma chamada específica feita a um "Web Hook Fake." Cada interação captura informações sobre o método HTTP usado, os parâmetros enviados, a resposta recebida e outros detalhes relevantes. Esses registros são essenciais para análises, depuração e acompanhamento do comportamento dos "Web Hooks Fakes" durante os testes e a integração.

- Registro de Interações: São registros que documentam as chamadas feitas aos "Web Hooks Fakes", permitindo análises e depuração.

- Catalogo de Integração: É o conjunto dos Registro de Interações.