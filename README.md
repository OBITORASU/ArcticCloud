It is a **Package** Created to solve few problems faced by people especially Students of CS at Scool Level Like **Converting Base of a given Number**, So this **Library** solve that **long awaited problem**. 

It has **two Classes**, they are:

Class **BaseConverter**:

```
This Module will Convert a number from the given base to any other base.
Usage : from ArcticCloud import BaseConvertor as b
# Say, you will convert from Binary to Hexadecimal,
v1 = b.Binary_to_Hexadecimal("11011101.111010") # bound the method calling to a variable and print it to get the desired result, 

Note: Remember to give the Argument of all the functions in str, if you use any good text editor like VS Code or any IDE it will show the references while you call the method/function. 
```

Class **MarkSheet**: 

```
This Module will generate a CBSE marksheet for you provided you give the Marks of 6 Subjects.
Usage: from ArcticCloud import Marksheet as mk
mk.PrintMarksheet("<name of school>",[<marks of 6 subjects>], ["<Name>", "<Sec>", "<Roll no>"])

# The First Argument of the Function is School Name in str class, marks of 6 subjects in a list -> [100, 100, 99, 98, 98, 99], details ["Samuel Miller", "C", 5]

Note: This Functions does not return anything and by default returns None , so bounding it to a Variable will return None.
```
