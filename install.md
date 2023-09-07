# Instalar Node.js (MacOS)

## Forma 1: Web oficial

Ir a [nodejs.org](https://nodejs.org/es/) y descargar la versión LTS (Long Term Support).

> No recomendable porque solo tendrás una versión de Node.js instalada en tu ordenador. Si necesitas cambiar de versión, tendrás que desinstalar la actual y volver a instalar la nueva versión.

## Forma 2 (**recomendada**): Controlador de versiones ([fnm](https://github.com/Schniz/fnm))

1. Instalar [Homebrew](https://brew.sh/es/):

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Instalar [Rust](https://www.rust-lang.org/es/):

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

3. Instalar [fnm](https://github.com/Schniz/fnm):

```bash
curl -fsSL https://fnm.vercel.app/install | bash
```
