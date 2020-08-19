1. Dynamic vs. Static Typed Languages
	- Python is dynamically typed language:
		- Types are only checked at runtime 
		- Types can changed over time
	- Static Type Checks:
		- Test type at compile time
	- Python remains a dynamically typed language, but can have features of static type checking 


2. Duck Typing 
	- Not the type that matters, but specific attributes or methods 
	- For example the __len__ method can be applied to many different objects. As long as it is defined for the object, it can be used 

3. Type Hinting 
	- A formal solution to indicate the type of a value 


	```py 
		def greet(name:str) -> str:
			return "Hello, " + name
	```

- name : str - hints that argument name must be of type string 
- -> str - hints that greet returns a string

4. Type Checking with MyPy
	- Allows to use static type checking on it.
	- mypy .py in terminal and uses the type hints in  

5. Pro/Con of Using Type Hints:
	- Pro: Helps you catch errors, documentation, build and maintain a cleaner architecture
	- Con: Developer time, does not work well with old code 

It is not dichotomous. Python supports gradual type hints:
- Best to use with more experience and larger projects
- In libraries, especially if used on PyPI 

> Type hints should be used wherever unit testing is required. 

6. Annotations
	- Used for type hints. 
	- Syntax:
		- For arguments - argument : annotation
		- For return type "-> annotation"
	- Can use the __annotation__ on the function to see them 
	- Can use reveal_type when checking with MyPy 
- Type Comments 
- Python Types 

