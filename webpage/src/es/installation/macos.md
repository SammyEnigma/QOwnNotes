# Instalar en macOS ™

Descargue la última **imagen de disco de macOS** desde los[lanzamientos de QOwnNotes en GitHub](https://github.com/pbek/QOwnNotes/releases). Ábrala y arrastre la aplicación **QOwnNotes** a su **carpeta de aplicaciones**.

La primera vez, debe hacer clic derecho en la aplicación y hacer clic en **Abrir** para abrir QOwnNotes.

El lanzamiento de GitHub actualmente solo está construido para la plataforma x86.

::: warning
Si recibe un mensaje de error `QOwnNotes.app no se puede abrir porque no se puede verificar el desarrollador`, debe visitar su **Configuración de seguridad** de macOS y hacer clic en `Abrir de todos modos`.

Para sacar la aplicación de la cuarentena también puede ejecutar el siguiente comando en la terminal:

```bash
xattr -r -d com.apple.quarantine /Applications/QOwnNotes.app
```

:::

::: tip
La aplicación utiliza su **actualizador interno** para actualizarse. Puede ver la última versión en la parte inferior derecha de la aplicación.
:::

## Homebrew

Hay un barril de QOwnNotes mantenido por la comunidad en [Homebrew](https://formulae.brew.sh/cask/qownnotes).

Puedes instalarlo con:

```bash
brew install qownnotes
```

## Nix

También puede instalar QOwnNotes con el [gestor de paquetes de Nix](https://wiki.nixos.org/wiki/Nix_package_manager) en macOS de forma nativa en **x86 y Apple Silicon**. Consulte [Instalar mediante Nix](./nix.md).
