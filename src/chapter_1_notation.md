# Notation

This guide uses the following syntax definitions

- `<item>`: Non-terminal (e.g., `<expr>`).
- `keyword`: Literal keywords from `keywords.yaml` (e.g., `gyatt`).
- `[item]`: Optional.
- `<item>*`: Zero or more.
- `<item>+`: One or more.
- `|`: Choice.
- `...`: Informal continuation.
- `(..)`: For grouping
Example

```text
<var-decl> ::= (gyatt | facts) <ident> [is <type>] skibidi <expr> [.]
```
