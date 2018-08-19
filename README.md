# Scala talk ideas

This repository contains all the ideas for talks I'd wish to see during [Kraków Scala User Group](https://www.meetup.com/Krakow-Scala-User-Group) meetup. 

## Speaker training programme
The list below should be treated as inspiration. There are lots of current topics for all levels of Scala developers. 

I  want to help all the potential speakers prepare the talks. This includes preparing the agenda, slides, meeting for rehearsals and generally making sure that the speaker and the audience have great experience. 

Please let me know here or send an e-mail to [Kraków Scala User Group organizers](krakow-scala-organizers@googlegroups.com) if you'd like to participate.

## List of talk titles

### Beginner level

| Title                                                          | Additional keywords           |
|----------------------------------------------------------------|-------------------------------|
| Integration testing with [testcontainers-scala](https://github.com/testcontainers/testcontainers-scala) |            |         |
| The landscape of testing libraries in Scala                    | [scalatest](http://www.scalatest.org/), [specs2](https://etorreborre.github.io/specs2/), [testz](https://github.com/scalaz/testz), [minitest](https://github.com/monix/minitest)           |
| I just want to compile it! aka “[SBT](https://www.scala-sbt.org/) made simple”               |            |
| Formatting Scala code using [scalafmt](https://scalameta.org/scalafmt/)                           |            |
| Building reactive UIs with [Scala.js](https://www.scala-js.org/) and [AkkaUI](https://github.com/pishen/akka-ui)                 |            |
| How do the [Scala collections](https://docs.scala-lang.org/overviews/collections/overview.html) work?                             |            |
| Getting metrics out of your Scala service                      | [kamon](https://github.com/kamon-io/Kamon), [prometheus](https://prometheus.io/), [grafana](https://grafana.com/)           |
| Being Scala DevOps                                             | [orkestra](https://orkestra.tech/)           |
| [Scala 3](https://www.scala-lang.org/blog/2018/04/19/scala-3.html) as your first Scala                                    |            |
| Building React components in Scala.js                          | [scalajs-react](https://japgolly.github.io/scalajs-react/)           |
| Stop using exceptions now                                      | [Try](https://www.scala-lang.org/api/2.12.3/scala/util/Try.html)           |
| To mock or not to mock in your scala tests                     |            |
| Using gRPC in Scala                                            | [ScalaPB](https://scalapb.github.io/)            |
| The magic behind [pattern matching](https://docs.scala-lang.org/tour/pattern-matching.html)                              |            |
| Polymorphism vs composition in Scala                           |            |
| Builder pattern in Scala - implementation techniques           |            |
| Introduction to Scala ecosystem                                |            |
| Stateful computations with [Flink](https://flink.apache.org/)                        |            |
| Integrating with [RxJava](https://github.com/ReactiveX/RxJava) APis in Scala                          |            |
| Power up your code with [Option](https://www.scala-lang.org/api/current/scala/Option.html)                                 |            |
| The biggest pains of beginner Scala developer                  |            |
| Handling dates & times in Scala web applications               | [scala-js-java-time](https://github.com/scala-js/scala-js-java-time)           |
| Handling geo data using [GeoTrellis](https://geotrellis.io/)                             |            |
| Integrating with [Kafka](https://kafka.apache.org/) using [Akka](https://akka.io/)                              | [alpakka-kafka](https://github.com/akka/alpakka-kafka)            |

### Intermediate level
| Title                                                          | Additional keywords           |
|----------------------------------------------------------------|-------------------------------|
| IO vs Future - why should I care?                              | [cats-effect](https://github.com/typelevel/cats-effect), [zio](https://github.com/scalaz/scalaz-zio), [Future](https://www.scala-lang.org/api/2.12.3/scala/concurrent/Future.html)       |
| 7 sins of implicits                                            | [implicit parameters](https://docs.scala-lang.org/tour/implicit-parameters.html), [implicit conversions](https://docs.scala-lang.org/tour/implicit-conversions.html), [design patterns](http://www.lihaoyi.com/post/ImplicitDesignPatternsinScala.html)       |
| Getting started with [TensorFlow in Scala](http://platanios.org/tensorflow_scala/)                       |        |
| Practical introduction to lenses                               | [monocle](https://github.com/julien-truffaut/Monocle), [quicklens](https://github.com/adamw/quicklens)       |
| Benchmarking scala code                                        | [sbt-jmh](https://github.com/ktoso/sbt-jmh)       |
| Introduction to [Linkerd service mesh](https://linkerd.io/)                           |        |
| Handling state with Monix [Atomic](https://monix.io/docs/2x/execution/atomic.html) and [Scheduler](https://monix.io/docs/2x/execution/scheduler.html)                 |        |
| Why do we need Nothing type?                                   |        |
| When should you write your own macro?                          | [scala macros](https://www.scala-lang.org/blog/2017/11/27/macros.html), [scalameta](https://scalameta.org/), [scala 3](https://www.scala-lang.org/blog/2018/04/19/scala-3.html)       |
| Handling distributed transactions in microservice world        |        |
| Why do I need refinment types?                                 | [refined](https://github.com/fthomas/refined)       |
| Real-world cases for property-based tests                      | [scalacheck](https://www.scalacheck.org/)       |
| Serializing JSON using Circe auto, semi-auto and manual modes  | [circe codec](https://circe.github.io/circe/codec.html)       |
| [Aux pattern](https://gigiigig.github.io/posts/2015/09/13/aux-pattern.html) explained                                          |        |
| Phantom types explained                                        |        |
| Refactoring and linting with [Scalafix](https://scalacenter.github.io/scalafix/)                          |        |
| Configuring your app with [pureconfig](https://pureconfig.github.io/)                           |        |
| Getting closer to bare metal with [Scala Native](https://pureconfig.github.io/)                 |        |
| Developing APIs with a sip of [Sangria](https://sangria-graphql.org/) and [GraphQL](https://graphql.org/learn/)              |        |
| Why do you need [Alpakka](https://github.com/akka/alpakka)?                                       |        |
| What’s new in [Scala 2.13 collections](https://www.scala-lang.org/blog/2017/02/28/collections-rework.html)?                          |        |
| Using [Finagle](https://twitter.github.io/finagle/) and [fintrospect](http://fintrospect.io/) to create documented Web APIs                                  |        |
| [Kafka 2.0](https://kafka.apache.org/downloads#2.0.0) in Scala                              | | 

### Advanced level
| Title                                                          | Additional keywords           |
|----------------------------------------------------------------|-------------------------------|
| The HTTP wars - how to choose HTTP lib for your Scala service  | [akka-http](https://doc.akka.io/docs/akka-http/current/), [finagle](https://twitter.github.io/finagle/), [cask](https://github.com/lihaoyi/cask), [http4s](https://http4s.org/), [typedapi](https://github.com/pheymann/typedapi)            |
| Building type-level web APIs using [typedapi](https://github.com/pheymann/typedapi)                    |            |
| Deep dive into [Scala collections](https://docs.scala-lang.org/overviews/collections/overview.html)                               |            |
| Abstracting your needs with [cats-effect](https://github.com/typelevel/cats-effect), [cats-mtl](https://github.com/typelevel/cats-mtl) and [meow-mtl](https://github.com/oleg-py/meow-mtl) |            |
| Should we fear [Scala 3](https://www.scala-lang.org/blog/2018/04/19/scala-3.html)?                                        |            |
| Trampolines and stack safety                                   |            |
| [GraalVM](https://www.graalvm.org/) and Scala                                              |            |
| Introduction to concurrency using Scala & Cats                 | [cats-effect](https://github.com/typelevel/cats-effect)           |
| Introduction to [doobie](https://tpolecat.github.io/doobie/) for data access                         |            |




