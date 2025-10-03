# Functions

## Function Definition

Syntax: `[mew | bet] bop <ident> uwu [<ident> is <type> [n <ident> is <type>]*] owo [bustin <type>] bussin <statements> no cap`

```skullbrain
bop add uwu x is aura n y is aura owo bustin aura bussin
    pluh x boost y.
no cap

mew bop area uwu width is vibing n height is vibing owo bustin vibing bussin
    pluh width drift height.
no cap

```

## Function Calls

Syntax: `<ident> uwu [<expr> [n <expr>]*] owo`

```skullbrain
gyatt sum skibidi add uwu 5 n 3 owo.
```

## Method Chaining

Syntax: `<expr> glaze <ident> uwu [<expr> [n <expr>]*] owo`

```skullbrain
gyatt str skibidi 'hello'.
gyatt upper skibidi str glaze uppercase uwu owo.
```

## Extension Functions

Add methods using `goated` to signify that the first paramter of the function is the receiver
```skullbrain
goated bop shout uwu this is chad owo bustin chad bussin
    pluh this.  
no cap

gyatt str skibidi 'yo fam'.
gyatt loud skibidi str glaze shout uwu owo.
```

## Overloading

Functions overload by matching the first signature (parameter count and types). Ambiguous calls yeet a runtime error (e.g., “cant decide between these..”).
