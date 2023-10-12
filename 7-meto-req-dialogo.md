# Exemplo

- Cliente: Time, estou enfrentando um desafio com as integrações dos meus clientes. Atualmente, estou dependendo que eles forneçam um endpoint de teste para que eu possa realizar minhas integrações. Isso está atrasando o meu progresso e gostaria de uma solução para simular esses endpoints dos nossos clientes. Como vocês podem me ajudar nisso?

- Desenvolvedor 1: Entendi, você está buscando uma solução que permita simular os endpoints dos nossos clientes para que você possa testar suas integrações sem depender deles. Estamos prontos para criar uma API fictícia que atenderá a essa necessidade. Ela permitirá que você configure e gerencie endpoints de teste, especificando respostas, códigos de status e outros detalhes. Isso deve ajudar a acelerar seus testes.

- Cliente: Isso mesmo! Estou feliz em ouvir que vocês podem desenvolver essa API fictícia para mim. Mas quais funcionalidades exatamente essa API terá?

- Desenvolvedor 2: A API fictícia que estamos criando permitirá que você faça o seguinte:
    - Cadastrar endpoints fictícios.
    - Editar as configurações desses endpoints.
    - Excluir endpoints fictícios quando não forem mais necessários.
    - Definir as respostas que esses endpoints devem fornecer.
    - Especificar os códigos de status das respostas.
    - Acessar uma lista de todos os endpoints que você configurou.
    - Buscar informações específicas sobre um endpoint, desde que você conheça o alias associado a ele.
    - Cliente: Perfeito, isso resolve meu problema. E quanto aos relatórios de chamadas que vocês mencionaram?

- Desenvolvedor 1: Além disso, a API permitirá que você gere relatórios de chamadas que contenham registros de todas as chamadas feitas aos seus endpoints fictícios. Você também poderá buscar informações específicas nessas chamadas, o que será útil para análises e depuração.

- Cliente: Ótimo! E quais métodos HTTP essa API fictícia suportará?

- Desenvolvedor 2: Os consumidores da API fictícia poderão utilizar os métodos POST, PUT, PATCH e DELETE para interagir com os endpoints fictícios que você configurar.

- Cliente: Isso soa excelente! Agora, quais são os detalhes técnicos que devo saber sobre essa API?

- Desenvolvedor 1: Para garantir um ótimo desempenho, estamos projetando a API para operações de leitura mais frequentes do que de escrita. Além disso, a API será escalável para lidar com um grande volume de solicitações, oferecerá alta disponibilidade para que você possa acessá-la de forma confiável e garantirá a consistência dos dados, para que suas configurações estejam sempre disponíveis quando você precisar delas.

- Cliente: Excelente! Estou satisfeito com esses detalhes. Vamos seguir em frente com o desenvolvimento da API fictícia. Obrigado, equipe de desenvolvimento, por ajudar a resolver meu problema!


Através do diálogo estabelecido entre nossa equipe e o cliente, conseguimos criar os requisitos fundamentais do projeto. Abaixo, apresentamos esses requisitos para que vocês possam compreender com clareza o direcionamento do projeto.

## Resumo

O objetivo deste projeto é desenvolver uma API fictícia que permitirá aos usuários criar, editar e gerenciar endpoints personalizados. Com essa API em funcionamento, os usuários poderão configurar rotas, especificar códigos de status HTTP e definir os corpos das respostas. Essa API estará pronta para ser consumida de acordo com as definições fornecidas.

## Requisitos Funcionais

- CRUD API Fictícia
    - Os usuários poderão cadastrar uma API fictícia.
    - Os usuários terão a capacidade de editar uma API fictícia já existente.
    - Os usuários poderão deletar uma API fictícia conforme necessário.
    - Os usuários poderão definir o conteúdo da resposta da API fictícia.
    - Os usuários poderão especificar o código de status da resposta da API fictícia.
    - Os usuários terão acesso a uma lista de todas as APIs cadastradas.
    - Os usuários poderão buscar informações sobre uma API específica, desde que conheçam o alias dessa API.

- Relatório de Chamadas: 
    - Os usuários poderão gerar um relatório contendo todas as chamadas realizadas pelos consumidores da API cadastrada.
    - Os usuários poderão buscar um registro específico no relatório da API cadastrada.

- Métodos HTTP: Os consumidores da API fictícia poderão utilizar os métodos POST, PUT, PATCH e DELETE.
- Armazenamento de Dados: Todos os dados fornecidos pelos consumidores da API fictícia serão armazenados para consultas futuras, incluindo cabeçalhos, corpos de requisição, métodos, respostas e códigos de status.

## Requisitos Não Funcionais

- Leitura Maior que Escrita: Prevemos um maior número de operações de leitura do que de escrita.
- Escalabilidade: O sistema deve ser capaz de lidar com um aumento significativo na carga de trabalho.
- Alta Disponibilidade: O sistema deve estar disponível de forma consistente e confiável.
- Consistência: Garantiremos que os dados sejam consistentes e estejam disponíveis quando necessários.