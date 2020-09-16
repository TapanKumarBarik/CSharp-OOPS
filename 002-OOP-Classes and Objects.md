# inside program class

```python
using System;

namespace MyApplication
{
  class Car
  {
    string color = "red";

    static void Main(string[] args)
    {
      Car myObj = new Car();
      Console.WriteLine(myObj.color);
    }
  }
}
```
# multiple objexts 
```python
using System;

namespace MyApplication
{
  class Car
  {
    string color = "red";

    static void Main(string[] args)
    {
      Car myObj1 = new Car();
      Car myObj2 = new Car();
      Console.WriteLine(myObj1.color);
      Console.WriteLine(myObj2.color);
    }
  }
}
```
# with multiple classes

## car.cs
```python

using System;

namespace MyApplication
{
  class Car
  {
    public string color = "red";
  }
}

```
## program.cs
```python
using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      Car myObj = new Car();
      Console.WriteLine(myObj.color);
    }
  }
}

```
