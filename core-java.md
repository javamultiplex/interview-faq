# How to create Immutable class in Java?
There are following rules to create a user defined immutable class.<br/>
1. Class should public and final.
1. All the properties of the class should be final.
1. Provide initialization only through constructors at the time of object creation.
1. Setter methods are not allowed.

## Example
```java
public final class ImmutableClass {

	private final int a;

	public ImmutableClass(int a) {
		this.a = a;
	}

	public int getA() {
		return a;
	} 
}
```
