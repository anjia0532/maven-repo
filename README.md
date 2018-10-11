# maven-repo
My personal maven repository.

## Usage
pom.xml:
```xml
<repositories>
    <repository>
        <id>Yanjia-maven-repo</id>
        <url>https://raw.githubusercontent.com/anjia0532/maven-repo/master/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```
