# Learning TypeScript

## Philosophy

Type checking is paramount.

## Compiling

1. ``tsc file.ts``
1. Enums are consts!

## Autocompiling

1. `npm i -g ts-node`
1. `npm i --save-dev @types/body-parser @types/express @types/node @types/mongoose`
1. Declare a .tsconfig file

## Adding Types

1. ``const myString: string = "hello";``
1. ``let myArray: number[] = [1,2,3];``
1. ``let myVar: any = { };``
1. ``const someFunction = (user: string, pass: string): string => { return ""; };``
1. ```typescript
    class MyClass { 
        someString: string;
        constructor(something) {
            this.someString = something;
        }
    }```
1. ```typescript
    export enums SomeValues {
        value1 = 'value1',
        value2 = 'value2',
    };
    let value = SomeValues.value1;
    ```
