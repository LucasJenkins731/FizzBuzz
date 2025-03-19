# FizzBuzz

## What is the project?
In FizzBuzz, each number 1 through 100 will be printed in the terminal. If a number is divisible by 3, 5, or 3 AND 5, fizz, buzz, or fizzbuzz will be printed into the terminal instead.

### Fizz
If a number is divisible by 3, the program will print "Fizz" in its place

```Java
else if (count % 3 == 0) {
    System.out.println("Fizz");
}
```
git 
### Buzz
If a number is divisible by 3, the program will print "Buzz" in its place

```Java
else if (count % 5 == 0) {
    System.out.println("Buzz");
}
```

### FizzBuzz
If a number is divisible by 3 and 5, the program will print "FizzBuzz" in its place

```Java
if (count % 3 == 0 && count % 5 == 0) {
    System.out.println("Fizzbuzz");
}
```