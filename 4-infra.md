# Adapters

## Resumo

Os Adapters atuam como portas de saída do serviço, fornecendo meios para o sistema se comunicar com o mundo externo. Eles desempenham um papel crucial na persistência de dados, publicação em filas, produção de eventos no Kafka e comunicação com serviços externos via HTTP ou gRPC. Os Adapters traduzem as ações internas do sistema em operações compreensíveis pelo ambiente externo.

# Definições

Aqui estão algumas definições essenciais relacionadas aos Adapters como portas de saída:

- Persistência de Dados: Os Adapters de persistência são responsáveis por interagir com sistemas de armazenamento de dados, como bancos de dados SQL ou NoSQL. Eles realizam operações de criação, leitura, atualização e exclusão de dados, abstraindo a complexidade do armazenamento.

- Publicação em Filas: Adapters de filas lidam com a publicação de mensagens em sistemas de filas, como RabbitMQ ou SQS. Eles garantem que eventos ou mensagens sejam entregues de forma confiável à fila.

- Produção no Kafka: Adapters de produção do Kafka são responsáveis por enviar eventos para tópicos no Kafka, permitindo a disseminação de informações em tempo real para outros sistemas que consomem esses tópicos.

- Comunicação com Serviços Externos: Adapters de comunicação externa permitem que o sistema interaja com serviços externos por meio de protocolos como HTTP ou gRPC. Eles traduzem as solicitações e respostas para garantir a interoperabilidade com esses serviços.

# Exemplos

Aqui estão exemplos de Adapters como portas de saída em uma arquitetura hexagonal:

- Adapter de Banco de Dados: Responsável por realizar operações de CRUD (Create, Read, Update, Delete) no banco de dados, abstraindo a lógica de persistência.

- Adapter de Fila: Publica mensagens em uma fila de mensagens, garantindo que eventos sejam entregues a consumidores interessados.

- Adapter do Kafka: Envia eventos para tópicos no Kafka, permitindo a disseminação assíncrona de informações para sistemas que consomem esses tópicos.

- Adapter de Comunicação Externa HTTP/gRPC: Facilita a comunicação com serviços externos, seja por meio de chamadas HTTP RESTful ou gRPC, traduzindo as solicitações e respostas conforme necessário.

- Adapter de Armazenamento em Nuvem: Pode ser usado para interagir com serviços de armazenamento em nuvem, como Amazon S3 ou Google Cloud Storage, para upload e recuperação de arquivos.

Esses Adapters como portas de saída garantem que o sistema seja capaz de se integrar eficazmente com o mundo externo, tornando possível a persistência de dados, a comunicação assíncrona e a interação com serviços externos de maneira organizada e desacoplada da lógica de negócios central na camada de domínio.