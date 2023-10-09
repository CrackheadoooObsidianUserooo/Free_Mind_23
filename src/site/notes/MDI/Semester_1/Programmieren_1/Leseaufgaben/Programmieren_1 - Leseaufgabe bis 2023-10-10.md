---
{"dg-publish":true,"permalink":"/mdi/semester-1/programmieren-1/leseaufgaben/programmieren-1-leseaufgabe-bis-2023-10-10/","tags":["Programmieren_1","Leseaufgabe","MDI"]}
---

# Fragen

1. ? Was versteht man unter [[Programmierkonventionen\|Programmierkonventionen]]❓
{ #bluuks}

	1. $ > "Eine Vereinbarkeit zwischen Menschen um die Lesbarkeit von Programmen für Menschen zu verbessern." → [[PR1_01_L.drvd.pdf#page=4&selection=143,0,173,43\|PR1_01_L.drvd, page 4]]
		1. Sun style
		2. Allman Style
2. ? Was stimmt an dem folgenden Statement nicht❓
	1. `System.out.println("C:\Users\norbert\Documents\teafortwo");`
		1. $ Die Backslashes brauchen einen eigenen Backslash 
			1. $ `("C:\\Users\\norbert\\Documents\\teafortwo")`
			2. Sowas nennt man dan escape sequence (wenn ein String Spezialzeichen durch ein Backslash einleitet)
{ #00428y}

			3. Ich dachte man müsse, vor jedem Sonderzeichen ein Backlash machen
3. ? Warum gibt es hier einen Compilerfehler
	1. ` public static void break(){ System.out.println("Spielabbruch"); }`
		1. $ 
4. ? Welche Sekundärtugenden brauchen Programmiererinnen und Programmierer❓
	1. $ Menschlichkeit, Kreativität, Selbstverwirklichung, Solidarität
5. ? Mit welchem Ausdruck isoliert man die letzte Ziffer einer Zahl❓
	1. $ `% 10`
6. ? Mit welchem Ausdruck isoliert man die vorletzte Ziffer einer Zahl❓
	1. $ `% 100 / 10`
7. ? Wie lautet die Ausgabe des folgenden Statements❓
	1. `System.out.println( 1.3 * 5 – 5 / 2 );`
		1. $ 
8. ? Warum lautet die Ausgabe von
	1.  `System.out.println(0.1 + 0.1 + 0.1);` nicht `0.3` ❓
		1. $ Der Grund: Die Zahl 0.1 ist in der internen Bitdarstellung nicht exakt darstellbar. Der leicht gerundete Wert wird nun dreifach addiert. Der Rundungsfehler vergrößert sich dadurch.

# Lesen sie die folgenden Abschnitte

- L. 1.3 - L.1.5 (einschl)
- L. 2.1 - L.2.5 (einschl)




# Auseinandernehmen







- [ ] ? Was ein Methodenkopf
	- Deklaration und Definiton einer Methode
- 
- 




# ` public static void main (String[] args)

- `public static void main(String[] args) { }` 
{ #yiin0b}

	- 🔎 ``
	- `public` 
		- ist ein sogenannter Modifier
			- ein [[Modifier\|Modifier]] legt die Sichtbarkeit von Programmelementen fest.
		- `public` erlaubt das ich von außerhalb der class auf die Methode zugreifen kann
	- `static` 
		- damit mach ich die Methode statisch
		- und unabhängig von der class in der sie steht
	- `void` kennzeichnet das die Methode kein Rückgabewert hat
		- ? Was ist ein Rückgabewert
	- [ ] ? `main(String[] args)`
		- [ ] ? Warum die Klammern und warum an dem Ort 
		- [ ] ? Was bedeutet main 
		- [ ] ? Warum die eckigen Klammern  und warum an dem Ort
		- [ ] ? Was bedeutet args




- ? Was ist ein Compiler




# Sonstiges

- [ ] L.1.3.1 Programmierfehler identifizieren → [[PR1_01_L.drvd.pdf#page=4&selection=46,1,50,82\|PR1_01_L.drvd, page 4]]


- [ ] ? Was ist ein `class` in Java
- [ ] ? Was ist eine Methode in Java
- [ ] ? Was bringt mir es das ich von außerhalb auf die Methode zugreifen kann 
- [ ] ? Was ist ein Programmelement
- [ ] ! Ich weiß garnicht was `public static void main(String[] args)` bedeutet → [[MDI/Semester_1/Programmieren_1/Leseaufgaben/Programmieren_1 - Leseaufgabe bis 2023-10-10#^yiin0b\|Programmieren_1 - Leseaufgabe bis 2023-10-10#^yiin0b]]
- [ ] ? Was ist ein Compiler
- [ ] ? Warum kann man sagen, das der String etwas einleitet❓ → [[MDI/Semester_1/Programmieren_1/Leseaufgaben/Programmieren_1 - Leseaufgabe bis 2023-10-10#^00428y\|Programmieren_1 - Leseaufgabe bis 2023-10-10#^00428y]]
- [ ] ? Übungsaufgabe machen → [[PR1_01_L.drvd.pdf#page=5&selection=222,0,226,31\|PR1_01_L.drvd, page 5]]
- [ ] ? Übungsaufgabe machen → [[PR1_01_L.drvd.pdf#page=5&selection=179,1,179,13\|PR1_01_L.drvd, page 5]]
- [ ] ? Ich verstehe die Seite nicht → [[PR1_01_L.drvd.pdf#page=5&selection=63,0,226,29\|PR1_01_L.drvd, page 5]]
- [ ] ? nochmal lesen → [[PR1_01_L.drvd.pdf#page=6&selection=0,24,445,18\|PR1_01_L.drvd, page 6]]



