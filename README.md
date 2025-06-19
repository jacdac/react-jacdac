# React-Jacdac

A library of hooks and context for [Jacdac](https://aka.ms/jacdac).
React with hooks support required.

**Jacdac** is a plug-and-play hardware/software stack
for **microcontrollers** and their peripherals (sensors/actuators),
with applications to rapid prototyping, making, and physical computing.
-   **[Jacdac Protocol Documentation](https://aka.ms/jacdac/)**
-   **[Documentation](https://jacdac.github.io/jacdac-docs/clients/javascript/react/)**
-   **[API Reference](https://jacdac.github.io/react-jacdac/)**
-   Discussions at https://github.com/jacdac/jacdac/discussions
-   Issues are tracked on https://github.com/jacdac/jacdac/issues

The rest of this page is for developers of the react-jacdac library.

## Developer setup

-   clone this repository and pull all submodules

```
git clone https://github.com/jacdac/react-jacdac
git pull
```

-   install node.js
-   install yarn

```
npm install -g yarn
```

-   install dependencies

```
yarn install
```

-   run storybook

```
yarn storybook
```

### Visual Studio Code

You are welcome to use any editor you want! Visual Studio Code
provides seamless support for git sub-modules and is our preferred editor.

-   open [Visual Studio Code](https://code.visualstudio.com/)

```
code .
```

-   install the recommended extensions (**MDX**, **ESLint** and **Prettier** extensions)
-   in the Git view, click on the `jacdac` branch and select `main` so that changes are automatically synched

### Build

To have a watch developement,

```
yarn watch
```

## Contributing

This project welcomes contributions and suggestions.
