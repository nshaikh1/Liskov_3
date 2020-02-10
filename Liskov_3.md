<h1>Liskov substitution principle<br>



<h3>Formal Defination by Zaiba:</h3>

	+ The Liskov Substitution principle was introduced by Barbara Liskov in her conference keynote “Data abstraction” in 1987.
	+ It extends the open/closed Principle by focusing on the behavior of a superclass and its subtypes.
	+ In a practical Software development environment:
	+ The principle defines that objects of a superclass shall be replaceable with objects of its subclasses without breaking the application.
	+ That requires the objects of your subclasses to behave in the same way as the objects of your superclass. You can achieve that by following a few rules, which are pretty similar to the design by contract concept defined by   Bertrand Meyer.
	+ An overridden method of a subclass needs to accept the same input parameter values as the method of the superclass.
	+ Let $(x) be a property provable about objects x of type T. Then $(y) should be true for objects y of type S where S is a subtype of T.

<h3>Example by Nomaan

![Image description](https://github.com/nshaikh1/Liskov_3/blob/master/Recursion_3%20copy.jpg)

<h3>Why is it needed? by Sujeet

I'm doing this
