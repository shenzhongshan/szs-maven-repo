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
mvn deploy:deploy-file
-Durl=file:PATH_TO_LOCAL/src/szs-maven-repo/releases -Dfile=target/lamejb-0.2.0.jar -DgroupId=net.sf -DartifactId=lamejb -Dversion=0.2.0 -Dpackaging=jar
```
