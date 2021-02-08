# LDA-Topic-Model


Here's an [LDA topic model](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) written in Scala. 
The project can be build and run in [sbt](https://www.scala-sbt.org/) by running ''sbt compile'' & ''sbt run''
in the root directory. The model pulls txt documents from the ''src/main/resources'' folder and seperates them 
into "topics", as specified by ''K'' parameter in the LDA class constructor. ''src/main/scala/WikiParser.scala'' 
can be used to pull and preprocess Wikipedia articles given a list of links in the ''src/main/articles/links.txt'' 
file. 