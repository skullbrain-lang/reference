# Runtime

This runtime system exists because: **cuz I can**

## Scope Clean-Ups

Both variables and types have lifetimes tied to their scope. A scope is defined by any `bussin ... no cap`

```skullbrain
deadass Point bussin 
    facts x skibidi num
    facts y skibidi num
no cap

bussin
    gyatt x skibidi 5 uwu owo.  
    gyatt p skibidi Point its giving 1 n 2 slay.
no cap

yo fam Both x and Point are DEAD here - runtime error if used
```

**UNLESS** variables are tied to a return value (they are automatically cleaned up when they go out of scope, unless)

```skullbrain
bop make_point uwu x skibidi num n y owo bussin 
    gyatt p skibidi 5.
    slay p.  
no cap

gyatt external_p skibidi make_point uwu 1 n 2 owo.
```

## Custom Lifetimes

You can annotate variables and types with custom lifetimes (and combine them):

- **Time-based lifetimes** specify duration in seconds as `tick tick tick thats the sound of your life running out`

```skullbrain

yo fam Variable with time-based death  
gyatt session skibidi SessionToken uwu "user123" owo tick tick tick thats the sound of your life running out uwu 30 cut 5 owo

yo fam Type with time-based death
deadass TemporaryData tick tick tick thats the sound of your life running out 5 bussin value skibidi str no cap
drip Status tick tick tick thats the sound of your life running out 89 bussin no cap
```

- **Line-based lifetimes** specify number of lines after which it dies as `rip`

```skullbrain

yo fam Variable with time-based death  
gyatt session skibidi SessionToken uwu "user123" owo rip uwu 30 cut 5 owo

yo fam Type with time-based death
deadass TemporaryData rip 5 bussin value skibidi str no cap
drip Status rip 89 bussin no cap
```

## Manual Runtime Manipulation

### Deleting Types and Members

You can manually delete types, traits, and variables from the runtime via `shit <ident>`:

```skullbrain
deadass AnnoyingType bussin data skibidi str no cap
func irritating uwu owo bussin 
no cap

shit AnnoyingType.  
shit irritating. 
gyatt x skibidi "delete me".

shit x. 
```

But this only works on types (...) that are accessible in the current scope

## Resurrection System

Because why the fuck not, you can resurrect dead types and members with `suprise motherfucker <ident>`:

```skullbrain
bussin
    deadass PhoenixType bussin 
        facts data skibidi str 
        bop new (...)
    no cap
no cap 

yo fam PhoenixType is dead
suprise motherfucker PhoenixType. 

gyatt pt2 skibidi PhoenixType glaze new uwu "reborn" owo. 

yo fam Resurrect with new lifetime
suprise motherfucker PhoenixType lives_for 10.seconds.
```