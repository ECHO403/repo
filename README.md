# maven repo

## 引用仓库

```groovy
rootProject.allprojects {
    repositories {
        google()
        mavenCentral()
        // maven { url 'http://localhost:8081/repository/m2/' }
        // maven { url 'https://raw.githubusercontent.com/tbc2140/repo/m2' }
        maven { url 'https://cdn.jsdelivr.net/gh/tbc2140/repo/' }
    }
}

dependencies {
    api '$group:$artifact:$version'
}
```
