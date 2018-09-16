# AiLearning
Material for AI learning

This is note for AI learning containing implemenation practice and theory notes

### 2018/9/12
 - Desicion tree implementation
  - Python copy list
	  - a = b[:] # a is a copy of b
	  - a = b # a and b is pointed to the same list
  - Python sorted and sort
	  - sort function operated on the original list or dict
	  - sorted function created a new list or dict based on original one
  - Python memory and variable
	  - mutable variable: list, dict, set, bytearray
	  - immutable variable: string, number, tuple
	  - function parameter passing can be regarded as pointer passing
  - Python operator.itemgetter
  - Python dict.items(): list of tuple in dictionary

### 2018/9/16
 - Desicion tree plot and classify implementation
  - Python tell variable type
  	- isinstance, isinstance(tree, dict)
	- type, type(tree).\__name__ == 'dict'
  - Python matplotlib axis range
  	- x from left to right: 0.0 -> 1.0
	- y from bottom to top: 0.0 -> 1.0
  - Python store variable in file
  	- pickle.dump
	- pickle.load
  - Vim find
  	- /string Find string from top to bottom
	- ?string Find string from bottom to top
  - Vim replace
  	- /s/origin/new/g Replace orgin with new
