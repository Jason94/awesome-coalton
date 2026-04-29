# Awesome Coalton
<div align="center">
  <p>
    <a href="https://github.com/sindresorhus/awesome"><img src="https://awesome.re/badge-flat.svg"></a>
  </p>
</div>

A curated list of awesome Coalton libraries, tutorials, examples, and applications. 

Because Coalton is so new and undergoing active development, the Coalton ecosystem is less mature than most languages'. Each project on this list is rated as:

- :green_circle: **Beta** - The maintainer keeps up with Coalton changes. Significant portions of the API/project are finished and can be relied on.
- :yellow_circle: **Alpha** - The maintainer keeps up with Coalton changes. The API/project is unfinished, and/or might undergo significant changes.
- :orange_circle: **Experimental** - The maintainer does not keep up with Coalton changes, or the project is intended as a proof-of-concept or experiment. Experimental projects are useful to learn from, but shouldn't be relied on directly.

_(Note: Currently, because Coalton is undergoing active development and doesn't have a versioning scheme, it's hard to label Coalton libraries as "complete." As Coalton's versioning and distribution becomes more organized, these categories will be updated.)_

**Table of Contents**
- [Compilers](#compilers)
- [Databases](#databases)
- [Functional Programming](#functional-programming)
- [Game Development](#game-development)
- [Math](#math)
- [Multithreading](#multithreading)

## Compilers

- :green_circle: [Typing Haskell in Haskell](https://github.com/coalton-lang/coalton/tree/main/examples/thih) - Mark Jones's _Typing Haskell in Haskell_ in Coalton
- :orange_circle: [quilc/discrete](https://github.com/quil-lang/quilc/tree/master/src/discrete) - Discrete gate compilation of unitary operators based on the Ross-Selinger method.
- :orange_circle: [quilc/foust](https://github.com/quil-lang/quilc/tree/master/src/foust) - A quantum circuit optimizer for the QUILC quantum compiler based on Intel's PCOAST algorithm.

## Databases

- :orange_circle: [coalton-db](https://github.com/Jason94/coalton-db) - Typed SQL query builder/runner and an "FRM" to translate between plain Coalton types and database tables.

## Functional Programming

- :green_circle: [coalton-io](https://github.com/Jason94/coalton-io) - Provides an IO monad and [Cats-Effect](https://typelevel.org/cats-effect/) style capability classes for a wide variety of IO effects, including file IO, multithreading, and networking.
- :yellow_circle: [charged-monads](https://github.com/Jason94/charged-monads) - Provides parameterized monads, which are capable of more complex operations. Includes delimited continuations which can change result type (ContT) and stateful computations that can change state type (PtState & PtStateT).

## Game Development

- :yellow_circle: [ECS](https://github.com/Jason94/ECS) - _Entity Component System_, a 2d game library built on top of Raylib.

## Math

- :green_circle: [xmath](https://github.com/coalton-lang/coalton/tree/main/xmath) - Big-floats, computable real numbers, dual numbers, hyperdual numbers, real algebraic numbers, and Fourier transforms.
- :yellow_circle: [fractal](https://github.com/coalton-lang/coalton/tree/main/examples/fractal) - Infinitely zoomable Mandelbrot fractal using big-floats and SDL.

## Multithreading

- :green_circle: [coalton-io](https://github.com/Jason94/coalton-io) - Includes a suite of concurrency tools, including MVars, Atomics Variables, and an STM. The runtime provides structured concurrency and the ability to mask threads to control asynchronous stops.
