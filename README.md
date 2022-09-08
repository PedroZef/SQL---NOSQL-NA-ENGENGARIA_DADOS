# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia e Cientista de Dados

## SQL

SQL é a sigla para Structured Query Language que significa, traduzindo para o português, “Linguagem de Consulta Estruturada”. Com o SQL, você pode executar vários comandos para criar, alterar, gerenciar, consultar, dentre outras informações no seu banco de dados e seguem uma modelagem relacional.

- DML: linguagem de manipulação de dados: Os comandos mais importantes desse subconjunto são: INSERT, DELETE e UPDATE.

- DQL: linguagem de consulta de dados: Define o Select, serve para consultar os dados armazenados.

- DDL: linguagem de definição de dados: Comporta os comandos usados para gerenciar as estruturas de dados – CREATE, DROP, ALTER.

- DCL: linguagem de controle de dados: Nela contém comandos para controlar o acesso aos dados da base - GRANT E REVOKE.

- DTL ou TCL: linguagem de transação de dados onde define comandos para gerenciar transações feitas no banco - COMMIT, BEGIN e ROLLBACK.

## NoSQL

NoSQL (Not Only SQL) é o termo utilizado para banco de dados não relacionais de alto desempenho, onde geralmente não é utilizado o SQL como linguagem de consulta e foi criado para ter uma performance melhor, uma escalabilidade mais horizontal para suprir necessidades onde os bancos relacionais não são eficazes.

### No geral, temos 5 tipos de bancos de dados

- Documentos
Os dados são armazenados como documentos. Os documentos podem ser de scritos como dados no formato de chave-valor, como por exemplo, o padrão JSON.
- Um exemplo de banco de dados neste formato é o MongoDB;

- Colunas
Os dados são armazenados em linhas particulares de tabela no disco, podendo suportar várias linhas e colunas e também permitem sub-colunas. Um banco de dados dessa família é o Cassandra;

- Grafos
Os dados são armazenados na forma de grafos (vértices e arestas). O Neo4j é um banco que utiliza grafos;

- Chave-valor
Este é a que aguenta mais carga de dados, pois o conceito dele é que um determinado valor seja acessado através de uma chave identificadora única. Um exemplo é o banco de dados Riak;

- Multi-Model
Como o próprio nome diz, os bancos de dados nosql desta categoria, mesclam os modelos acima citados.

### Suas diferenças

- NoSQL é que toda a informação é agrupada e guardada no mesmo registro.

- Já no SQL você precisa ter o relacionamento entre várias tabelas para ter a informação, informação está disposta no modelo entidade e relacionamento.

- O SQL tem certa dificuldade em conciliar a demanda por escalabilidade. Quanto a escalabilidade do NoSQL, deve se levar em consideração a modelagem do sistema.

- Um ponto forte do SQL é quanto à consistência das informações.

- Já o NoSQL garante o último valor atualizado, isso se nenhuma atualização for realizada até o momento da consulta.

- Quanto à segurança, ambos estão suscetíveis a ataques.

## NewSQL

Os bancos de dados NewSQL buscam promover a mesma melhoria de desempenho e escalabilidade dos sistemas NoSQL, não abrindo mão dos benefícios dos bancos de dados tradicionais, da linguagem SQL e das propriedades ACID.

Diferente dos SGBD tradicionais, no SGBD NewSQL definem cinco características:

- Linguagem SQL como meio de interação entre o SGBD e a aplicação;

- Suporte para transações ACID;

- Controle de concorrência não bloqueante, para que as leituras e escritas não causem conflitos entre si;

- Arquitetura que forneça um maior desempenho por nó de processamento;

- Arquitetura escalável, com memória distribuída e com capacidade de funcionar em um aglomerado com um grande número de nós.

- NewSQL é um aprimoramento do RDBMS utilizando o melhor dos dois mundos. Pois vimos, cada banco tem um propósito específico.

- Bancos NoSQL especialistas com o poder do NewSQL, como é o caso do MariaDB (Desenvolvido pelo criador do MySQL).

- MemSQL: Como o próprio nome sugere, é operado em memória, e é um sistema de banco de dados de alta escala por sua combinação de desempenho e compatibilidade com o SQL transacional e ACID na memória, adicionando uma interface relacional em uma camada de dados in-memory.

- VoltDB: Projetado por vários pesquisadores de sistema de banco de dados bem conhecidos, oferece a velocidade e a alta escalabilidade dos bancos de dados NoSQL, mas com garantias ACID, e sua latência em milissegundo e integração com Hadoop.

- SQLFire: Servidor de banco de dados NewSQL da VMware, desenvolvido para escalar em plataformas nas nuvens e tomar as vantagens de infraestrutura virtualizadas.

## Engenharia de dados

- Um profissional dessa área é responsável por desenvolvimento de esquemas de tabelas, gerenciar e organizar dados, também projetar e desenvolver uma arquitetura de dados escalável, verificar a qualidade dos dados e eliminar dados, agrupar dados, armazenamento

### Na engenharia de dados

- Coletar e alinhar dados;

- Desenvolver algoritmos para transformação de dados;

- Auxiliar na gestão;

- Validar e analisar dados;

- Criar, testar e manter dados.

- O profissional que atua na área de engenharia de dados tem a responsabilidade de implementar, monitorar, atualizar e garantir a segurança do banco, o que requer um excelente nível de conhecimento em SQL e NoSQL.

## Big data

- É a área do conhecimento focada em tratar, analisar e obter informações a partir de conjuntos de dados grandes demais. Big data é uma realidade para muitas empresas, o mercado demanda profissionais que estejam atualizados e saibam lidar com esse novo cenário.

- Os conhecimentos em SQL, NoSQL são muito importantes para lidar com grandes quantidades de dados. Atualmente, com o uso do NoSQL permitem as empresas trabalharem com dados semiestruturados e com grande poder de escalabilidade para o universo do Big Data.
