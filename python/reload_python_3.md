When you're using ipython or any python REPL terminal, sometimes you need to reload the module.

in python 2.7 there's a reload function that automatically reloads the module, but that function is missing on python 3.

however, python 3 you can achieve the same functionality using importlib module

	 import importlib
	 imprtlib.reload(\`module\`)