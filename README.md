# Including in your project

### settings.gradle.kts
dependencyResolutionManagement => repositories
```
maven {
    setUrl("https://jitpack.io")
}
```

### build.gradle.kts (Module:app)
dependencies
```
implementation ("com.github.ParkJunFeel:Sample-Library:1.0.0")
```
