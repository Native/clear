# Clear

A minimal SaSS framework to help deploy fast pages

## Table of contents

- [Quick start](#quick-start)

## Usage

There are two ways of using Clear.<br>
Clone the repo: ``.

### Via the command line by globally installing the required tools.

* Globally installing the neccesary tools
`
npm -g i node-sass
npm -g i nodemon
`

* Compiling

`npm run build-css`

minifying css not yet available..<br>


### Via nodeJs

* Installing neccesary modules

To get node to install the neccesary modules run `npm i` from the root directory

* Running the project

Run the project via `node index.js`

Any compiled css can be found under css/


### What's included

To create a webpage with this framework start with this skeleton:

```HTML
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">

    <title>Clear</title>

    <link rel="stylesheet" href="./css/main.css">
</head>

<body>
    <!-- start building -->
</body>

</html>
```

## Responsive functionality

### Display content based on screen size.

| class               | x-small | small | medium | large | x-large |
|---------------------|---------|-------|--------|-------|---------|
| `visible-xsmall-up` | ✔️       | ✔️     | ✔️      | ✔️     | ✔️       |
| `visible-small-up`  | ✖️      | ✔️     | ✔️      | ✔️     | ✔️       |
| `visible-medium-up` | ✖️      | ✖️    | ✔️      | ✔️     | ✔️       |
| `visible-large-up`  | ✖️      | ✖️    | ✖️     | ✔️     | ✔️       |
| `visible-xlarge-up` | ✖️      | ✖️    | ✖️     | ✖️    | ✔️       |

### Hide content based on screen size


| class              | x-small | small | medium | large | x-large |
|------------------  |---------|-------|--------|-------|---------|
| `hidden-xsmall-up` | ✖️      | ✖️    | ✖️     | ✖️    | ✖️      |
| `hidden-small-up`  | ✔️       | ✖️    | ✖️     | ✖️    | ✖️      |
| `hidden-medium-up` | ✔️       | ✔️     | ✖️     | ✖️    | ✖️      |
| `hidden-large-up`  | ✔️       | ✔️     | ✔️      | ✖️    | ✖️      |
| `hidden-xlarge-up` | ✔️       | ✔️     | ✔️      | ✔️     | ✖️      |


