# Swift Language Guide Notes

This repository compiles notes made on the Swift language guide. The order in which the notes were made was dictated by the Stanford course 'Developing iOS 11 apps with Swift', and the releases reflect the reading exercises made in that course. As a result, if you are following along with the official [Swift Language Guide](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/TheBasics.html#//apple_ref/doc/uid/TP40014097-CH5-ID309), there will be small differences in the order topics are covered

Attempts have been made to keep the notes as brief as possible, and omit content that would be intuitive to a programmer with some experience of Object Oriented Languages. If you ever feel you need more detail, there is no better source than the [official language guide itself](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/TheBasics.html#//apple_ref/doc/uid/TP40014097-CH5-ID309). Each note is also linked to the appropriate section of the language guide.

## Table of Contents

1. [The Basics](/1%20-%20The%20Basics) 
   0. [Intro](/1%20-%20The%20Basics/1.0%20-%20The%20Basics.md)
   1. [Constants and Variables](/1%20-%20The%20Basics/1.1%20-%20Constants%20and%20Variables.md)
   1. [Comments](/1%20-%20The%20Basics/1.2%20-%20Comments.md)
   1. [Semicolons](/1%20-%20The%20Basics/1.3%20-%20Semicolons.md)
   1. [Integers](/1%20-%20The%20Basics/1.4%20-%20Integers.md)
   1. [Floating Point Numbers](/1%20-%20The%20Basics/1.5%20-%20Floating%20Point%20Numbers.md)
   1. [Type Safety and Type Inference](/1%20-%20The%20Basics/1.6%20-%20Type%20Safety%20and%20Type%20Inference.md)
   1. [Numeric Literals](/1%20-%20The%20Basics/1.7%20-%20Numeric%20Literals.md)
   1. [Numeric Type Conversion](/1%20-%20The%20Basics/1.8%20-%20Numeric%20Type%20Conversion.md)
   1. [Type Aliases](/1%20-%20The%20Basics/1.9%20-%20Type%20Aliases.md)
   1. [Booleans](/1%20-%20The%20Basics/1.10%20-%20Booleans.md)
   2. [Tuples](/1%20-%20The%20Basics/1.11%20-%20Tuples.md)
   1. [Optionals](/1%20-%20The%20Basics/1.12%20-%20Optionals.md)
   1. [Error Handling](/1%20-%20The%20Basics/1.13%20-%20Error%20Handling.md)
   1. [Assertions and Preconditions](/1%20-%20The%20Basics/1.14%20-%20Assertions%20and%20Preconditions.md)
2. [Basic Operators](/2%20-%20Basic%20Operators)
   0. [Intro](/2%20-%20Basic%20Operators/2.0%20-%20Basic%20Operators.md)
   1. [Terminology](/2%20-%20Basic%20Operators/2.1%20-%20Terminology.md)
   2. [The Assignment, Arithmetic and Logical Operators](/2%20-%20Basic%20Operators/2.2%20-%20The%20Arithmetic%2C%20Assignment%20and%20Logical%20Operators.md)
   1. [Comparison Operators](/2%20-%20Basic%20Operators/2.3%20-%20Comparison%20Operators.md)
   1. [Ternary Coniditonal Operator](/2%20-%20Basic%20Operators/2.4%20-%20Ternary%20Conditional%20Operator.md)
   1. [Nil-Coalescing Operator](/2%20-%20Basic%20Operators/2.5%20-%20Nil-Coalescing%20Operator.md)
   1. [Range Operators](/2%20-%20Basic%20Operators/2.6%20-%20Range%20Operators.md)
3. [Strings and Characters](/3%20-%20Strings%20and%20Characters)
   0. [Intro](/3%20-%20Strings%20and%20Characters/3.0%20-%20Strings%20and%20Characters.md)
   1. [Unicode](/3%20-%20Strings%20and%20Characters/3.1%20-%20Unicode.md)
   1. [Counting Characters](/3%20-%20Strings%20and%20Characters/3.2%20-%20Counting%20Characters.md)
   1. [Accessing and Modifying a String](/3%20-%20Strings%20and%20Characters/3.3%20-%20Accessing%20and%20Modifying%20a%20String.md)
   1. [Substrings](/3%20-%20Strings%20and%20Characters/3.4%20-%20Substrings.md)
   1. [Comparing Strings](/3%20-%20Strings%20and%20Characters/3.5%20-%20Comparing%20Strings.md)
   2. [Unicode Representations of Strings](/3%20-%20Strings%20and%20Characters/3.6%20-%20Unicode%20Representations%20of%20Strings.md)
4. [Collection Types](/4%20-%20Collection%20Types)
   0. [Intro](/4%20-%20Collection%20Types/4.0%20-%20Collection%20Types.md)
   1. [Arrays](/4%20-%20Collection%20Types/4.1%20-%20Arrays.md)
   2. [Dictionaries](/4%20-%20Collection%20Types/4.2%20-%20Dictionaries.md)
   3. [Sets](/4%20-%20Collection%20Types/4.3%20-%20Sets.md)
   4. [Performing Set Operations](/4%20-%20Collection%20Types/4.4%20-%20Performing%20Set%20Operations.md)
5. [Control Flow](/5%20-%20Control%20Flow)
   0. [Intro](/5%20-%20Control%20Flow/5.0%20-%20Control%20Flow.md)
   1. [For-in loops](/5%20-%20Control%20Flow/5.1%20-%20For-in%20Loops.md)
   2. [Switch Statements](/5%20-%20Control%20Flow/5.2%20-%20Switch%20Statements.md)
   3. [Control Transfer Statements](/5%20-%20Control%20Flow/5.3%20-%20Control%20Transfer%20Statements.md)
   4. [Early Exit](/5%20-%20Control%20Flow/5.4%20-%20Early%20Exit.md)
6. [Functions](/6%20-%20Functions)
   0. [Intro](/6%20-%20Functions/6.0%20-%20Functions.md)
   1. [Argument Labels and Parameter Names](/6%20-%20Functions/6.1%20-%20Argument%20Labels%20and%20Parameter%20Names.md)
   2. [Functions with Multiple Return Values](/6%20-%20Functions/6.2%20-%20Functions%20with%20Multiple%20Return%20Values.md)
   3. [Function Types](/6%20-%20Functions/6.3%20-%20Function%20Types.md)
7. [Classes and Structures](/7%20-%20Classes%20and%20Structures)
   0. [Intro](/7%20-%20Classes%20and%20Structures/7.0%20-%20Classes%20and%20Structures.md)
   1. [Comparing Classes and Structures](/7%20-%20Classes%20and%20Structures/7.1%20-%20Comparing%20Classes%20and%20Structures.md)
   2. [Structures and Enumerations are Value Types](/7%20-%20Classes%20and%20Structures/7.2%20-%20Structures%20and%20Enumerations%20are%20Value%20Types.md)
   3. [Classes are Reference Types](/7%20-%20Classes%20and%20Structures/7.3%20-%20Classes%20are%20Reference%20Types.md)
   4. [Choosing Between Classes and Structures](/7%20-%20Classes%20and%20Structures/7.4%20-%20Choosing%20Between%20Classes%20and%20Structures.md)
8. [Properties](/8%20-%20Properties)
   0. [Intro](/8%20-%20Properties/8.0%20-%20Properties.md)
   1. [Stored Properties](/8%20-%20Properties/8.1%20-%20Stored%20Properties.md)
   2. [Property Observers](/8%20-%20Properties/8.2%20-%20Property%20Observers.md)
9. [Methods](/9%20-%20Methods)
   0. [Intro](/9%20-%20Methods/9.0%20-%20Methods.md)
   1. [Instance Methods](/9%20-%20Methods/9.1%20-%20Instance%20Methods.md)
10. [Inheritance](/10%20-%20Inheritance/10.0%20-%20Inheritance.md)
11. [Initialization](/11%20-%20Initialization)
    0. [Intro](/11%20-%20Initialization/11.0%20-%20Initialization.md)
    1. [Setting Initial Values for Stored Properties](/11%20-%20Initialization/11.1%20-%20Setting%20Initial%20Values%20for%20Stored%20Properties.md)
    2. [Customizing Initialization](/11%20-%20Initialization/11.2%20-%20Customizing%20Initialization.md)
    3. [Default Initializers](/11%20-%20Initialization/11.3%20-%20Default%20Initializers.md)
    4. [Initializer Delegation for Value Types](/11%20-%20Initialization/11.4%20-%20Initializer%20Delegation%20for%20Value%20Types.md)
12. [Closures](/12%20-%20Closures)
    0. [Intro](/12%20-%20Closures/12.0%20-%20Closures.md)
    1. [Closure Expressions](/12%20-%20Closures/12.1%20-%20Closure%20Expressions.md)
    2. [Trailing Closures](/12%20-%20Closures/12.2%20-%20Trailing%20Closures.md)
    3. [Capturing Values](/12%20-%20Closures/12.3%20-%20Capturing%20Values.md)
    4. [Closures are Reference Types](/12%20-%20Closures/12.4%20-%20Closures%20are%20Reference%20Types.md)
5. [Enumerations](/13%20-%20Enumerations)
    0. [Intro](/13%20-%20Enumerations/13.0%20-%20Enumerations.md)
    1. [Enumeration Syntax](/13%20-%20Enumerations/13.1%20-%20Enumeration%20Syntax.md)
    2. [Matching Enumeration Values with a Switch Statement](/13%20-%20Enumerations/13.2%20-%20Matching%20Enumeration%20Values%20with%20a%20Switch%20Statement.md)
    3. [Associated Values](/13%20-%20Enumerations/13.3%20-%20Associated%20Values%20Syntax.md)
    4. [Raw Values](/13%20-%20Enumerations/13.4%20-%20Raw%20Values%20Syntax.md)
    5. [Recursive Enumerations](/13%20-%20Enumerations/13.5%20-%20Recursive%20Enumerations.md)

## Stanford iOS Reading Exercised

The guide below outlines the order you should read these notes in if you are following the Stanford iOS course, and wish to complete the reading exercises in the same order.

### Reading 1

Read all of sections 1 - 11, with the following exceptions:

* Section 1.11 - Tuples
* Section 3.6 - Unicode Representations of Strings
* Section 4.3 - Sets
* Section 4.4 - Performing Set Operations
* Part of Section 5.2. Ignore everything related to Tuples
* Part of Section 6.1 - Ignore Variadic Parameters and In-Out Parameters
* Section 6.2 - Functions with Multiple Return Values
* Section 6.3 - Function Types