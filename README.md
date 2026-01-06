# autodiff-from-scratch

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-educational-lightgrey.svg)

A minimal automatic differentiation engine inspired by Andrej Karpathy’s [micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0).
This repository implements a scalar-valued autograd system from scratch, supporting reverse-mode automatic differentiation (backpropagation) over a dynamically constructed computation graph.

## Features
- Scalar-based automatic differentiation
- Dynamic computation graph construction
- Reverse-mode autodiff (backpropagation)

## Motivation
The goal of this project is to build an autograd engine from scratch and understand how modern deep learning frameworks compute gradients and propagate them through computation graphs.

## Scope and Limitations
- Scalars only
- CPU-only

## References
- Andrej Karpathy’s [micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0).
- [Core concepts in reverse-mode automatic differentiation](https://auto-ed.readthedocs.io/en/latest/mod3.html)

## License
MIT
