# DRIVER+ GitHub Hosted Maven Repository

This GitHub Repository is a Maven Repository containing artifacts of DRIVER+ Java Projects.

# Using the Artifacts

Add the following repository in your pom.xml

```
<repositories>
    <repository>
        <id>YOUR-PROJECT-NAME-mvn-repo</id>
        <url>https://raw.github.com/YOUR-USERNAME/YOUR-PROJECT-NAME/mvn-repo/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```
