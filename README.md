# crawler4j

A arquitetura utilizada foi:

  -  Elasticsearch, para indexação dos conteúdos;
  -  Apache Spark, para as atividades de aprendizado de máquina;
  -  Crawler4J, para recuperar conteúdos encontrados na Web;
  -  Apache Lucene é empregado pontualmente para retirar palavras não importantes;
  -  JSoup ajuda durante o parsing dos códigos HTML das páginas analisadas.



Adicionar as dependências no pom.xml

<dependency>
         <groupId>org.jsoup</groupId>
         <artifactId>jsoup</artifactId>
         <version>1.7.2</version>
   </dependency>
   <dependency>
         <groupId>edu.uci.ics</groupId>
         <artifactId>crawler4j</artifactId>
         <version>4.1</version>
   </dependency>
   <dependency>
         <groupId>org.elasticsearch</groupId>
         <artifactId>elasticsearch</artifactId>
         <version>1.5</version>
   </dependency>
   <dependency>
         <groupId>org.apache.spark</groupId>
         <artifactId>spark-mllib_2.10</artifactId>
         <version>1.4.0</version>
   </dependency>

