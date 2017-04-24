# Go Python Way to Scala while CPPing Java

Python one liners - First of all you are in for a ride!

```golang
type SomeName struct {
}

func (SomeName*sm) SomeMethodName() {
}

func main() {
    var someVariable int = 0;
}
```

```scala
object SomeName {
/*
*/
//
    def main(args: Array[String]){
          val someVariable: Int = 0; // Immtable variable
          var someOtherVariable:Int = 0; // Mutable Variable
          println(args)
    }
}
```
Alright the aim is to taste the scala sugar.
```scala
object someName extends App {
    val someVariable: Integer = 0;
    println(args)
}
```
Interesting thing one can see about over here is a typed tuple `val (myVar1: Int, myVar2: String) = Pair(40, "Foo")`, this Pair reminds me of the pair from cpp `pair<int,int> someName;`.

```python
class someName:
    def __init__(self,someArgument):
        self.someVariable=someArgument
    
    def someMethod(self):
        pass
```


```scala
class someName(val someArgument: Int) {
    val someVariable: Int = someArgument
    
    def someMethod(){
    }
}
```
Sadly `val`ed variable is immutable :( .

> In scala everything is a function.

# References
1. _https://datasciencevademecum.wordpress.com/2016/01/28/6-points-to-compare-python-and-scala-for-data-science-using-apache-spark/_
