```
LM-SJN-XXXXXXXX:~ robasu$ brew update
LM-SJN-XXXXXXXX:~ robasu$ brew install kotlin
```

## Hello World
A new file called **helloworld.kt** 

*Kotlin files always end with the **.kt** extension*

```
LM-SJN-XXXXXXXX:~ robasu$ cat helloworld.kt 
fun main(args: Array<String>) {
    println("Hello, World!")
}
LM-SJN-XXXXXXXX:~ robasu$ 
```
### Compile & Run

```
LM-SJN-XXXXXXXX:~ robasu$ kotlinc helloworld.kt -include-runtime -d helloworld.jar
LM-SJN-XXXXXXXX:~ robasu$ java -jar helloworld.jar
Hello, World!
LM-SJN-XXXXXXXX:~ robasu$ 
```

*The **-include-runtime** option makes the resulting .jar file self-contained and runnable by including the Kotlin runtime library in it.*

*quick to get set up and started with*

**can be difficult to master**

vs *JAVA*

- Lambda expressions + Inline functions = performant custom control structures
- **Extension functions**
- **Null-safety**
- Smart casts
- String templates
- Properties
- Primary constructors
- First-class delegation
- Type inference for variable and property types
- Singletons
- Declaration-site variance & Type projections
- Range expressions
- Operator overloading
- Companion objects
- Data classes
- Separate interfaces for read-only and mutable collections
- **Coroutines**
