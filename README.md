#### Quick Java 21 - Maven Archetype
An archetype to create Java 21 maven project, quick and easy.

#### Test
```bash
mvn clean verify`
```
#### Build and install
The archetype will be installed in local repository `.m2`

```bash
mvn clean install
```
#### Then create a new project
```bash
mvn -B archetype:generate \
-DarchetypeCatalog=local \
-DarchetypeGroupId=net.yoedtos.archetypes \
-DarchetypeArtifactId=archetype-quick-java21 \
-DarchetypeVersion=1.0.0 \
-DgroupId=net.yoedtos.demo \
-DartifactId=java-21 \
-Dversion=1.0.0

```

### Or in Interactive Mode
```bash
mvn archetype:generate -DarchetypeCatalog=local
```