# maven-repo
GitHub hosted Maven Repository for DRIVER+ Java Projects.

# Using artifacts hosted here

Add the following repository to your maven pom.xml file:

```
<repositories>
    <repository>
        <id>driver-mvn-repo</id>
        <url>https://raw.github.com/DRIVER-EU/maven-repo/master/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```
