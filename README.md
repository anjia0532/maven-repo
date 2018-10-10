# maven-repo
My personal maven repository.

## Usage
pom.xml:
```xml
        <repository>
            <id>anjia0532-repo</id>
            <name>anjia0532-repo</name>
            <url>https://raw.githubusercontent.com/anjia0532/maven-repo/master/</url>
            <releases>
                <enabled>true</enabled>
            </releases>
            <snapshots>
                <enabled>true</enabled>
            </snapshots>
        </repository>
```

```bash
mvn deploy -DaltDeploymentRepository=anjia-mvn-repo::default::file:/path/to/maven-repo/
````