
```kotlin
val pi = 3.14 // Double
// val one: Double = 1 // Error: type mismatch
val oneDouble = 1.0 // Double
```

To explicitly specify the `Float` type for a value, add the suffix `f` or `F`.
If such a value contains more than 6-7 decimal digits, it will be rounded. 

```kotlin
val e = 2.7182818284 // Double
val eFloat = 2.7182818284f // Float, actual value is 2.7182817
```
