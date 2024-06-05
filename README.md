# Analiza korišćenjem Checkstyle

## Inspection Results - 36 grešaka

### Calculator - 25 grešaka
- **Checkstyle:** Utility klase ne bi trebalo da imaju javni ili podrazumevani konstruktor.
- **Checkstyle:** Nedostaje Javadoc komentar.
- **Checkstyle:** Promenljiva 'finalResult' mora biti privatna i imati pristupne metode.
- **Checkstyle:** Klasa Operations bi trebalo da bude deklarisana kao finalna.
- **Checkstyle:** Nedostaje Javadoc komentar.
- **Checkstyle:** Nedostaje Javadoc komentar.
- **Checkstyle:** Nedostaje Javadoc komentar.
- **Checkstyle:** Nedostaje Javadoc komentar.
- **Checkstyle:** Naziv 'ToString' mora da odgovara obrascu '^[a-z][a-zA-Z0-9]*$'.
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 103).
- **Checkstyle:** Nedostaje Javadoc komentar.
- **Checkstyle:** Naziv 'Run' mora da odgovara obrascu '^[a-z][a-zA-Z0-9]*$'.
- **Checkstyle:** Parametar expression bi trebalo da bude finalan.
- **Checkstyle:** Parametar expression bi trebalo da bude finalan.
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 81).
- **Checkstyle:** Naziv 'Calculate' mora da odgovara obrascu '^[a-z][a-zA-Z0-9]*$'.
- **Checkstyle:** Parametar numbers bi trebalo da bude finalan.
- **Checkstyle:** Parametar operations bi trebalo da bude finalan.
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 97).
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 89).
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 86).
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 82).
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 82).
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 87).
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 91).

### Calculator.java - 2 greške
- **Checkstyle:** Fajl ne završava sa novom linijom.
- **Checkstyle:** Nedostaje package-info.java fajl.

### Start - 6 grešaka
- **Checkstyle:** Utility klase ne bi trebalo da imaju javni ili podrazumevani konstruktor.
- **Checkstyle:** Nedostaje Javadoc komentar.
- **Checkstyle:** Parametar args bi trebalo da bude finalan.
- **Checkstyle:** Naziv 'Expression' mora da odgovara obrascu '^[a-z][a-zA-Z0-9]*$'.
- **Checkstyle:** Linija je duža od 80 karaktera (nađeno 83).
- **Checkstyle:** Linija ima prazne prostore.

### Start.java - 3 greške
- **Checkstyle:** Fajl sadrži tab karaktere (ovo je prva instanca).
- **Checkstyle:** Fajl ne završava sa novom linijom.
- **Checkstyle:** Nedostaje package-info.java fajl.

# Analiza korišćenjem PMD-a

