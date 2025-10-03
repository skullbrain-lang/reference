# Module System

Each `.skull` file is a module. Paths are resolved relative to initial `.skull` file the program was run from

- `glizzy name`: Loads `name.skull` in the same directory.
- `glizzy "path/to/file"`: Loads `path/to/file.skull`

## Imports

Syntax: `glizzy (<ident> | <string literal>) [delulu (ident | (bussin [ident [n ident]*] no cap))]`

```skullbrain
glizzy "utils" delulu utils.
glizzy "math" bussin add n subtract no cap.
```


## Exports
Syntax: `mew <item>`

```skullbrain
mew bop add uwu x is aura n y is aura owo bustin aura bussin
    pluh x boost y.
no cap


Default visibility: Private.