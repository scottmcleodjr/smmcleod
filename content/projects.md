---
title: "Projects"
description: "My personal software projects."
---

You can find all of my public repos on [GitHub](https://github.com/scottmcleodjr?tab=repositories).

Here are a few of my favorites:

## K3GDS REKL

[Source](https://github.com/scottmcleodjr/rekl) · Go · BSD 2-Clause

![REKL Demo GIF](/images/reklDemo.gif)

An interactive repl-like experience for amateur radio morse code (CW) keying. REKL includes support for saved memory messages and dynamic speed adjustments.

## GebVM

[Source](https://github.com/scottmcleodjr/gebvm) · Go · BSD 2-Clause

```sh
> # Pull the code
> go get github.com/scottmcleodjr/gebvm
>
> # Build the project
> go build github.com/scottmcleodjr/gebvm
>
> # Run hellow_world.geb
> ./gebvm ~/go/src/github.com/scottmcleodjr/gebvm/examples/hello_world.geb
Hello, World!
```

An 8-bit register-based virtual machine. GebVM executes a bytecode with 29 supported instructions on 65K memory.

## cl-lambdacalc

[Source](https://github.com/scottmcleodjr/cl-lambdacalc) · Common Lisp · MIT

```lisp
> (define-lc-func four "Afx.f(f(f(fx)))")
#<FUNCTION (LAMBDA (F)) {52DF583B}>

> (church-numeral-to-number (lc-succ #'four))
5

> (church-numeral-to-number (funcall (lc-expt #'four) #'four))
256
```

A library that allows you to define Lisp functions using Lambda Calculus syntax. cl-lambdacalc also includes symbols for boolean logic and church numerals.

## wolfram-image

[Source](https://github.com/scottmcleodjr/wolfram-image) · Common Lisp · MIT

![wolfram-image Example Image](/images/image-rule-150.png)

A library that creates images of the Wolfram Automata. The library provides configuration for colors, sizes, and rule.

## K3GDS Arduino Keyer

[Source](https://github.com/scottmcleodjr/k3gds_keyer) · C++ (Arduino) · MIT

A morse code keyer designed for the Arduino platform with support for speed adjustment and a stored message. The keyer is designed to be simple enough for any radio amateur to build.
