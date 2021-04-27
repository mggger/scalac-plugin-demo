# Usage

A scalac plugin demo 

```scala
object Test {
  val five = 5
  val amount = five / 0
  def main(args: Array[String]): Unit = {
    println(amount)
  }
}
```

Named as **Test.scala**

## package
```sbt clean assembly``` 

```shell script
scalac -Xplugin:scala-plugin.jar Test.scala
```
