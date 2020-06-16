# How to Export and Import VSCode extensions

## Unix
1. Export extensions to a shell file

    ```bash
    code --list-extensions | sed -e 's/^/code --install-extension /' > extensions.sh
    ```

2. Import extensions from a shell file

    ```bash
    ./extensions.sh
    ```

## Windows (PowerShell)

```bash
code --list-extensions | % { "code --install-extension $_" }
```
