# Cookie Jar

## Use

To activate one of the templates within a subdirectory, use the `--directory` option:

```shell
cookiecutter https://github.com/Traenqui/Cookie_Jar.git --directory="Python_Data_Science"
```

## Contribute new cookies

```
https://github.com/user/repo-name.git
    ├── directory1-name/
    |   ├── {{cookiecutter.project_slug}}/
    |   └── cookiecutter.json
    └── directory2-name/
        ├── {{cookiecutter.project_slug}}/
        └── cookiecutter.json
```