| File | Line | Problem |
|------|------|---------|
| C:\java_programs\zadatakMetrika\src\Calculator.java | 4 | All classes, interfaces, enums and annotations must belong to a named package |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 4 | All methods are static. Consider using a utility class instead. Alternatively, you could add a private constructor or make the class abstract to silence this warning. |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 4 | Class comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 4 | The class 'Calculator' has a Modified Cyclomatic Complexity of 7 (Highest = 10). |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 4 | The class 'Calculator' has a Standard Cyclomatic Complexity of 7 (Highest = 10). |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 6 | Do not use non-final non-private static fields |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 6 | Field comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 6 | To avoid mistakes add a comment at the beginning of the finalResult field if you want a default access modifier |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 6 | Use explicit scoping instead of the default package private level |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 8 | Class comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 8 | To avoid mistakes add a comment at the beginning of the Operations nested class if you want a default access modifier |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 10 | Field comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 10 | To avoid mistakes add a comment at the beginning of the ADDITION_SYMBOL field if you want a default access modifier |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 10 | Use explicit scoping instead of the default package private level |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 11 | Avoid excessively long variable names like SUBTRACTION_SYMBOL |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 11 | Field comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 11 | To avoid mistakes add a comment at the beginning of the SUBTRACTION_SYMBOL field if you want a default access modifier |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 11 | Use explicit scoping instead of the default package private level |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 12 | Avoid excessively long variable names like MULTIPLICATION_SYMBOL |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 12 | Field comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 12 | To avoid mistakes add a comment at the beginning of the MULTIPLICATION_SYMBOL field if you want a default access modifier |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 12 | Use explicit scoping instead of the default package private level |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 13 | Field comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 13 | To avoid mistakes add a comment at the beginning of the DIVISION_SYMBOL field if you want a default access modifier |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 13 | Use explicit scoping instead of the default package private level |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 18 | Public method and constructor comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 18 | The static method name 'ToString' doesn't match '[a-z][a-zA-Z0-9]*' |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 19 | Do not add empty strings |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 24 | Parameter 'expression' is not assigned and could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 24 | Public method and constructor comments are required |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 24 | The static method name 'Run' doesn't match '[a-z][a-zA-Z0-9]*' |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 28 | The method 'evaluateExpression(String)' has a cognitive complexity of 15, current threshold is 15 |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 28 | The method 'evaluateExpression(String)' has a cyclomatic complexity of 12. |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 34 | Avoid reassigning parameters such as 'expression' |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 37 | Local variable 'numbers' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 37 | Potential violation of Law of Demeter (object not created locally) |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 40 | Found 'DU'-anomaly for variable 'operationList' (lines '40'-'72'). |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 40 | Local variable 'operationList' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 51 | Local variable 'numberList' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 53 | This for loop can be replaced by a foreach loop |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 55 | Position literals first in String comparisons |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 57 | Position literals first in String comparisons |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 63 | Avoid catching generic exceptions such as NullPointerException, RuntimeException, Exception in try-catch block |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 64 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 70 | Local variable 'textResult' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 71 | Consider simply returning the value vs storing it in local variable 'textResult' |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | Avoid really long methods. |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | Parameter 'numbers' is not assigned and could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | Parameter 'operations' is not assigned and could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | The method 'Calculate' has a Modified Cyclomatic Complexity of 10. |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | The method 'Calculate' has a Standard Cyclomatic Complexity of 10. |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | The method 'Calculate(List, List)' has a NCSS line count of 67. |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | The method 'Calculate(List, List)' has a cognitive complexity of 23, current threshold is 15 |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | The method 'Calculate(List, List)' has a cyclomatic complexity of 12. |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | The method 'Calculate(List, List)' has an NPath complexity of 512, current threshold is 200 |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 74 | The static method name 'Calculate' doesn't match '[a-z][a-zA-Z0-9]*' |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 76 | Avoid using Literals in Conditional Statements |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 78 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 81 | Found 'DU'-anomaly for variable 'result' (lines '81'-'186'). |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 83 | Local variable 'indexMultiply' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 84 | Local variable 'indexDivide' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 96 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 106 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 119 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 131 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 134 | Local variable 'indexPlus' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 135 | Local variable 'indexMinus' could be declared final |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 147 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 157 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Calculator.java | 171 | A method should have only one exit point, and that should be the last statement in the method |
| C:\java_programs\zadatakMetrika\src\Start.java | 3 | All classes, interfaces, enums and annotations must belong to a named package |
| C:\java_programs\zadatakMetrika\src\Start.java | 3 | All methods are static. Consider using a utility class instead. Alternatively, you could add a private constructor or make the class abstract to silence this warning. |
| C:\java_programs\zadatakMetrika\src\Start.java | 3 | Class comments are required |
| C:\java_programs\zadatakMetrika\src\Start.java | 5 | Parameter 'args' is not assigned and could be declared final |
| C:\java_programs\zadatakMetrika\src\Start.java | 5 | Public method and constructor comments are required |
| C:\java_programs\zadatakMetrika\src\Start.java | 6 | The local variable name 'Expression' doesn't match '[a-z][a-zA-Z0-9]*' |
| C:\java_programs\zadatakMetrika\src\Start.java | 6 | Variables should start with a lowercase character, 'Expression' starts with uppercase character. |
| C:\java_programs\zadatakMetrika\src\Start.java | 8 | System.out.println is used |
| C:\java_programs\zadatakMetrika\src\Start.java | 9 | Ensure that resources like this Scanner object are closed after use |
| C:\java_programs\zadatakMetrika\src\Start.java | 12 | Avoid instantiating new objects inside loops |
| C:\java_programs\zadatakMetrika\src\Start.java | 15 | Position literals first in String comparisons |
| C:\java_programs\zadatakMetrika\src\Start.java | 19 | System.out.println is used |

Korišćenje alata cloc za brojanje linija koda:

       3 tekstualne datoteke.
       2 jedinstvene datoteke.
       2 ignorisane datoteke.

github.com/AlDanial/cloc v 2.00  T=0.02 s (116.5 datoteka/s, 12461.4 linija/s)
-------------------------------------------------------------------------------
Jezik                       datoteke       prazno         komentar          kod
-------------------------------------------------------------------------------
Java                             2             61              5            148
-------------------------------------------------------------------------------
SUMA:                            2             61              5            148
-------------------------------------------------------------------------------


Analiza korišćenjem SpotBugs:

IntelliJ SpotBugs dodatak: pronađeno 0 grešaka u 0 klase
