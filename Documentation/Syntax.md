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
<!--
Option 1:
	[public|protected|private]	[static?]	[void|return type]			12
	uoi				 			sn			vr
	inr inv isr isv onr onv osr osv unr unv usr usv
Option 2:
	
-->
- `proc`: Processes read and/or write type and template features without returing a value. They can be accessed from outside the type or template.
- ``: 

### Variable Types
- `bool`: holds a simple `true` or `false` value
- `int`: 8-byte signed integer. \[-2^31 - (2^31)-1\]
- `float`: IEEE 754-1985 double precision
- `string`: UTF-8 Encoding
<!--
Option 1:
	[public|protected|private]	[static|not]	[constant|not]					12
	uoi							sn				cn
	inn	inc isn isc onn onc osn osc unn unc usn usc
Option 2:
	[private|(private) static|global (public static)]	[constant|not]			6
	psg													cn
	gn gc sn sc pn pc
-->
`const`: defines a variable as constant (unchanging). It must be initialized when decleared and cannot be modified.

- `` 



## Example
```
template vehicle
{
	float property location;

	
}

type car : vehicle
{
	int property speed;
}
```
