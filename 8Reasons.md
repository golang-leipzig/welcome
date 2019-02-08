# Eight reasons for Go

Eight reasons (or bold claims), why I think, Go will be successful in the
future - maybe as a lightning talk.

> Golang and Cloud Leipzig, 2019-02-08, Basislager

## TOC

* [Simplicity is attractive](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#simplicity-is-attractive)
* [Active community](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#active-community)
* [Readability and the standard library](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#readability-and-the-standard-library)
* [The net/http package](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#the-nethttp-package)
* [No callbacks](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#no-callbacks)
* [Emphasis on Composition](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#emphasis-on-composition)
* [Tools welcome](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#tools-welcome)
* [Fun](https://github.com/golang-leipzig/welcome/blob/master/8Reasons.md#fun)

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

## Readability and the standard library

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

