## What does it mean for a method to "return" a value? (Jack Hubert)

The return value is what an invoked method will be equal to. It is often indicated by the keyword `return`, or in some langauges is implicity done with the last line of a method.
- A return value can also be referred to as an "output parameter"
- Any object can be returned, as well as multiple objects as "output parameters"
- Returning a value refers to 

## What is the difference between a procedure, a function, and a method? (Arielle Ross)

## What's the difference between a hash and an array? (Gerald Bivens)

## What's the difference between a hash and an object? (Grant Hesketh)

## When should you use map? Select? Reduce? Find? (Jeff Golden)

## What's the difference between a class and an instance of a class? (Mary Beth Ingram)

## What's the difference between an instance method and a class method? (Brett Needham) 

## What is a gem? Gemfile? Gemfile.lock? (Kat Leight)

## What is a one to many relationship? Many to many? (Colton O'Connor)

## How does a database relate 2 tables? (Luke Thinnes)

## What does "single source of truth" mean in terms of related objects? (Ryan Choe)

## What is the purpose of the environment.rb file? (Jack Hubert)

An environment.rb file imports all of the libraries and classes that should be available to the program at run time.
- Lets you customize your individual working environment as well as environment variables
- I like to think of your environment file as the playground, with all of your models, views, & controllers as the playground equipment
    - If you build a slide in the gym, no one outside on the playground is going to be able to use it

## What does an ORM do? (Arielle Ross)

## What is an API? (Gerald Bivens)

## What is semantic HTML? (Grant Hesketh)

## What is the DOM? (Jeff Golden)

## Describe the HTTP Request/Response cycle (Mary Beth Ingram)

## What's the difference between the web and the internet? (Brett Needham) 

## What is a computer virus? (Kat Leight)

## What is validation, where can it occur, and what purpose does it serve? (Colton O'Connor)

## What is an event? (Luke Thinnes)

## What is event bubbling? (Ryan Choe)

## What is referential transparency? (Jack Hubert)

Referential transparency is when an expression is equivalent to what the expression evaluates to. In other words, any valid operation on the result of an expression can be done on the expression itself
- The fact that an expression, in a program, may be replaced by its value (or anything having the same value)
    - This makes reasoning about programs easier, & makes each subprogram independent,
    - Greatly simplifiying unit testing & refactoring
- Used in various domains, such as mathematics, logic, linguistics, philosophy, & programming
    - In functional programming, our applications / programs are composed of sub-programs & routines which are represented themselves by methods, functions, & various expression assignment evaluation
    - When we use our functions as arguments in JavaScript, we are relying on the referential transparency of those functions return values
    - When we build our helper functions, we are 
    - When we refactor our code we are using referential transparency to increase readability
- Referential transparency allows reasoning, & it's how we perform multi-step equations / code executions
    - Ex.
            const sumOfParts = (x,y) => x + y
            sumOfParts(1,2) IS 3 because of referential transparency
    - Ex.   
            x = 2 + (3 * 4)
            x = 2 + 12

## What are the 4 pillars of OOP? (Arielle Ross)

## What are some tenets of functional programming? (Gerald Bivens)

## What's the difference between authentication and authorization? (Grant Hesketh)

## How do you avoid storing plain-text passwords? (Jeff Golden)

## What is serialization? (Mary Beth Ingram)

## Describe the MVC architecture pattern (Brett Needham) 

## What is Big O? (Kat Leight)

## What is a closure? (Colton O'Connor)

## What is CORS? (Luke Thinnes)

## What's the semantic difference between PUT and PATCH? (Ryan Choe)

## What is DRY?

