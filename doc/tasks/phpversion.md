# PhpVersion

The Phpversion task will check if your current php version is still supported.
The date of the php version that is checked, is the end of the security updates that can be found [here](https://secure.php.net/supported-versions.php).
It lives under the `phpversion` namespace and has following configurable parameters:

```yaml
# grumphp.yml
parameters:
    tasks:
        phpversion:
            project: 7.0
```

**project**

*Default: null*

Manually set a minimum version for your project.