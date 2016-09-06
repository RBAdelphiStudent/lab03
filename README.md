# lab03

## What do you think is the type of each of the following fields? 
* private int count; 
* This field is of the int data type.
* private Student representative; 
* This field has the `Student` data type, which is also considered a class.
* private Server host; 
* * This field has the `Server` data type, which is also considered a class.

## What are the names of the following fields? 
* private boolean alive;
* This field is named alive.
* private Person tutor; 
* This field is named tutor.
* private Game game; 
* This field is named game.

## From what you know about the naming conventions for classes, which of the type names in the above questions would you say are class names? 
* Based off of the convention that class names are capitalized in code, the data type names Student, Server, Person, and Game all represent classes.

## In the following field declaration from the `TicketMachine` class  
```
private int price;
```
does it matter which order the three words appear in? Edit the TicketMachine class to try different orderings. After each change, close the editor. Does the appearance of the class diagram after each change give you a clue as to whether or not other orderings are possible? Check by pressing the Compile button to see if there is an error message. Make sure that you reinstate the original version after your experiments! 
* The order of the three words matters; if the words are not entered in the order above, the class diagram shows that a parsing error occurs when trying to compile the file. The order of the declaration must be the field state, the field data type, then the field name.

## Is it always necessary to have a semicolon at the end of a field declaration? Once again, experiment via the editor. The rule you will learn here is an important one, so be sure to remember it. 
* It is always necessary to have a semicolon at the end of a field declaration; the computer is unable to parse the declaration if the semicolon is not used to end the declaration.

## Write in full the declaration for a field of type `int` whose name is `status`.
```
private int status;
```

## To what class does the following constructor belong?
```
public Student(String name)
```
The constructor shown above belongs to the Student class.

## How many parameters does the following constructor have, and what are their types?
```
public Book(String title, double price)
```
* The following constructor has two parameters, a string (title) and a double (price).

## Can you guess what types some of the `Book` class’s fields might be, from the parameters in its constructor? Can you assume anything about the names of its fields? 
*Based off its constructor, the class `Book` has at least two fields of the types `String` and `double`. The `String` is named `title`, while the `double` is named `price`.

## Suppose that the class `Pet` has a field called `name` that is of the type `String`. Write an assignment statement in the body of the following constructor so that the `name` field will be initialized with the value of the constructor’s parameter.
```
public Pet(String petsName)
{
private int name=petsName;
}
```
## The following object creation will result in the constructor of the `Date` class being called. Can you write the constructor’s header?
```
new Date ("March", 23, 1861)
```
Try to give meaningful names to the parameters.
```
public Date (String month, int day, int year)
```
