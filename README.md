# Template Project for Python Projects

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier) 

This project is scaffolded with `copier`.

# How to use

Add this to your `.zshrc` file:

```bash
template() {
    if [ -z "$1" ]; then
        echo "Usage: template <project_name>"
        return 1
    fi
    copier copy gh:ajay-bhargava/python-template "$1"
}
```

Then, run `template <project_name>` to scaffold a new project.
