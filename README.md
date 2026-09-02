# Quick Maven

**A simple emacs plugin to generate a minimal workable project so you don't have to write the pom.xml every time.**

Simply press M-x and type qkmvn and return, it will generate:

- src/main/java
- src/main/resources
- src/test/java
- src/test/resources
- pom.xml

and pom.xml will be filled with:

```xml
<project xmlns=\"http://maven.apache.org/POM/4.0.0\" xmlns:xsi=\"http://www.w3.org/2001/XMLSchema-instance\" xsi:schemaLocation=\"http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd\">
    <modelVersion>4.0.0</modelVersion>
    <groupId>com.example</groupId>
    <artifactId>hello</artifactId>
    <version>1.0-SNAPSHOT</version>
</project>
```

Yes there is only one function and yes you cannot customize information with any parameters

But im a lazy person, so if u got a better idea, fork one or rewrite one urself :)
