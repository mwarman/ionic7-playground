# Ionic 7 Playground

> **NOTE:** This project uses Ionic React.

## Getting Started

### NodeJS

Install Node Version Manager, [nvm](https://github.com/nvm-sh/nvm).

Change directory to the project base directory run the following commands.

Switch to the version of Node required by this project.

```
nvm use
```

If you receive a message stating that version of Node is not currently installed, use nvm to install it.

```
nvm install
```

### Ionic CLI

This project uses Ionic 7.1.1. Install the Ionic CLI globally.

> **NOTE:** Ensure you have installed the correct version of Node and are currently using it.

```
npm install -g @ionic/cli@7.1.1
```

## `main` Branch

The `main` branch contains the source for the initially generated Ionic 7 React project.

The project was created using the following command:

```
ionic start ionic7-playground tabs --type=react --capacitor --no-git
```

Do **NOT** commit experiments on the `main` branch.

## Experiments

Create experiments on experiment branches. Experiment branches are prefixed with `exp/`, for example:

- `exp/modal-slider`
- `exp/use-camera`

## Related Information

- [Ionic Docs][ionic7]

[ionic7]: https://ionicframework.com/docs/ 'Ionic Documentation'
[nvm]: https://github.com/nvm-sh/nvm 'Node Version Manager'
