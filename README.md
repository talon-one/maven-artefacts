# JAVA SDK with Maven

Add the following to your `pom.xml`:

```xml
<repository>
  <id>talon-one</id>
  <url>https://github.com/talon-one/maven-artefacts/raw/master</url>
</repository>
```

```xml
<dependency>
  <groupId>one.talon</groupId>
  <artifactId>talon-one-client</artifactId>
  <version>4.4.1</version>
  <scope>compile</scope>
</dependency>
```
## Latest Release Candidate version

Latest RC version: `4.5.0-rc`

After adding the above repository definition to your `pom.xml` file, add the following to use the RC version:

```xml
<dependency>
  <groupId>one.talon</groupId>
  <artifactId>talon-one-client</artifactId>
  <version>4.5.0-rc</version>
  <scope>compile</scope>
</dependency>
```
