# EntityHider
A lightweight Maven resource that can be shaded into a Spigot Plugin to facilitate fully hiding entities through packets
Designed so that multiple plugins can use it without causing incompatibilities.

## How to include in your project
This dependency is not delivered as a jar file like a plugin. Instead, you can shade it inside your own plugin
as a dependency. To do that, include the following in your `pom.xml`

```xml
<repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
</repository>
        ...
<dependency>
    <groupId>com.github.Sentropic</groupId>
    <artifactId>EntityHider</artifactId>
    <version>VERSION</version>
</dependency>
```