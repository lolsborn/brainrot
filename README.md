# Brainrot Programming Language 🔥

A joke programming language that's absolutely bussin, fr fr. No cap.

## What is Brainrot?

Brainrot is a meme-inspired programming language with BASIC-like syntax but with Gen-Z slang keywords. It's designed to be ridiculous, fun, and surprisingly functional.

## Language Features

### Keywords & Syntax

#### Types
- `vibe` - integer type
- `rizz` - string type (charisma = text, get it?)
- `sigma` - boolean type
- `ghost` - void/null type

#### Literals
- `cap` - false (it's a lie/cap)
- `nocap` - true (no lie/for real)
- `nada` - 0 (zero/nothing)
- `ghost` - null/undefined value

#### Control Flow
- `chat` - if statement (like "if we're being real...")
- `whatever` - else
- `bussin` - while loop (keep going while it's bussin/good)
- `periodt` - block terminator (ends if/while/function blocks)
- `?` - optional readability marker (treated as whitespace)

#### Comparison Operators
- `is` - equals (`==`)
- `aint` / `isnt` - not equals (`!=`)
- `under` / `<` - less than
- `over` / `>` - greater than
- `under_or_is` / `<=` - less than or equal
- `over_or_is` / `>=` - greater than or equal

#### Functions
- `side_quest` - function declaration
- `bounce` - return statement

#### I/O
- `spill` - print/output (spill the tea = tell the truth)

#### Loop Control
- `mid` - break (it's mid/mediocre, exit the loop)
- `slaps` - continue (it slaps, keep going)

#### Error Handling
- `yeet` - throw exception
- `bet` - try block
- `cringe` - catch block

## Example Programs

### Hello World
```brainrot
spill "Hello World, fr fr!"
```

### Variables and Conditionals
```brainrot
vibe age is 25
rizz username is "SigmaSteve"

chat age over 21?
    spill "You can drink, no cap"
whatever
    spill "Too young, that's cap"
periodt
```

### Loops
```brainrot
vibe counter is nada

bussin counter under 10?
    spill counter
    counter is counter + 1
    
    chat counter is 5?
        spill "Halfway there!"
        mid
    periodt
periodt
```

### Functions
```brainrot
side_quest greet(rizz name)?
    spill "Yo, "
    spill name
    spill "! What's good?"
    bounce ghost
periodt

greet("Chad")
```

### Error Handling
```brainrot
side_quest divide(vibe a, vibe b)?
    chat b is nada?
        yeet "Cannot divide by zero, that's cap!"
    periodt
    bounce a / b
periodt

bet
    vibe result is divide(10, 0)
    spill result
cringe
    spill "Error: that's cringe"
periodt
```

### FizzBuzz (Because Why Not)
```brainrot
vibe num is 1

bussin num under_or_is 100?
    chat num % 15 is nada?
        spill "FizzBuzz"
    whatever
        chat num % 3 is nada?
            spill "Fizz"
        whatever
            chat num % 5 is nada?
                spill "Buzz"
            whatever
                spill num
            periodt
        periodt
    periodt
    
    num is num + 1
periodt
```

## Files

- `brainrot.pest` - Pest parser grammar definition
- `examples.brainrot` - Collection of example programs
- `README.md` - This file
- `LICENSE.md` - License (very official, trust me bro)

## Implementation

This language uses [Pest](https://pest.rs/) for parsing. The grammar is defined in `brainrot.pest`.

To implement an interpreter/compiler:
1. Use Pest to parse `.brainrot` files
2. Build an AST from the parse tree
3. Implement an interpreter or compile to bytecode/native code
4. ???
5. Profit (but fr though)

## Why Does This Exist?

Because we can. Also it's funny. Also it demonstrates parser design. Also brain rot is real and this is both a symptom and a cure.

## Contributing

If you want to add more brainrot keywords or features, go for it. This is peak comedy and we should lean into it.

## Examples

Check out `examples.brainrot` for a comprehensive set of example programs including:
- Basic I/O
- Conditionals and loops
- Functions and recursion
- Error handling
- FizzBuzz
- Prime number checker
- Game simulation
- And more!

## Is This Serious?

No cap, this is a joke language. But also, it's a fully-specified language with a proper grammar, so... maybe?

The real question is: are you brave enough to write production code in Brainrot? (Please don't.)

---

*Made with 100% pure, unfiltered brain rot. No cap, fr fr. Periodt.* 💀🔥
