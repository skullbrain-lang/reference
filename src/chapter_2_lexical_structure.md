# Lexical Structure

## Basic Syntax Notes

- **The period (`.`) serves as a semicolon** in SkullScript (is optional)
- **Code blocks** are denoted by `bussin` and `no cap` instead of curly braces `{}`.  
- **Parens `()` are replaced by `uwu ... owo`** .  
- **For assignment use `skibidi`**

## Keywords

Defined in [`keywords.yaml`](https://github.com/Deaths-Door/SkullBrain/blob/main/skullbrain-lexer/keywords.yaml)

## Identifiers

- **Format**: Alphanumeric, underscores, emojis (e.g., `user_123`, `🔥`).
- **Restrictions**: Cannot match keywords.
- **Example**:

```skullbrain
  gyatt 🔥 skibidi 42.
```

## Comments

### Single-Line Comments

Written as `yo fam <text>` continue until the end of the line.

### Multi-Line Comments

Written as `chat <text> thats real`

- Nesting: Multi-line comments can be nested.
- Important: An unterminated multi-line comment (one missing thats real) will cause a compile error.
