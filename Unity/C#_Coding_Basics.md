# C# Coding Basics

## Variables
* A variable is something which holds a value of something else
* To declare a variable you specify the data type and variable name followed by a value
  DataTypes to know:
  * String: anything inside " ... "
  * Int: any whole number
  * Bool: True or False
### Syntax
DataType variableName = value;

__Show below are some examples:__
```C#
string Name = "iCodeEdu";
int Year = 2023;
bool yes = true;
```

## Arrays
* similar to variables, but can hold more values
### Syntax
DataType[] ArrayName = {Comma Separated Values};

__Show below are some examples:__
```C#
string[] movies = {"World War Z", "Minions", "Oppenheimer"};
int[] numbers = {1, 2, 3, 4, 5};
```


# Conditional Statements
## If Statements
* If a condition is true then the code must be evaluated else another code must be evaluated
  
### Syntax
if(true){
//some code;
}
else{
//some other code;
}

__Show below are some examples:__
```C#
int Year = 2023;
if (Year == 2023)
{
  Console.WriteLine("The year is 2023");
}
else
{
  Console.WriteLine("The year is not 2023");
}
```

## Switch Statement
* similar to a if-else statement but is much cleaner and easier to maintain
### Syntax
switch(condition to evaluate against)
{
  default:

}

__Show below are some examples:__
```C#
int Year = 2023;
switch(Year):
{
  case 2013:
    Console.WriteLine("It's 2013");
    break;
  default:
    Console.WriteLine("It's" + Year + "!");
    break;
}
```




