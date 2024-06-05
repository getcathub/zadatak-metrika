
Analiza koriscenjem Checkstyle:

Inspection Results - 36 errors

Calculator - 25 errors
Checkstyle: Utility classes should not have a public or default constructor.
Checkstyle: Missing a Javadoc comment.
Checkstyle: Variable 'finalResult' must be private and have accessor methods.
Checkstyle: Class Operations should be declared as final.
Checkstyle: Missing a Javadoc comment.
Checkstyle: Missing a Javadoc comment.
Checkstyle: Missing a Javadoc comment.
Checkstyle: Missing a Javadoc comment.
Checkstyle: Name 'ToString' must match pattern '^[a-z][a-zA-Z0-9]*$'.
Checkstyle: Line is longer than 80 characters (found 103).
Checkstyle: Missing a Javadoc comment.
Checkstyle: Name 'Run' must match pattern '^[a-z][a-zA-Z0-9]*$'.
Checkstyle: Parameter expression should be final.
Checkstyle: Parameter expression should be final.
Checkstyle: Line is longer than 80 characters (found 81).
Checkstyle: Name 'Calculate' must match pattern '^[a-z][a-zA-Z0-9]*$'.
Checkstyle: Parameter numbers should be final.
Checkstyle: Parameter operations should be final.
Checkstyle: Line is longer than 80 characters (found 97).
Checkstyle: Line is longer than 80 characters (found 89).
Checkstyle: Line is longer than 80 characters (found 86).
Checkstyle: Line is longer than 80 characters (found 82).
Checkstyle: Line is longer than 80 characters (found 82).
Checkstyle: Line is longer than 80 characters (found 87).
Checkstyle: Line is longer than 80 characters (found 91).

Calculator.java - 2 errors
Checkstyle: File does not end with a newline.
Checkstyle: Missing package-info.java file.

Start - 6 errors

Checkstyle: Utility classes should not have a public or default constructor.
Checkstyle: Missing a Javadoc comment.
Checkstyle: Parameter args should be final.
Checkstyle: Name 'Expression' must match pattern '^[a-z][a-zA-Z0-9]*$'.
Checkstyle: Line is longer than 80 characters (found 83).
Checkstyle: Line has trailing spaces.

Start.java - 3 errors

Checkstyle: File contains tab characters (this is the first instance).
Checkstyle: File does not end with a newline.
Checkstyle: Missing package-info.java file.


Analiza koriscenjem PMD-a:
                           file                                Line                            Problem

