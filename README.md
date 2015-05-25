# study-category-theory
Study Functional Programming and Category Theory with [Scala](http://www.scala-lang.org/).

# Functional Programming
> Functional programming is a programming paradigm - a style of building the structure and elements of computer programs - that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data. It is a declarative programming paradigm, which means programming is done with expressions. In functional code, the output value of a function depends only on the arguments that are input to the function, so calling a function f twice with the same value for an argument x will produce the same result f(x) each time. Eliminating side effects, i.e. changes in state that do not depend on the function inputs, can make it much easier to understand and predict the behavior of a program, which is one of the key motivations for the development of functional programming.
-- <quote>[Wikipedia](http://en.wikipedia.org/wiki/Functional_programming)</quote>

> Functional programming is a restriction on how we write programs, but not on what programs we can write - we can still use side-effects. (ie. write to a file, printing to the console, reading user input, drawing on a screen, alter state). As it turns out that accepting this restriction is tremendously beneficial because of the increase in that we gain `modularity` from programming with pure functions. Because of their modularity, pure functions are easier to test, to reuse, to parallelize, to generalize, and to reason about. 
-- <quote>[Functional Programming in Scala](http://www.manning.com/bjarnason/)</quote>

# Video
- [Youtube - Brian Beckman: Don't fear the Monad](https://www.youtube.com/watch?v=ZhuHCtR3xq8)
- [Youtube - Brian Beckman: The Zen of Stateless State - The State Monad](https://www.youtube.com/watch?v=XxzzJiXHOJs)
- [Youtube - Expert to Expert: Brian Beckman and Erik Meijer - Inside the .NET Reactive Framework (Rx)](https://www.youtube.com/watch?v=looJcaeboBY)
- [YouTube - Introduction to Type-Level Programming](https://www.youtube.com/watch?v=WZOzxAP8NpI)
- [YouTube - Type-Level Programming: The Subspace of Scala](https://www.youtube.com/watch?v=MjzBPIvgB24)
- [YouTube - PNWS 2014 - What every (Scala) programmer should know about category theory](https://www.youtube.com/watch?v=W67LYX_1J_M)
- [YouTube - Miles Sabin - Shapeless: Exploring Generic Programming in Scala](https://www.youtube.com/watch?v=GDbNxL8bqkY)
- [YouTube - Jared Roesch - Demystifying Shapeless: An Exploration of Dependent Types in Scala](https://www.youtube.com/watch?v=VF-ISUiXIY0)
- [YouTube - Scalaz - The good parts](https://www.youtube.com/watch?v=jPdHQZnF56A)

# Blogs
- [CakeSolutions - Category theory patterns in Scala](http://www.cakesolutions.net/teamblogs/category-theory-patterns-in-scala)

# Slides
- [Category theory for beginners](http://www.slideshare.net/kenbot/category-theory-for-beginners)

# Scala
> Scala is an object-functional programming language for general software applications. Scala has full support for functional programming and a very strong static type system. This allows programs written in Scala to be very concise and thus smaller in size than other general-purpose programming languages. Many of Scala's design decisions were inspired by criticism of the shortcomings of [Java]().
-- <quote>[Wikipedia](http://en.wikipedia.org/wiki/Scala_(programming_language))</quote>

# Scalaz
> Scalaz is a Scala library for functional programming. It provides purely functional data structures to complement those from the Scala standard library. It defines a set of foundational type classes (e.g. Functor, Monad) and corresponding instances for a large number of data structures.
-- <quote>[Scalaz](https://github.com/scalaz/scalaz)</quote>

## Links
- [Learning Scalaz](http://eed3si9n.com/learning-scalaz/)

## Video
- [Youtube - Learning Scalaz](https://www.youtube.com/watch?v=jyMIvcUxOJ0)
- [Youtube - Scalaz - The good parts](https://www.youtube.com/watch?v=jPdHQZnF56A)
- [Youtube - Scalaz - The State Monad](https://www.youtube.com/watch?v=Jg3Uv_YWJqI)
- [Youtube - Scalaz for the rest of us at Yelp](https://www.youtube.com/watch?v=kcfIH3GYXMI)
- [Youtube - Scalaz for the rest of us](https://www.youtube.com/watch?v=J3Mrwp_BzrI)
- [Youtube - Explorations in Variance](https://www.youtube.com/watch?v=VZWLRepyNvo)


# Shapeless
> Shapeless is a type class and dependent type based generic programming library for Scala.
-- <quote>[Shapeless](https://github.com/milessabin/shapeless)</quote>

## HList
> HList provides many operations to create and manipulate heterogenous lists (HLists) whose length and element types are known at compile-time.

## Youtube 
- [Youtube - Shapeless: Exploring Generic Programming in Scala](https://www.youtube.com/watch?v=GDbNxL8bqkY)

# Slick
> [Slick](http://slick.typesafe.com) is a modern database query and access library for Scala. It allows you to work with stored data almost as if you were using Scala collections while at the same time giving you full control over when a database access happens and which data is transferred. You can write your database queries in Scala instead of SQL, thus profiting from the static checking, compile-time safety and compositionality of Scala. Slick features an extensible query compiler which can generate code for different backends. From version 3.0 and up, Slick is reactive and asynchronous. It has a lot of [new features](http://slick.typesafe.com/news/2015/04/29/slick-3.0.0-released.html) most notably: A new API for composing and executing database actions, support for the [Reactive Streams API](http://www.reactive-streams.org) for streaming results from the database and improved configuration of database connections via Typesafe Config, including built-in support for HikariCP.
-- <quote>[Slick](http://slick.typesafe.com)</quote>

## Video
- [Youtube - Database access with Slick](https://www.youtube.com/watch?v=BDVpvneFNeI)

## Blogs
- [Cool Monday: HList and Shapeless](http://www.edofic.com/posts/2012-10-29-hlist-shapeless.html)
