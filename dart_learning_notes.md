Dart - learning notes
=============
Now I'm reading the Dart: Up and Running which you can get [here](https://www.dartlang.org/docs/dart-up-and-running/). It seems to be a good point of reference for a Dart beginners. I will create some code samples and notes during studies of that book.

- [Dart - Important Concepts](https://www.dartlang.org/docs/dart-up-and-running/contents/ch02.html#ch02-concepts)
- Code samples
```
/**
 * Function description
 * This is an example of function definition
 * This function prints the given number in the console
 */
printNumber(num number){
    print('Number: $number');
    // This is a comment.
    // print() - function for displaying output in console
    // '...' or "..." - string literal
    // $variableName(or${expression}) - string interpolation
}

// This is where tha app starts executing (similar to Java or C#)
void main() {
  var number = 7;
  // var - declare a variable without specifying its type.
  printNumber(number);
}
```

### Creating the REST client - first approach

