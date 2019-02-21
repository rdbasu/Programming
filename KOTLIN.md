## INSTALL KOTLIN

```
LM-SJN-XXXXXXXX:~ robasu$ brew update
LM-SJN-XXXXXXXX:~ robasu$ brew install kotlin
```

```
LM-SJN-XXXXXXXX:~ robasu$ kotlin -version
Kotlin version 1.3.21-release-158 (JRE 1.8.0_102-b14)
LM-SJN-XXXXXXXX:~ robasu$ 
```

## Hello World
### helloworld.kt

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

## 5 THINGS

- CONCISE
- INTEROPERABLE
- TOOL FRIENDLY

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
