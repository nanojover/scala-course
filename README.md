# Scala course

This is a course crafted for OO developers that want to learn Scala &
functional programming.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [Scala course](#scala-course)
    - [Sections](#sections)
        - [Basics 1](#basics-1)
        - [Basics 2](#basics-2)
        - [Abstraction](#abstraction)
        - [Typeclasses](#typeclasses)
    - [exercises](#exercises)
        - [tags](#tags)
        - [compiling](#compiling)
    - [building](#building)

<!-- markdown-toc end -->


## Sections

This course has the following sections, delivered during two days
normally.

### Basics 1

Learn the basics of the language, the most interesting features and
how to deal with data usign ADTs.

### Basics 2

Learn how to apply pattern matching and recursion to solve problems on
algebraic data types.

### Abstraction

In this section we'll start to dig deeper in the functional
programming aspects of Scala, and to learn new functional
abstractions.

### Typeclasses

In this section we'll learn how to implement _Ad hoc polymorphism_ in
Scala using typeclasses, and all the benefits it provides.

## exercises

For the exercises, go to the `exercises` folder & select the exercise
you want to do.

### tags

Then, checkout the tag from the description (or the solution if you
want to see it).

| description               | solution               |
|---------------------------|------------------------|
| `exercise1.1-description` | `exercise1.1-solution` |
| `exercise1.2-description` | `exercise1.2-solution` |
| `exercise2.1-description` | `exercise2.1-solution` |
| `exercise2.2-description` | `exercise2.2-solution` |
| `exercise2.3-description` | `exercise2.3-solution` |
| `exercise2.4-description` | `exercise2.4-solution` |
| `exercise2.5-description` | `exercise2.5-solution` |
| `exercise2.6-description` | `exercise2.6-solution` |
| `exercise3.1-description` | `exercise3.1-solution` |
| `exercise3.2-description` | `exercise3.2-solution` |
| `exercise3.3-description` | `exercise3.3-solution` |
| `exercise3.4-description` | `exercise3.4-solution` |
| `exercise4.1-description` | `exercise4.1-solution` |
| `exercise4.2-description` | `exercise4.2-solution` |
| `exercise4.3-description` | `exercise4.3-solution` |
| `exercise5.1-description` | `exercise5.1-solution` |
| `exercise5.2-description` | `exercise5.2-solution` |
| `exercise5.3-description` | `exercise5.3-solution` |
| `exercise5.4-description` | `exercise5.4-solution` |
| `exercise5.5-description` | `exercise5.5-solution` |

### compiling

You can compile the exercises with one of:

```sbt
$ ./sbt exercise1/compile
$ ./sbt exercise2/compile
$ ./sbt exercise3/compile
$ ./sbt exercise4/compile
$ ./sbt exercise5/compile
```

## building

To build the slides for the course you'll need `pandoc`. Get it from
your package manager.

Once you have it:

```sh
$ make all
```

This will generate HTMLs for the presentation in the `docs/tut-out`
presentation.
