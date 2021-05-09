# Ritchie's formulas templates

<img width="940" alt="title" src="https://user-images.githubusercontent.com/22433243/117589773-15e03c00-b102-11eb-8a42-2015656831f8.png">

This repository contains templates which can be used to create new formulas with [ritchie-cli](https://github.com/ZupIT/ritchie-cli).

## Ritchie CLI Full Documentation

[Gitbook](https://docs.ritchiecli.io)

## Use Templates

To import this repository, you need [Ritchie CLI installed](https://docs.ritchiecli.io/getting-started/installation) and substitute the "commons" repository by this one.

To do so, you can use the `rit add repo` command manually, or execute the command line below directly on your terminal:

```bash
echo '{"provider":"Github", "name":"commons", "url":"https://github.com/GuillaumeFalourd/ritchie-templates", "priority":1}' | rit add repo --stdin
```

Finally, you can check if the repository has been imported correctly by executing the `rit list repo` command.

## Add support to other languages

The `rit create formula` command use the folder `/templates/create_formula` to list the languages options. If you want to edit some language template or to add new language templates, please access the following tutorial: [Languages Template Tutorial](https://github.com/GuillaumeFalourd/ritchie-templates/tree/main/templates/create_formula)

## Contributing

[Guidelines](https://github.com/GuillaumeFalourd/ritchie-templates/blob/main/CONTRIBUTING.md)
