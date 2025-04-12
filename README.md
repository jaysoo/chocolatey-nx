# chocolatey-nx

Package:

```shell
choco pack
```

Check package locally:

```shell
choco install nx -s . --ignore-dependencies
choco uninstall nx -y
```

Publish:

```shell
choco push nx.<version>.nupkg --source https://push.chocolatey.org/
```