1	C:\java_programs\zadatakMetrika\src\Calculator.java	4	All classes, interfaces, enums and annotations must belong to a named package
2	C:\java_programs\zadatakMetrika\src\Calculator.java	4	All methods are static. Consider using a utility class instead. Alternatively, you could add a private constructor or make the class abstract to silence this warning.
3	C:\java_programs\zadatakMetrika\src\Calculator.java	4	Class comments are required
4	C:\java_programs\zadatakMetrika\src\Calculator.java	4	The class 'Calculator' has a Modified Cyclomatic Complexity of 7 (Highest = 10).
5	C:\java_programs\zadatakMetrika\src\Calculator.java	4	The class 'Calculator' has a Standard Cyclomatic Complexity of 7 (Highest = 10).
6	C:\java_programs\zadatakMetrika\src\Calculator.java	6	Do not use non-final non-private static fields
7	C:\java_programs\zadatakMetrika\src\Calculator.java	6	Field comments are required
8	C:\java_programs\zadatakMetrika\src\Calculator.java	6	To avoid mistakes add a comment at the beginning of the finalResult field if you want a default access modifier
9	C:\java_programs\zadatakMetrika\src\Calculator.java	6	Use explicit scoping instead of the default package private level
10	C:\java_programs\zadatakMetrika\src\Calculator.java	8	Class comments are required
11	C:\java_programs\zadatakMetrika\src\Calculator.java	8	To avoid mistakes add a comment at the beginning of the Operations nested class if you want a default access modifier
12	C:\java_programs\zadatakMetrika\src\Calculator.java	10	Field comments are required
13	C:\java_programs\zadatakMetrika\src\Calculator.java	10	To avoid mistakes add a comment at the beginning of the ADDITION_SYMBOL field if you want a default access modifier
14	C:\java_programs\zadatakMetrika\src\Calculator.java	10	Use explicit scoping instead of the default package private level
15	C:\java_programs\zadatakMetrika\src\Calculator.java	11	Avoid excessively long variable names like SUBTRACTION_SYMBOL
16	C:\java_programs\zadatakMetrika\src\Calculator.java	11	Field comments are required
17	C:\java_programs\zadatakMetrika\src\Calculator.java	11	To avoid mistakes add a comment at the beginning of the SUBTRACTION_SYMBOL field if you want a default access modifier
18	C:\java_programs\zadatakMetrika\src\Calculator.java	11	Use explicit scoping instead of the default package private level
19	C:\java_programs\zadatakMetrika\src\Calculator.java	12	Avoid excessively long variable names like MULTIPLICATION_SYMBOL
20	C:\java_programs\zadatakMetrika\src\Calculator.java	12	Field comments are required
21	C:\java_programs\zadatakMetrika\src\Calculator.java	12	To avoid mistakes add a comment at the beginning of the MULTIPLICATION_SYMBOL field if you want a default access modifier
22	C:\java_programs\zadatakMetrika\src\Calculator.java	12	Use explicit scoping instead of the default package private level
23	C:\java_programs\zadatakMetrika\src\Calculator.java	13	Field comments are required
24	C:\java_programs\zadatakMetrika\src\Calculator.java	13	To avoid mistakes add a comment at the beginning of the DIVISION_SYMBOL field if you want a default access modifier
25	C:\java_programs\zadatakMetrika\src\Calculator.java	13	Use explicit scoping instead of the default package private level
26	C:\java_programs\zadatakMetrika\src\Calculator.java	18	Public method and constructor comments are required
27	C:\java_programs\zadatakMetrika\src\Calculator.java	18	The static method name 'ToString' doesn't match '[a-z][a-zA-Z0-9]*'
28	C:\java_programs\zadatakMetrika\src\Calculator.java	19	Do not add empty strings
29	C:\java_programs\zadatakMetrika\src\Calculator.java	24	Parameter 'expression' is not assigned and could be declared final
30	C:\java_programs\zadatakMetrika\src\Calculator.java	24	Public method and constructor comments are required
31	C:\java_programs\zadatakMetrika\src\Calculator.java	24	The static method name 'Run' doesn't match '[a-z][a-zA-Z0-9]*'
32	C:\java_programs\zadatakMetrika\src\Calculator.java	28	The method 'evaluateExpression(String)' has a cognitive complexity of 15, current threshold is 15
33	C:\java_programs\zadatakMetrika\src\Calculator.java	28	The method 'evaluateExpression(String)' has a cyclomatic complexity of 12.
34	C:\java_programs\zadatakMetrika\src\Calculator.java	34	Avoid reassigning parameters such as 'expression'
35	C:\java_programs\zadatakMetrika\src\Calculator.java	37	Local variable 'numbers' could be declared final
36	C:\java_programs\zadatakMetrika\src\Calculator.java	37	Potential violation of Law of Demeter (object not created locally)
37	C:\java_programs\zadatakMetrika\src\Calculator.java	40	Found 'DU'-anomaly for variable 'operationList' (lines '40'-'72').
38	C:\java_programs\zadatakMetrika\src\Calculator.java	40	Local variable 'operationList' could be declared final
39	C:\java_programs\zadatakMetrika\src\Calculator.java	51	Local variable 'numberList' could be declared final
40	C:\java_programs\zadatakMetrika\src\Calculator.java	53	This for loop can be replaced by a foreach loop
41	C:\java_programs\zadatakMetrika\src\Calculator.java	55	Position literals first in String comparisons
42	C:\java_programs\zadatakMetrika\src\Calculator.java	57	Position literals first in String comparisons
43	C:\java_programs\zadatakMetrika\src\Calculator.java	63	Avoid catching generic exceptions such as NullPointerException, RuntimeException, Exception in try-catch block
44	C:\java_programs\zadatakMetrika\src\Calculator.java	64	A method should have only one exit point, and that should be the last statement in the method
45	C:\java_programs\zadatakMetrika\src\Calculator.java	70	Local variable 'textResult' could be declared final
46	C:\java_programs\zadatakMetrika\src\Calculator.java	71	Consider simply returning the value vs storing it in local variable 'textResult'
47	C:\java_programs\zadatakMetrika\src\Calculator.java	74	Avoid really long methods.
48	C:\java_programs\zadatakMetrika\src\Calculator.java	74	Parameter 'numbers' is not assigned and could be declared final
49	C:\java_programs\zadatakMetrika\src\Calculator.java	74	Parameter 'operations' is not assigned and could be declared final
50	C:\java_programs\zadatakMetrika\src\Calculator.java	74	The method 'Calculate' has a Modified Cyclomatic Complexity of 10.
51	C:\java_programs\zadatakMetrika\src\Calculator.java	74	The method 'Calculate' has a Standard Cyclomatic Complexity of 10.
52	C:\java_programs\zadatakMetrika\src\Calculator.java	74	The method 'Calculate(List, List)' has a NCSS line count of 67.
53	C:\java_programs\zadatakMetrika\src\Calculator.java	74	The method 'Calculate(List, List)' has a cognitive complexity of 23, current threshold is 15
54	C:\java_programs\zadatakMetrika\src\Calculator.java	74	The method 'Calculate(List, List)' has a cyclomatic complexity of 12.
55	C:\java_programs\zadatakMetrika\src\Calculator.java	74	The method 'Calculate(List, List)' has an NPath complexity of 512, current threshold is 200
56	C:\java_programs\zadatakMetrika\src\Calculator.java	74	The static method name 'Calculate' doesn't match '[a-z][a-zA-Z0-9]*'
57	C:\java_programs\zadatakMetrika\src\Calculator.java	76	Avoid using Literals in Conditional Statements
58	C:\java_programs\zadatakMetrika\src\Calculator.java	78	A method should have only one exit point, and that should be the last statement in the method
59	C:\java_programs\zadatakMetrika\src\Calculator.java	81	Found 'DU'-anomaly for variable 'result' (lines '81'-'186').
60	C:\java_programs\zadatakMetrika\src\Calculator.java	83	Local variable 'indexMultiply' could be declared final
61	C:\java_programs\zadatakMetrika\src\Calculator.java	84	Local variable 'indexDivide' could be declared final
62	C:\java_programs\zadatakMetrika\src\Calculator.java	96	A method should have only one exit point, and that should be the last statement in the method
63	C:\java_programs\zadatakMetrika\src\Calculator.java	106	A method should have only one exit point, and that should be the last statement in the method
64	C:\java_programs\zadatakMetrika\src\Calculator.java	119	A method should have only one exit point, and that should be the last statement in the method
65	C:\java_programs\zadatakMetrika\src\Calculator.java	131	A method should have only one exit point, and that should be the last statement in the method
66	C:\java_programs\zadatakMetrika\src\Calculator.java	134	Local variable 'indexPlus' could be declared final
67	C:\java_programs\zadatakMetrika\src\Calculator.java	135	Local variable 'indexMinus' could be declared final
68	C:\java_programs\zadatakMetrika\src\Calculator.java	147	A method should have only one exit point, and that should be the last statement in the method
69	C:\java_programs\zadatakMetrika\src\Calculator.java	157	A method should have only one exit point, and that should be the last statement in the method
70	C:\java_programs\zadatakMetrika\src\Calculator.java	171	A method should have only one exit point, and that should be the last statement in the method
71	C:\java_programs\zadatakMetrika\src\Start.java	3	All classes, interfaces, enums and annotations must belong to a named package
72	C:\java_programs\zadatakMetrika\src\Start.java	3	All methods are static. Consider using a utility class instead. Alternatively, you could add a private constructor or make the class abstract to silence this warning.
73	C:\java_programs\zadatakMetrika\src\Start.java	3	Class comments are required
74	C:\java_programs\zadatakMetrika\src\Start.java	5	Parameter 'args' is not assigned and could be declared final
75	C:\java_programs\zadatakMetrika\src\Start.java	5	Public method and constructor comments are required
76	C:\java_programs\zadatakMetrika\src\Start.java	6	The local variable name 'Expression' doesn't match '[a-z][a-zA-Z0-9]*'
77	C:\java_programs\zadatakMetrika\src\Start.java	6	Variables should start with a lowercase character, 'Expression' starts with uppercase character.
78	C:\java_programs\zadatakMetrika\src\Start.java	8	System.out.println is used
79	C:\java_programs\zadatakMetrika\src\Start.java	9	Ensure that resources like this Scanner object are closed after use
80	C:\java_programs\zadatakMetrika\src\Start.java	12	Avoid instantiating new objects inside loops
81	C:\java_programs\zadatakMetrika\src\Start.java	15	Position literals first in String comparisons
82	C:\java_programs\zadatakMetrika\src\Start.java	15	Position literals first in String comparisons
83	C:\java_programs\zadatakMetrika\src\Start.java	19	System.out.println is used





Koriscenje alata cloc za brojanje linija koda:

       3 text files.
       2 unique files.
       2 files ignored.

github.com/AlDanial/cloc v 2.00  T=0.02 s (116.5 files/s, 12461.4 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Java                             2             61              5            148
-------------------------------------------------------------------------------
SUM:                             2             61              5            148
-------------------------------------------------------------------------------


Analiza koriscenjem SpotBugs:

IntelliJ SpotBugs plugin: found 0 bugs in 0 class



