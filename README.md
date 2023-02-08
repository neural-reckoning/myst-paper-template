# myst-paper-template
MyST markdown paper template with actions

## TO DO

* GitHub actions to automate
* Static website how?

## Install node locally

Install [NodeJS](https://nodejs.org/en/download/).

Install myst:

```
npm install -g myst-cli
```

Create config file:

```
myst init
```

## Run node locally

```
myst start
```

## Build docx and pdf

To compile the pdf you need a latex distribution installed with ``latexmk`` package that requires perl to be installed.
For Windows you can use [MikTeX](https://miktex.org/) and [Starbwerry Perl](https://strawberryperl.com/).

```
myst build paper.md
```

Built files will be found in ``_build\exports``.