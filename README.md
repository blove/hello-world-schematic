# Hello World Angular Schematic

This repository is a very simple Angular Schematic.

## Install

First, install the dependencies via:

```bash
yarn install
```

## Build

To build the schematic from the TypeScript source:

```bash
yarn build
```

## Test

First, install the schematics CLI:

```bash
npm i -g @angular-devkit/schematics-cli
```

Then, run the schematic locally:

```bash
schematics .:hello-world YOUR_NAME_HERE --dry-run=false
```

Or, you can specify the name option explicitly:

```bash
schematics .:hello-world --dry-run=false --name=YOUR_NAME_HERE
```

## Unit Tests

Run the Jasmine unit tests:

```bash
npm test
```
