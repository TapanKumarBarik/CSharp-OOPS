
# C# Enums
An enum is a special "class" that represents a group of constants (unchangeable/read-only variables).

To create an enum, use the enum keyword (instead of class or interface), and separate the enum items with a comma:
```python
Example
enum Level 
{
  Low,
  Medium,
  High
}
```
## You can access enum items with the dot syntax:

```python
Level myVar = Level.Medium;
Console.WriteLine(myVar);
```
