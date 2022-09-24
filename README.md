## Desafio
**Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes em um novo repositório Git, aumentando assim seu portfolio de conhecimentos.**

**Super Dica: Organize tudo em seu README.md, é uma alternativa bem rápida e efetiva, pois, o GitHub provê uma interface bem simples e intuitiva para isso. Além de ampliar seu portifólio de projetos no GitHub!**

### Pré-requisitos:

**Conhecimento Avançados(SQL, NoSQL);**

**Computador com SO de sua preferência(Windows, Linux, Mac OS);**





# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

## O que é um Banco de Dados Reacional (SQL)?

É o tipo de Banco onde se armazena ou pretende armazenar informações que tenham relacionamento entre si.
Normalmente quando a gente tem um conjunto de dados e precisa armazenar isso, seja normalmente para um modelo transacional e tem uma normalização das informações e precisar criar duplicidades,ter uma consistência e quando se tem um esquema de dados rígido e a gente sabe de fato o que agente vai armazenar nesse banco.

**Exemplos:**
Um sistema transacional de vendas ou de pedidos online, um e-commerce,pode ter ali ,armazenar entidades de clientes,de produtos.
Na hora de modelar você conhece o esquema que precisa modelar,e precisa ter relação entre esses dados.



## O que é um Banco de Dados Não Reacional (NoSQL)?

Podem processar grandes dados não estruturados e realizar modificações constantes de variadas formas de um banco de dados relacional.

É uma alternativa ao Banco De Dados Relacional, surgiu a partir da necessidade de escabilidades diferentes (horizontal).


## Porque dizer que o NoSQL foi criado para substituir o SQL é um equívoco?

O banco de Dados NoSQL surgir para tentar resolver as demandas que não conseguia ser resolvidas no banco de Dados Relacional, ele pode ser usado de maneira complementar e dependendo do nosso cenário e ao alto volume de informação,
O NoSQL é mais flexível em relação a armazenamento e consulta de dados.


## Como se consulta um Dado armazenado no NoSQL?
É preciso que essa consulta seja bem analisada desde o 
início da criação do Banco, definir as chaves, a formas como se quer consultar essas informações é importante, inclusive, para não precisar armazenar de uma única forma.


## Conhecer um SGBD de cada tipo é suficiente para iniciar?

O importante é conhecer o contexto sobre esses bancos de dados e para que foram feitos.
Conhecer os fundamentos principais para analisar qual o melhor banco a usar dependendo do cenário.

## A flexibilidade do NoSQL frente ao SQL

Com os bancos de dados SQL, os dados são armazenados em uma estrutura predefinida muito mais rígida. Mas com o NoSQL, os dados podem ser armazenados de uma forma mais livre, sem aqueles esquemas rígidos. Este design permite inovação e rápido desenvolvimento de aplicativos


## Sobre DataLake e Databricks

Os data lakes fornecem um armazenamento de dados completo e confiável que pode impulsionar a análise de dados, inteligência de negócios e aprendizado de máquina.
Um data lake é um local central que contém uma grande quantidade de dados em seu formato bruto nativo. Comparado a um data warehouse hierárquico, que armazena dados em arquivos ou pastas, um data lake usa uma arquitetura simples e armazenamento de objetos para armazenar os dados.
os data lakes são de formato aberto, para que os usuários evitem o bloqueio a um sistema proprietário como um data warehouse, que se tornou cada vez mais importante nas arquiteturas de dados modernas. Os data lakes também são altamente duráveis e de baixo custo, devido à sua capacidade de dimensionar e aproveitar o armazenamento de objetos.


## Quais os maiores desafios na hora de realizar o ETL?

 As ferramentas de ETL permitem acessar dados de várias origens, transformá-los e carregá-los nos mais variados sistemas de destino.
Um dos maiores desafios hoje para a prática de ETL é o custo para os projetos, influenciado por possíveis práticas inadequadas durante o desenvolvimento do projeto, mesmo utilizando ferramentas robustas. O retorno do investimento das iniciativas de ETL virá pela automatização de tarefas repetitivas que consumiriam horas de serviços profissionais e pela melhor qualidade da gestão propiciada pela tomada de decisão com dados entregues na hora certa e de maneira correta.



