# CivRepo

Use the follow to import this repository into your project

```xml
<repositories>
    <repository>
        <id>civrepo</id>
        <url>https://civrepo.io/</url>
    </repository>
</repositories>
```

```groovy
repositories {
    maven {
        url "https://civrepo.io/"
    }
}
```

## Redirects

CivRepo also offers easy aliasing to other Civ repositories, just replace `https://civrepo.io/` with:

- Devoted: `https://devoted.civrepo.io/`
    
- Civclassic: `https://civclassic.civrepo.io/`
