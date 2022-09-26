# syntax
## literals
### numeric
int match
` [0-9] ([0-9_]* [0-9])?` <br>
examples `123 0123 10_000` <br>
faulty examples `_123 0123_ _` <br>
#### int (bigint)
    base
        10 => 013 = 13
        2  => 0b1010
        16 => 0x19af
        8 => 0o70
#### float
    123.123
    123f
    1_2.3_4
#### complex (of any)
    123i
    1_2i
#### rational (bigint)
    123r
    123r456 (123r/456)
    1_000r
####

### array
    [elem, elem]

### hash
    { a : b , a : b}
    where a is any expression, b is any expression
    { (1 ? "a" : "b") : (0 ? "c" : "d") } => {"a":"d"}
    { 1 ? "a" : "b" : "c"} => {"a":"c"}
### 

operators
objects
errors

