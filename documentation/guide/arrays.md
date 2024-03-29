### <img src="https://media.discordapp.net/attachments/980517878220615710/992872212786860143/Near.png?width=473&height=473" width="300" height="300" alt="#">
# Arrays on Near


Document published on: **5/27/2022** - takes a few seconds to a minute to read.

On arrays, you are able to store multiple variables on a structure, there are multiple types that can be used for arrays such as:

- [x] `object`
- [x] `string`
- [x] `bool`
- [x] `int`
- [x] `char`

## Example

```csharp

import Packages.reg;

context ArraysNamespace {
    
    class ArrayClass {
        
        int[] veryCoolIntegers = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };
        
        char[] veryCoolCharacters = { 'a', 'b', 'c' };
        
        string[] veryCoolStrings = { "yes very cool", "also very cool" };
        
    }
}
```

Arrays are very useful for when needing to have multiple variables of the same type, it can be defined as a sequence of objects which are of the same data type. It is used to store a collection of data, and it is more useful to think of an array as a collection of variables of the same type.

## Object Example

```csharp

import Packages.reg;

context ArraysNamespace {
    
    class ArrayClass {
        
        int[] veryCoolIntegers = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };
        int numberLength = veryCoolIntegers.Length;
        
        static func Main(string[] arguments) {
            
            
            printJ($"Length of 'veryCoolIntegers': {numberLength}");
            printJ.PauseAtKey();
            
        }
    }
}
```

That's it for the arrays documentation.
