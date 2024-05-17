<p align="center">
<img src="https://raw.githubusercontent.com/albertodev01/equations/master/assets/equations_logo.svg" height="92" alt="dart_equations logo" />
</p>
<p align="center">An equation-solving library written purely in Dart.</p>
<p align="center">
    <a href="https://codecov.io/gh/albertodev01/equations"><img src="https://codecov.io/gh/albertodev01/equations/branch/master/graph/badge.svg?token=OQFZFHPD3S"/></a>
    <a href="https://github.com/albertodev01/equations/actions"><img src="https://github.com/albertodev01/equations/workflows/equations_ci/badge.svg" alt="CI status" /></a>
    <a href="https://github.com/albertodev01/equations/stargazers"><img src="https://img.shields.io/github/stars/albertodev01/equations.svg?style=flat&logo=github&colorB=blue&label=stars" alt="Stars count on GitHub" /></a>
  <a href="https://pub.dev/packages/equations"><img src="https://img.shields.io/pub/v/equations.svg?style=flat&logo=github&colorB=blue" alt="Stars count on GitHub" /></a>
</p>

---

The `equations` package is used to solve numerical analysis problems with ease. It's purely written in Dart, meaning it has no platform-specific dependencies and doesn't require Flutter to work. You can use `equations`, for example, in a Dart CLI project or a Flutter cross-platform application. Here's a summary of what you can do with this package:

- solve polynomial equations with `Algebraic` types;
- solve nonlinear equations with `Nonlinear` types;
- solve linear systems of equations with `SystemSolver` types;
- evaluate integrals with `NumericalIntegration` types;
- interpolate data points with `Interpolation ` types.

In addition, you can also find utilities to work with:

- Real and complex matrices, using the `Matrix<T>` types;
- Complex number, using the `Complex` type;
- Fractions, using the `Fraction` and `MixedFraction` types.

This package has a type-safe API and requires Dart 3.0 (or higher versions). There is a demo project created with Flutter that shows an example of how this library could be used to develop a numerical analysis application  :rocket:

<p align="center"><img src="https://raw.githubusercontent.com/albertodev01/equations/master/assets/circle_logo.svg" alt="Equation Solver logo" width="55" height="55" /></p>
<p align="center"><a href="https://albertodev01.github.io/equations/">Equation Solver - Flutter web demo</a></p>


---

# Getting Started

Use one of the following classes to find the roots of a polynomial equation (also known as "algebraic equation"). You can use both complex numbers and fractions as coefficients.
