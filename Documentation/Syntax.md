# Syntax
## Comments
Single-Line	`#`

Multi-line Start	`/*`

Multi-line End	`*/`

## Operaters
### Assignment
Base Assignment:	`a = b`

Increment:	`++a`

Decrement:	`--a`

### Numerical
Addition:	`a + b`

Subtraction:	`a - b`

Multiplication:	`a * b`

Division:	`a / b`

Modulus (Remainder):	`a % b`

### Boolean
Eqality:	`a == b`

Inequality:	`a != b`

Less Than:	`a < b`

Greater Than:	`a > b`

Less Than or Equal To:	`a <= b`

Greater Than or Equal To:	`a >= b`

## Structure
### type
Similar to `class` in C-Family Languages.

### template
Templates cannot be made into objects, but they provide base information and simple 

Templates usually have `template` that

### enum
Abbreviation for Enumerator.

### operator
Allows for operator overloading and creation.

### Function Types
- `process`: Processes read and/or write type and template features without returing a value. They can be accessed from outside the type or template.
- `method`: 

### Variable Types
- `bool`: holds a simple `true` or `false` value
- `int`: 8-byte signed integer.
- `float`: IEEE 754-1985 double precision
- `char`: 

- `const`
- ``


## Example
```
template vehicle
{
	float[3] property location;

	
}

type car : vehicle
{
	int property speed;
}
```
