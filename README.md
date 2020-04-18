# Elm-Responsive-UI

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

These modules provide a simple and repeatable way of 'doing Resppnsive' and is intended for use with [ Elm-UI ](https://package.elm-lang.org/packages/mdgriffith/elm-ui/latest/ "The best UI package for Elm").


## Install
```bash
$ git clone https://github.com/phollyer/elm-responsive-ui.git
```
Then you can either:

    1. Copy the files in `src` to your project, or
    2. Tell the Elm compiler where to find the files by adding the relative path
        from your Elm project, to `source-directories` in your `elm.json` file.

# Design Goals

For some time I've wanted a repeatable way of doing responsive
designs. A way to help me design for mobile first, and then adjust my views as
necessary for larger screens.

I have previously used
[Twitter Bootstrap](https://getbootstrap.com/) and
[Zurb Foundation](https://get.foundation), but have long since dropped using
CSS in favour of
[Elm-UI](https://package.elm-lang.org/packages/mdgriffith/elm-ui/latest). As a
result, I want a pure Elm way of reacting to different size screens and
orientations, and while requirements may change from project to project, I
want the process to remain the same. Constantly, re-inventing the wheel isn't
something that I feel should be necessary for this particular problem.


# Be Careful

These modules have evolved from a current project. As a result, it is still an
experimental work in progress, so more functions could be added and some
functions may disappear or change. Therefore, **the usual caveats apply with
regard to using an experimental package in your projects**.


# Feedback/Collaboration

Feedback and/or collaboration is welcome. Initially, please start an issue on
Github, post a question on
[Discourse](https://discourse.elm-lang.org/u/paulh/) (I try to read it every
day), or private message me on
[Discourse](https://discourse.elm-lang.org/u/paulh/).


# What is Responsiveness?

When I think about responsiveness, I think of scaling fonts, spacing, padding
etc, and changing layouts according to screen size and orientation. This
module is intended to address those types of problems simply and intuitively.

# Usage

TODO


