# LC3_Compiler
 A partial two-pass LC3 compiler.
 
 What it currently has:
	
 	* A full tokenizer, which takes in lexemes from lines fed by a scanner.

	* The "first pass", which stores all leading labels with their associated memory addresses in an internal hashmap
	
 Now I just need to add the second pass, which generates the opcodes/instructions and creates the obj file
