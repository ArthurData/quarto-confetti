# Confetti Extension For Quarto

Send some 🎊 confetti 🎊 through your presentation.

This extension uses a JavaScript library called: **[canvas-confetti](https://github.com/catdad/canvas-confetti)**.

## Installation

To install this extension:

```
quarto add ArthurData/quarto-confetti
```

> Requires Quarto Version 1.2.269 or later...

## Usage

First, create a project for your presentation:

```
quarto create-project prezwithconfetti
cd prezwithconfetti
```

Add this extension to the project:

```
quarto add ArthurData/quarto-confetti
```

Then, modify the YAML header of your presentation:

```
---
title: "My presentation"
format:
  revealjs: default
revealjs-plugins:
  - confetti
---
```

This will activate the confetti extension in your revealjs presentation with **default parameters**.

You can also personalise your confetti:

```
---
title: "My presentation"
format:
  revealjs:
    confetti:
      particleCount: 150
      angle: 90
      spread: 360
      startVelocity: 25
      gravity: 0.65
      drift: 0
      ticks: 400
      colors: ["#0366fc", "#f54281", "#1fd14f"]
      scalar: 0.7
revealjs-plugins:
  - confetti
---
```

## Options

More details about the options are available here: [canvas-confetti](https://github.com/catdad/canvas-confetti#options)

## Example

Use the `c` to send some 🎊🎊

<img src="example.gif" width="100%"/></a>

View an example: [https://ArthurData.github.io/quarto-confetti/](https://ArthurData.github.io/quarto-confetti/)
