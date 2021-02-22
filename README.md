### Paulo Siécola

Mestre em Ciência da Computação pela Universidade de São Paulo - USP. Desenvolvedor backend e mobile. Instrutor online, professor e autor de livros sobre cloud computing e desenvolvimento mobile 

## Cursos online:

* [Criando serviços em Java com AWS ECS e Fargate](https://www.udemy.com/course/aws-ecs-fargate-java/?referralCode=859777729E4809B20485)

Crie a infraestrutura das aplicações baseadas em **Docker** com **AWS CDK**, interagindo com serviços da AWS como **SNS**, **SQS**, **RDS**, **DynamoDB** e **S3**.

[<img src="images/aws_course_image.png" alt="aws_course_image" style="zoom:30%;"/>](https://www.udemy.com/course/aws-ecs-fargate-java/?referralCode=859777729E4809B20485)

*Áudio em Português e legendas em Português e Espanhol*



Nesse curso você irá criar duas aplicações utilizando **Spring Boot em containers Docker**, para interagir com serviços da AWS como:

- **ECS:** o Elastic Container Service é o serviço de orquestração de containers da AWS. Com ele é possível gerenciar a execução de aplicações baseados em **containers Docker** de forma robusta e escalável. E com o **AWS Fargate**, o **Serverless** compute for containers da AWS, não é necessário criar instâncias de máquinas EC2, reduzindo o custo de operação de aplicações baseadas em containers;
- **RDS**: o Relational Database Service é um recurso que permite a criação de instâncias de banco de dados, com serviços como backups automáticos e diretrizes de segurança de acesso;

- **SNS**: o Simple Notification Service é um recurso muito utilizado para criação de mecanismos de notificações para diversas aplicações ou outros serviços;

- **SQS**: o Simple Queue Service é um recurso que permite a criação de filas para entrega de mensagens de forma rápida e confiável, possibilitando a criação de um mecanismo assíncrono de comunicação entre aplicações;

- **DynamoDB**: esse é um poderoso serviço de banco de dados NoSQL, que permite a criação de tabelas, sem a necessidade de se criar um servidor, com características exclusão automática de dados, escalabilidade e muito mais;

- **S3**: o Simple Storage Service permite a criação de buckets para armazenamento seguro de arquivos. Além disso é possível configurar eventos a serem gerados quando esses arquivos são colocados nesses buckets, fazendo com outras aplicações sejam avisadas desses eventos.

Com isso você aprenderá também a utilizar o **AWS SDK**, que é um conjunto de bibliotecas desenvolvido pela própria AWS para utilizar seus serviços. Esses recursos serão criados na AWS utilizando o **AWS Cloud Development Kit - CDK**, uma forma moderna de modelamento e provisionamento de infrastrutura na AWS. Você também aprenderá como monitorar os serviços através de gráficos e métricas, além de utilizar o **CloudWatch Insights,** para visualização e pesquisa de logs das aplicações. Aprenda tudo isso com explicações detalhadas e exercícios práticos, onde você poderá testar suas habilidades e aplicar os conceitos aprendidos. Ao final desse curso, você estará confiante para arquitetar e desenvolver serviços na AWS de forma escalável e robusta.



## E-books:

- [Desenvolvendo aplicações em Java para AWS](https://leanpub.com/amazonwebservice)

[<img src="images/book_cover_03_pt.png" alt="book_cover_03_pt" style="zoom:30%;" />](https://leanpub.com/amazonwebservice)

Esse livro é destinado a **desenvolvedores de software**, com ou sem experiência em cloud computing, que desejam se aprofundar nos serviços oferecidos pela AWS. Também é uma fonte de conhecimento para **administradores e operadores de sistemas**, para se familiarizarem com as ferramentas de criação e administração de recursos de cloud computing da AWS. 

As aplicações ensinadas nesse livro, como forma de exemplificação dos conceitos que serão apresentados, utilizam *frameworks* e ferramentas modernas, como **Spring Boot** e **Docker**. Dessa forma, o leitor aprenderá a trabalhar com tais tecnologias em conjunto com os serviços de *cloud computing*. 

Todos os exemplos possuem código-fonte disponíveis para acesso gratuito. A seguir uma breve descrição de cada um deles:

- Project01: nesse exemplo será construída uma aplicação com serviços REST para cadastro de produtos de uma loja. Tais produtos serão armazenados em um banco de dados MySQL utilizando o [AWS RDS](https://aws.amazon.com/rds/). Em cada operação de cadastro, exclusão ou alteração de um produto, um evento será publicado em um tópico do [AWS SNS](https://aws.amazon.com/sns), permitindo a integração com outras aplicações. Essa aplicação também fará importação de arquivos de notas fiscais através do [AWS S3](https://aws.amazon.com/s3/).
- Project02: esse projeto contará com uma tabela do [AWS DynamoDB](https://aws.amazon.com/dynamodb), para armazenar os eventos gerados pela aplicação de cadastro de produtos, integrado através de uma fila do [AWS SQS](https://aws.amazon.com/sqs/).
- Lambda01: esse será um exemplo simples de uma aplicação *serverless* utilizando funções com o [AWS Lambda](https://aws.amazon.com/lambda/), demonstrando como agendar a execução de uma função.
- Lambda02: nesse segundo exemplo, será demonstrado como executar uma função Lambda através de um evento publicado no SNS.
- Lambda03: aqui será apresentado como criar uma função Lambda para consumir arquivos importados no S3 e gravar seus dados em uma tabela do DynamoDB.

