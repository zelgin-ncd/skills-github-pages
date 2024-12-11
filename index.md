# Magic Rocks
## Turtles All The Way Down
How does a computer understand natural language?
Lets look at some simple code:

```
int a = 10
a = a + 10
print a
```
Output:
```
20
```

How did the computer know what to do?

Lets look at the first line:
```
int a = 10
```
Code is evaluated right to left in most compuilers/interpreters.
The first thing encountered is:
```
10
```
This is a number (specifically an int) and the computer treats this as a *Literal*
A Literal is a special type of entity to the computer. It does need any extra work to determine its value. 
It is 10 and definitely not 11.
So now our computer is aware of 1 literal:
Computer State:
```
Literals: 10
```
Next up is a new type of entity:
```
=
```
This is *NOT* a literal and the computer must do some additional work to determine how to handle this. Because it is a letter
the computer knows this is an entity type known as a *Operator*
The computer knows that when it sees a operator it needs more info, specficially it needs operators or parameters.
The computer knows that the = operator takes two arguements and that it should have already encountered the first one (our 10)
The computer then tries to find the other operators parameter by going to the next character.

```
int
```
This tells the computer that the variable is of a type *Integer* and it knows to setup to handle an integer variable.
The computers state now looks like:
```
Literals: 10
Operators: =
```
So now our computer

