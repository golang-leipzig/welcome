# Ten reasons for Go

* Golang and Cloud Leipzig, 2019-02-08, Basislager

Eight reasons (or bold claims), why I think, Go will be successful in the
future.

## TOC

* Similicity is attractive
* Active community
* The standard library
* The net/http package
* No callbacks
* Emphasis on Composition
* Tools welcome
* Fun

## Simplicity is attractive

* When Java appeared, it had simpler memory management and promised code reuse (and delivered).
* Simplicity can be attractive.
* Go thrives on simplicity - sometimes too much, so there is duplication and
  boilerplate (but [worse can be
better](https://en.wikipedia.org/wiki/Worse_is_better)).
* A simple language is faster to learn.
* [play.golang.org](https://play.golang.org)

## Active community

* The community seems to grow and the number of tools and libraries are growing.
* [tinygo](https://fosdem.org/2019/schedule/event/bof_tinygo/), Go for microcontrollers, WASM target.
* Gopherdata works on gonum, a numpy like packages, tfgo (tensorflow integration)
* Availability books, tutorials (e.g. justforfunc), a million developers.
* Lots of discussions, open source project and process, no fast additions to the language.

## The standard library

* Have you ever read through the Java standard library? Yes, no, maybe? Reading
  of Go standard library is encouraged.
* I regularly try to read code of some projects
  ([stdlib](https://github.com/golang/go),
[go4](https://github.com/go4org/go4),
[cayley](https://github.com/cayleygraph/cayley), ...).
* Encouraging to just read code (and expectation or readability) is encouraging on its own.

## The net/http package

* Writing servers has successively become cheaper. With Go, the basics boil
  down to a few lines. It's good enough. It's also fast enough to start.
* Everyone wants microservices. With Go you could start even without containers and orchestration.

## No callbacks

* Sequential code, no callback based concurrency (node, twisted).
* Simple primitives.
* Encourages to keep channels out of API if possible.

## Emphasis on Composition

* Composition is hard.
* Go separates behaviour (interfaces) and structure (structs) more. In the best case, network effect of small components that can be plugged together.
* The io.Reader and io.Writer interfaces.

## Tools welcome

* Go encourages tools, linters, refactoring tools, code generation (api stubs, structs, ...).
* Go makes it easy to work on Go code.
* One reason go fmt exists is to have stylisticly equivalent output from machine and human.

## Fun

* Go is fun - for some.

