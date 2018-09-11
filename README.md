# Scala talk ideas

This repository contains all the ideas for talks I'd wish to see during [Kraków Scala User Group](https://www.meetup.com/Krakow-Scala-User-Group) meetup. 

## Speaker training programme
The list below should be treated as inspiration. There are lots of current topics for all levels of Scala developers. 

I  want to help all the potential speakers prepare the talks. This includes preparing the agenda, slides, meeting for rehearsals and generally making sure that the speaker and the audience have great experience. 

Please let me know here or send an e-mail to [Kraków Scala User Group organizers](krakow-scala-organizers@googlegroups.com) if you'd like to participate.

## List of talk titles

### Beginner level

| Title                                                          | Additional keywords           | Deadline |
|----------------------------------------------------------------|-------------------------------| -----|
| Integration testing with [testcontainers-scala](https://github.com/testcontainers/testcontainers-scala) |            |        Oct 2018 |
| The landscape of testing libraries in Scala                    | [scalatest](http://www.scalatest.org/), [specs2](https://etorreborre.github.io/specs2/), [testz](https://github.com/scalaz/testz), [minitest](https://github.com/monix/minitest), [utest](https://github.com/lihaoyi/utest)           | Oct 2018
| I just want to compile it! aka “[SBT](https://www.scala-sbt.org/) made simple”               |            | Oct 2018
| Formatting Scala code using [scalafmt](https://scalameta.org/scalafmt/)                           |            |Oct 2018
| Building reactive UIs with [Scala.js](https://www.scala-js.org/) and [AkkaUI](https://github.com/pishen/akka-ui)                 |            |Oct 2018
| How do the [Scala collections](https://docs.scala-lang.org/overviews/collections/overview.html) work?                             |            |Oct 2018
| Getting metrics out of your Scala service                      | [kamon](https://github.com/kamon-io/Kamon), [prometheus](https://prometheus.io/), [grafana](https://grafana.com/)           |Oct 2018
| Being Scala DevOps                                             | [orkestra](https://orkestra.tech/)           |Oct 2018
| [Scala 3](https://www.scala-lang.org/blog/2018/04/19/scala-3.html) as your first Scala                                    |            |Oct 2018
| Building React components in Scala.js                          | [scalajs-react](https://japgolly.github.io/scalajs-react/)           | Oct 2018
| Stop using exceptions now                                      | [Try](https://www.scala-lang.org/api/2.12.3/scala/util/Try.html)           |Oct 2018
| To mock or not to mock in your scala tests                     |            |Oct 2018
| Using gRPC in Scala                                            | [ScalaPB](https://scalapb.github.io/)            | Nov 2018
| The magic behind [pattern matching](https://docs.scala-lang.org/tour/pattern-matching.html)                              |            | Nov 2018
| Polymorphism vs composition in Scala                           |            |Nov 2018
| Builder pattern in Scala - implementation techniques           |            |Nov 2018
| Introduction to Scala ecosystem                                |            |Nov 2018
| Stateful computations with [Flink](https://flink.apache.org/)                        |            |Nov 2018
| Integrating with [RxJava](https://github.com/ReactiveX/RxJava) APis in Scala                          |            |Nov 2018
| Power up your code with [Option](https://www.scala-lang.org/api/current/scala/Option.html)                                 |            |Nov 2018
| The biggest pains of beginner Scala developer                  |            | Dec 2018
| Handling dates & times in Scala web applications               | [scala-js-java-time](https://github.com/scala-js/scala-js-java-time)           | Dec 2018
| Handling geo data using [GeoTrellis](https://geotrellis.io/)                             |            | Dec 2018
| Integrating with [Kafka](https://kafka.apache.org/) using [Akka](https://akka.io/)                              | [alpakka-kafka](https://github.com/akka/alpakka-kafka)            | Dec 2018

### Intermediate level
| Title                                                          | Additional keywords           | Deadline |
|----------------------------------------------------------------|-------------------------------|----------|
| IO vs Future - why should I care?                              | [cats-effect](https://github.com/typelevel/cats-effect), [zio](https://github.com/scalaz/scalaz-zio), [Future](https://www.scala-lang.org/api/2.12.3/scala/concurrent/Future.html)       | Jan 2019
| 7 sins of implicits                                            | [implicit parameters](https://docs.scala-lang.org/tour/implicit-parameters.html), [implicit conversions](https://docs.scala-lang.org/tour/implicit-conversions.html), [design patterns](http://www.lihaoyi.com/post/ImplicitDesignPatternsinScala.html)       |Jan 2019
| Getting started with [TensorFlow in Scala](http://platanios.org/tensorflow_scala/)                       |        |Jan 2019
| Practical introduction to lenses                               | [monocle](https://github.com/julien-truffaut/Monocle), [quicklens](https://github.com/adamw/quicklens)       | Jan 2019
| Benchmarking scala code                                        | [sbt-jmh](https://github.com/ktoso/sbt-jmh)       | Jan 2019
| Introduction to [Linkerd service mesh](https://linkerd.io/)                           |        | Feb 2019
| Handling state with Monix [Atomic](https://monix.io/docs/2x/execution/atomic.html) and [Scheduler](https://monix.io/docs/2x/execution/scheduler.html)                 |        |Feb 2019
| Why do we need Nothing type?                                   |        |Feb 2019
| When should you write your own macro?                          | [scala macros](https://www.scala-lang.org/blog/2017/11/27/macros.html), [scalameta](https://scalameta.org/), [scala 3](https://www.scala-lang.org/blog/2018/04/19/scala-3.html)       |Feb 2019
| Handling distributed transactions in microservice world        |        |Feb 2019
| Why do I need refinment types?                                 | [refined](https://github.com/fthomas/refined)       | March 2019
| Real-world cases for property-based tests                      | [scalacheck](https://www.scalacheck.org/)       | March 2019
| Serializing JSON using Circe auto, semi-auto and manual modes  | [circe codec](https://circe.github.io/circe/codec.html)       | Apr 2019
| [Aux pattern](https://gigiigig.github.io/posts/2015/09/13/aux-pattern.html) explained                                          |        | Apr 2019
| Phantom types explained                                        |        |  Apr 2019
| Refactoring and linting with [Scalafix](https://scalacenter.github.io/scalafix/)                          |        | Apr 2019
| Configuring your app with [pureconfig](https://pureconfig.github.io/)                           |        | Apr 2019
| Getting closer to bare metal with [Scala Native](https://pureconfig.github.io/)                 |        | May 2019
| Developing APIs with a sip of [Sangria](https://sangria-graphql.org/) and [GraphQL](https://graphql.org/learn/)              |        | May 2019 
| Why do you need [Alpakka](https://github.com/akka/alpakka)?                                       |        | May 2019
| What’s new in [Scala 2.13 collections](https://www.scala-lang.org/blog/2017/02/28/collections-rework.html)?                          |        | May 2019
| Using [Finagle](https://twitter.github.io/finagle/) and [fintrospect](http://fintrospect.io/) to create documented Web APIs                                  |        | May 2019
| [Kafka 2.0](https://kafka.apache.org/downloads#2.0.0) in Scala                              | | May 2019

### Advanced level
| Title                                                          | Additional keywords           |Deadline|
|----------------------------------------------------------------|-------------------------------|--------|
| The HTTP wars - how to choose HTTP lib for your Scala service  | [akka-http](https://doc.akka.io/docs/akka-http/current/), [finagle](https://twitter.github.io/finagle/), [cask](https://github.com/lihaoyi/cask), [http4s](https://http4s.org/), [typedapi](https://github.com/pheymann/typedapi), [colossus](https://github.com/tumblr/colossus), [finatra](https://twitter.github.io/finatra/)            | Jun 2019
| Building type-level web APIs using [typedapi](https://github.com/pheymann/typedapi)                    |            | Jun 2019
| Deep dive into [Scala collections](https://docs.scala-lang.org/overviews/collections/overview.html)                               |            | Jun 2019
| Abstracting your needs with [cats-effect](https://github.com/typelevel/cats-effect), [cats-mtl](https://github.com/typelevel/cats-mtl) and [meow-mtl](https://github.com/oleg-py/meow-mtl) |            | Jun 2019
| Should we fear [Scala 3](https://www.scala-lang.org/blog/2018/04/19/scala-3.html)?                                        |            | Jul 2019
| Trampolines and stack safety                                   |            | Jul 2019
| [GraalVM](https://www.graalvm.org/) and Scala                                              |            | Jul 2019
| Introduction to concurrency using Scala & Cats                 | [cats-effect](https://github.com/typelevel/cats-effect)           | Jul 2019
| Introduction to [doobie](https://tpolecat.github.io/doobie/) for data access                         |            | Jul 2019




