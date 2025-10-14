# Expressions

## Operators

| Standard | SkullScript       | Description                     |
|----------|-------------------|---------------------------------|
| `+`      | `boost`           | Addition                        |
| `-`      | `cut`             | Subtraction                     |
| `*`      | `drift`           | Multiplication                  |
| `/`      | `dab`             | Division                        |
| `%`      | `skrrt`           | Modulo                          |
| `==`     | `valid`           | Equality                        |
| `!=`     | `cap`             | Inequality                      |
| `>`      | `flex`            | Greater than                    |
| `<`      | `lowkey`          | Less than                       |
| `>=`     | `flex valid`      | Greater than or equal           |
| `<=`     | `lowkey valid`    | Less than or equal              |
| `&&`     | `frfr`            | Logical AND                     |
| `||`     | `but eh`          | Logical OR                      |
| `!`      | `nah`             | Logical NOT                     |
| `.`      | `glaze`           | Method chaining                 |




## Block Expressions

Syntax: `bussin <statements> [pluh <expr>] no cap`

```skullbrain
gyatt result skibidi bussin
    gyatt x skibidi 42.
    pluh x boost 1.
no cap
```

## Variable Declarations

- Mutable: `gyatt <ident> [is <type>] [skibidi <expr> [.]}`
- Immutable: `facts <ident> [is <type>] [skibidi <expr> [.]]`

```skullbrain
gyatt counter is aura skibidi 0.
facts PI is vibing skibidi 3.14159.
```

> Note: All variables can be shadowed without issue

