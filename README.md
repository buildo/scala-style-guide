# scala-style-guide
A shared scala style guide for buildo projects

## Usage with scalastyle sbt plugin
Add the [scalastyle sbt plugin](http://www.scalastyle.org/sbt.html), by adding

```scala
addSbtPlugin("org.scalastyle" %% "scalastyle-sbt-plugin" % "0.8.0")
```

to `project/plugins.sbt`.

Then in `build.sbt` add

```scala
(scalastyleConfigUrl in Compile) := Some(url("https://raw.githubusercontent.com/buildo/scala-style-guide/master/scalastyle-config.xml"))
```
