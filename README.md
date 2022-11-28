# Confetti Extension For Quarto

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)

Send some 🎊 confetti 🎊 through your presentation.

This extension uses a JavaScript library called: **[canvas-confetti](https://github.com/catdad/canvas-confetti)**.

## Installation

To install this extension:

```
quarto install extension ArthurData/quarto-confetti
```

> Requires Quarto Version 1.2.0 or later...

## Usage

Add this extension to your YAML configuration:

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
```

## Options

_More details to come..._

More details about the options are available here: [canvas-confetti](https://github.com/catdad/canvas-confetti#options)

## Example

Use the `c` to send some 🎊🎊

<img src="example.gif" width="100%"/></a>
