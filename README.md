# myst-paper-template
MyST markdown paper template with actions

Use this repository as a starting point (template) for writing a paper using [MyST](https://myst.tools).

1. Click "Use this template" at the top. This will prompt you to create a new repository of your own based on this one.
2. Go to your repository, edit the paper.md file from within GitHub (click the file, then click the pen icon to edit it). You can preview what the markdown will look like when converted although the final output will be slightly different.
3. Commit your changes.
4. GitHub will automatically build the project to docx, LaTeX and PDF format and upload them as a release "latest". You can find this at [releases/tag/latest/](https://github.com/neural-reckoning/myst-paper-template/releases/tag/latest).

You can track the build process at [actions/](https://github.com/neural-reckoning/myst-paper-template/actions) and if there are errors you can check the logs there.

Alternatively, you can run locally (see below) but you need to install some tools.

## TO DO

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