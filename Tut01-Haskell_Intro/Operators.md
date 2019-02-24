# VALUES AND OPERATORS


Try to run provided expressions in GHCI shell,
and run missing operations in your GHCI shell


### 1. Boolean Operations
------------------------

Binary Boolean Operations
```
True || True
True || False
False || True
False || False
```
```
True && True
True && False
False && True
False && False
```

Unary Boolean Operations
```
not True
not False
```

(In)Equality
```
True == True
True == False
False == False
```
```
False /= True
True /= False
```

Composite Boolean Operations
	XOR (only returns True when either ONE of the operands is True)
	Answer in GHCI shell!

Boolean Operator precedence
```
True /= True && True
True /= True || True
```

### 2. Arithmetic Operations
------------------------

Simple Operations
```
5 + 7
9 - 5
3 / 10
6 * 8
2^3
```

(In)Equality Operations
```
3.14 < 4
5.0 >= 4.999999999999999
5.0 == 4.999999999999999
```
	Is there any surprising result from any of the expression above?
		How can we make it return the value we expected?

Arithmetic Operator precedence
	Average these values: 4, 5, 6, 7, 8, 9!
	i.e:
	```
	> 4+5+6+7+8+9 / 5
	```
		Will expression above give the average of the values? why?
		Try in the GHCI shell!
		