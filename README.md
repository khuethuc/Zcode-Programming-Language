# CO3005 - Principles of Programming Languages - Assignments - HCMUT - HK232
- Description: ZCode is a programming language which is created to help students learn the principles of programming language and how to build a compiler for a programming language. In this assignment, I implemented Lexer and Parser Analysis, Abstract Syntax Tree Generation, Static Checker, and Code Generation for ZCode.
- Score: 
  + Lexer: 84/100
  + Parser: 97/100
  + AST Generation: 100/100
  + Static Checker: 38/100 😭😭😭
  + Code Generation: 24/100 😭😭😭
 
# Test code
Set environment variable ```ANTLR_JAR``` to the file ```antlr-4.9.2-complete.jar``` in your computer.

```
cd initial/src
python run.py gen
```

For Lexer (assignment 1):
```
python run.py test LexerSuite
```

For Parser (assignment 1): 
```
python run.py test ParserSuite
```

For AST (assignment 2): 
```
python run.py test ASTGenSuite
```

For Static Checker (assignment 3): 
```
python run.py test CheckSuite
```

For Code Generation (assignment 4):
```
python run.py test CodeGenSuite
```
