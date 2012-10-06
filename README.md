# Maven SchemaSpy project

Sample maven project to generate schema documentation using maven-schemaspy-plugin.  Documents will be generated from an existing database. and will be outputed into target/site/schemaspy

SchemaSpy depends on the dot program provided by Graphviz.  Download Graphviz from:

[http://www.graphviz.org/Download.php](http://www.graphviz.org/Download.php)
    
Generate database schema documentation:    

    mvn site

To view:

    open target/site/schemaspy/index.html
    
    or
    
    start target/site/schemaspy/index.html 