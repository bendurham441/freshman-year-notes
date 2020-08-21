# Generics

When creating methods, it often doesn't make sense to constrain to one particular type. In this case, one can implement generics, allowing a method to accept any non-primative type, infer what thay type is, and use it throughout the method. This can be implemented in the following way:

`
static <E> void bubbleSort(E[] array) {...}
`

In this example, the generic allows the `bubbleSort` method to accept any type so as to eliminate the need to create additional versions of the `bubbleSort` method for other types.
