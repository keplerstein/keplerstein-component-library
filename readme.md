# Reusable components for Keplerstein

## Introduction

Reusable components used in the Keplerstein website projects.

The goal is that this repository is an npm installable library. Included in the default Craft CMS install, but can be updated anytime by a simple npm install.

## Table of contents

- [Reusable components for Keplerstein](#reusable-components-for-keplerstein)
  - [Introduction](#introduction)
  - [Table of contents](#table-of-contents)
  - [Installation](#installation)
  - [Base styles](#base-styles)
  - [Installation](#installation-1)
  - [Components](#components)
  - [Utilities](#utilities)
  - [Snippets](#snippets)
  - [Icons](#icons)
  - [Coding guidelines](#coding-guidelines)

## Installation

To add this library to a project, install it by the private Github URL

```console
$ yarn add git+ssh://git@github.com:keplerstein/keplerstein-component-library.git
```

Make sure the domain github.com is added to the list of your well known hosts. Just run following command and **answer yes** to save it automatically:

[More info](https://stackoverflow.com/questions/13363553/git-error-host-key-verification-failed-when-connecting-to-remote-repository)

```console
$ ssh github.com
```

Make sure your SSH key is added to Github, and Yarn knows about it. Run the following command:

```console
$ ssh-add
```

## Base styles

Every project starts with some base styles applied:

-   normalize-scss
-   reset
-   breakpoints
-   ...

[More info](./docs/base-styles.md)

## Installation

```scss
@import "keplerstein-component-library/scss/base";
```

## Components

-   [Button](./docs/button.md)
-   [Container](./docs/container.md)
-   [Lists (ul>li)](./docs/lists.md)
-   [Card grid](./docs/card-grid.md)

## Utilities

Various small mixins for common tasks. [View Utilities](./docs/utilities.md).

## Snippets

Various frequently used snippets in our templates. [View snippets](./docs/snippets.md)

## Icons

- [Products (Used in Commerce when adding to the navbar)](./icons/products.svg)
- [Orders (Used in Commerce when adding to the navbar)](./icons/orders.svg)

## Coding guidelines

We try to use the [BEM (Block Element Modifier) naming convention](http://getbem.com/naming/)
