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
