title="Test 2"
date="2018-07-20"
tags=["biggertag", "test"]
---
# Title
Some text

## Title 2
Here is some code:
```scala
def function[A](a: Seq[Seq[A]], b: Int = 12, c: String = "defaultValue"): Unit = {
  println(a)
  println(b)
  println(c)
}

def thisFunctionDefinitionIsWayTooLong[A, B <: Any, C >: Null <: AnyRef, D <: C](a: A, b: B, c: C, d: D = Magic.getDefaultValueFor[D, Any](d, "20" :: "20")): Magic[mutable.Buffer[D], A, B, C, List[String]] = {
  return null; // Do *not* ever do this in prod!
}
```

Some very long line here. Some very long string here. Some very long string here. Some very long string here. Some very long string here. Some very long string here. Some very long string here. Some very long string here. Some very long string here. Some very long string here. Some very long string here. Some very long string here.  

### Subtitle
Java:
```java
import java.lang.Object;
public class String extends Object {
  private final byte[] data;

  String(byte[] data) {
    this.data = data;
  }
}
```

## Title 3

- list
- list
- still list
- list, again

Enjoy :)
