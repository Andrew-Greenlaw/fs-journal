# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
it provides a way for c# to know the scope in which functions and uses it can have.
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
the difference is that a class defaults accessibilty to private and struct defaults to public
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
void makes it so you can not return a value
```

## Example 1

```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```

**5.** In the example what is the access modifier of the `Start()` method?

<!-- enter you answer in the space below -->

```
the public is the access modifier
```

**6.** In the example what is `string` an indication of?

<!-- enter you answer in the space below -->

```
its the value type that is going to return
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
it restricts the class so it cannot create objects
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
makes it so it can be redifined and the dirived class can override the method
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
public private protected and internal
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
it can only be accessed within the same class
```
