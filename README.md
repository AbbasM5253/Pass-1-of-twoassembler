# Pass-1-of-twoassembler

This project provides a concise overview of the pass-1 of  two-pass assembler implemented using the Python code. The assembler transforms assembly language code into intermediate code while generating essential tables and visualizations. 

Assembly Language:

Assembly language is a low-level programming language that is closely related to the machine language of a computer's central processing unit (CPU). Unlike high-level programming languages, which are designed to be more human-readable and abstract, assembly language provides a direct representation of the CPU's instructions and operations. Each assembly language instruction corresponds to a specific machine-level instruction or operation that the CPU can execute.


Data Structures: 

The assembler utilizes dictionaries to store mnemonic information, including opcodes and instruction types. Files such as "inter_code.txt," "literals.txt," and "tmp.txt" hold the intermediate code, literal data, and temporary data respectively. Lists like pooltab, symbol_addresses, and literal_addresses track pool table entries and symbol/literal addresses.

Mnemonics Used :

             {'STOP': ('00', 'IS', 0), 'ADD': ('01', 'IS', 2), 'SUB': ('02', 'IS', 2), 'MUL': ('03', 'IS', 2),
             'MOVER': ('04', 'IS', 2), 'MOVEM': ('05', 'IS', 2), 'COMP': ('06', 'IS', 2), 'BC': ('07', 'IS', 2),
             'DIV': ('08', 'IS', 2), 'READ': ('09', 'IS', 1), 'PRINT': ('10', 'IS', 1), 'LTORG': ('05', 'AD', 0),
             'ORIGIN': ('03', 'AD', 1), 'START': ('01', 'AD', 1), 'EQU': ('04', 'AD', 2), 'DS': ('01', 'DL', 1),
             'DC': ('02', 'DL', 1), 'END': ('AD', 0)}


Table and Visualizations:

1.Symbol Table : The assembler creates a symbol table that captures labels and symbols along with their assigned memory addresses. 

![image](https://github.com/AbbasM5253/Pass-1-of-twoassembler/assets/148611666/e9df0eae-0e49-40e8-b3c7-56b0882c218d)

2.Pool Table :  The assembler creates a symbol table that captures labels and symbols along with their assigned memory addresses. 

![image](https://github.com/AbbasM5253/Pass-1-of-twoassembler/assets/148611666/d4a7f15c-a1d1-4ce9-9fa9-53850658ed9c)

3.Literals Table : The assembler tracks literals and their addresses.

![image](https://github.com/AbbasM5253/Pass-1-of-twoassembler/assets/148611666/c5b94716-9060-4c2c-8d7d-88eea2cd0e20)

4.Pool Table Visualization : A line plot visualizes pool table entries, indicating where new literal pools begin.

![image](https://github.com/AbbasM5253/Pass-1-of-twoassembler/assets/148611666/e58a3f11-6689-435b-8a24-7cc0fa97580e)

5.Symbol Table Visualizations : A line plot depicts the addresses of symbols stored in the symbol table.

![image](https://github.com/AbbasM5253/Pass-1-of-twoassembler/assets/148611666/756ffe9a-ae1c-4ac4-afd5-ba7eedaca01c)








