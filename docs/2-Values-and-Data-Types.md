# Intro

## Values

- chunks of information we want to work with
- that information (data) can be of different types

## typeof()

- Tells you the type of value, it return string always

## JS have two kinds of data

- Primitive types (e.g: string, number)
- Objects (documents & friends)

## Primitive data types

- string
- number
- boolean
- undefined
- null
- couple of other

`Null` in JavaScript means an empty value and is also a primitive type in JavaScript. The variable which has been assigned as null contains no value. `Undefined`, on the other hand, means the variable has been declared, but its value has not been assigned.
`Null` indicates the absence of a value for a variable. `Undefined` indicates the absence of the variable itself.

## How many characters are in this string?

```js
"supercalifragilisticexpialidocious".length;
"super k".length;
"".length;
```

- Note space is also count
- Characters are in a specific order
- Each gets a number, starting at 0, that called index

### What's the first character in the string?

```js
"ALOHA"[0]; // put this in console, it gives `A`
```

### What's the index of a specific character?

```js
"ALOHA".indexOf("L");
```

- It return the index of value, and it is case sensitive means `a` is not equal to `A`

```js
"ALOHA".indexOf("A"); // return 0
```

```js
"ALOHA".indexOf("a"); // return -1
```

- It return `0` so that `indexOf` return first find index.

### What id a character is not defined

```js
"ALOHA".indexOf("Q");
```

- It return `-1` that represent this character not present in this string

## Does this string contain some other string?

The includes() method of Array instances determines whether an array includes a certain value among its entries, returning true or false as appropriate.

- `includes` return a boolean value, if string mach, that means is `ALOHA` have the string `HA` so the answer is yes

```js
"ALOHA".includes("HA"); // true
"ALOHA".includes("LOL"); // false bcs string LOL not exist in string
```

## Does this string start with some other string?

```js
"ALOHA".startsWith("AL"); // true
"ALOHA".startsWith("HA"); // false bcs string not start with `HA`
```

## At what index does this substring begin?

```js
"ALOHA".indexOf("HA"); // return 3
"ALOHA".indexOf("LOL"); // -1
```

## Connecting strings together

```js
"ALOHA" + "!"; // ALOHA!
```

## Change letter case

```js
"ALOHA".toLowerCase();
```
