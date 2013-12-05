szs-maven-repo
==============

## Getting Started
Add to your pom.xml:

```
<repositories>
    <repository>
        <id>tc-maven-repo</id>
        <url>https://github.com/shenzhongshan/szs-maven-repo/raw/master/releases</url>
    </repository>
</repositories>
```


## To deploy a third party jar:
```
mvn deploy:deploy-file -Durl=file:E:\want\szs-maven-repo\releases -Dfile=D:\jboss-4.0.5.GA\server\default\lib\ojdbc6_g.jar -DgroupId=com.oracle -DartifactId=ojdbc -Dversion=6_g -Dpackaging=jar
```
