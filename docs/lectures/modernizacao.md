## 17H25 - 17H55 - App Modernization | Modernizando sua arquitetura na AWS com serverless e containers

_Gabriel Leite da Silva - AWS_

![App Modernization | Modernizando sua arquitetura na AWS com serverless e containers](./pictures/modernizacao.jpg)

* Aplicações monolíticas - limitações
    * Difícil de escalar
* Microserviços*
* Aplicações modernas com GenAI
* Otimização de custo e elasticidade com Karpenter (SIMPLIFICANDO O MECANISMO DE CLUSTER AUTOSCALER DO KUBERNETES)
    * Provisionamento de computação rápido e simples para clusters Kubernetes
    * Lança automaticamente os recursos de computação certos para lidar com os aplicativos do cluster
    * Toma decisões para iniciar e encerrar nós para minimizar as latências de agendamento e o custo da infraestrutura
    * https://karpenter.sh/
* Eficiência Operacional com AWS Fargate (REDUZA A COMPLEXIDADE INDESEJADA NA EXECUÇÃO DE CONTAINERS)
    * Benefícios
        * Plano de dados serverless para Amazon ECS e Amazon EKS
        * Remove a necessidade de lidar com atualização, proteção e gestão de instâncias EC2
        * Simplifica o mecanismo de auto-scaling
        * Dimensionamento adequado ("Rightsizing")
        * Fargate Spot e Saving Plans para optimização de custos
* AWS Serverless Spectrum (A AWS oferece o mais amplo portfólio de serviços sem servidor para executar e criar aplicativos modernos.)
    * Primitivos
        * AWS Lambda
        * AWS Fargate
        * Amazon EventBridge
        * AWS App Runner
        * Amazon ECS
        * Amazon SNS
        * Amazon S3
        * Amazon EFS
        * Amazon SQS
        * Amazon API Gateway
    * Periféricos        
        * Amazon Aurora Serverless        
        * Amazon DynamoDB
        * Amazon Kinesis
        * AWS Step Functions
        * AWS AppSync
        * Amazon CloudWatch
        * AWS Glue
        * Amazon OpenSearch
        * Amazon QuickSight
* Processamento de Dados em Grande Escala com AWS Step Functions (Processamento dinâmico de grandes arrays de dados com estado de mapa distribuído.)
    * Coordenação de cargas de trabalho paralelas em grande escala com Step Functions.
    * Interação com milhões de objetos do S3 como arquivos JSON ou CSV.
    * Até 10.000 execuções paralelas.
    * Invocação do Lambda ou ECS/Fargate para computação sem servidor sob demanda em grande escala.
* Serverless com Amazon Bedrock
    * O Web Adapter oferece suporte ao streaming de resposta em todos os tempos de execução do AL2, incluindo o tempo de execução do Python
    * Amazon Step Function com Amazon Bedrock, possibilita a interconexão de business com GenAI (paralelização., determinismo e integração)

[Voltar](/aws-cloud-experience-2024)