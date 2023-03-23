# DependentProjectBug

```
msbuild DependentProjectBug -t:Clean
del lib\Code.cs
msbuild DependentProjectBug -t:Restore -t:Build
```
