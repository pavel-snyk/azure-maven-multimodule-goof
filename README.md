# Azure Maven Multi-Module Goof

Snyk test command can be run only with passing additional arguments
to enable `gradlePluginRepository` profile. 

```
snyk test --all-projects -- -PgradlePluginRepository
```
