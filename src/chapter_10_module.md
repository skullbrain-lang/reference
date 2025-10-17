# Module System

Each `.skull` file is a module. Paths are resolved relative to initial `.skull` file the program was run from

- `glizzy name`: Loads `/name.skull` in the same directory.
- `glizzy "path/to/file"`: Loads `/path/to/file.skull`

The namespace is derived from the final segment of the import path:

- `glizzy "utils"` → namespace: `utils`
- `glizzy "lib/data"` → namespace: `data`

## Imports

Syntax: `glizzy (<ident> | <string literal>) [delulu (ident | (bussin [ident [n ident]*] no cap))] [.]`

- Importing a module under namespace

```skullbrain
yo fam `utils glaze function`
glizzy "utils"

yo fam `data glaze function` 
glizzy "lib/data"
```

- Importing everything under a custom namespace using `bussin ... no cap`

```skullbrain
yo fam Import only 'add' and 'subtract' from "math"
glizzy "math" bussin add n subtract no cap.

yo fam Use directly: add(5, 3)
```

Access Syntax: `[namespace] glaze [function]`

```skullbrain
yo fam Usage examples
utils glaze some_function uwu owo
data glaze another_function uwu owo
```

## Exports

Syntax: `mew <item>`

```skullbrain
mew bop add uwu x is aura n y is aura owo bustin aura bussin
    pluh x boost y.
no cap
```

Default visibility: Private to the module
