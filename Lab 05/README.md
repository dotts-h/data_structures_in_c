# Lab_5 - Stacks

## Stiva Dinamica - Dynamic Stack

### Operatii Principale - Main Operation

> Se considera o stiva implementata dinamic prin utilizarea unei liste simplu (sau dublu) inlantuite. Fiecare element al stivei va contine un singur caracter. Sa se implementeze urmatoarele operatii de baza ce pot fi selectate prin intermediul unui meniu
> Let there be a stack implemented with dynamic memory allocation using a linked list or a doubly linked list. Each node of the stack should contain one character. Implement the following operations which can be selected via a menu

- Push
- Pop
- Peek
- Is Empty
- Clear

## Operatii Extinse - Extra Operation

> Sa se adauge optiunea "Verificarea expresiei" la meniul precedent, pentru a permite efectuarea verificarii unei secvente de paranteze si simboluri. Sirul este prelucrat astfel incat elementele sale sa fie adaugat si scoase din stiva automat (prin operatii de push si pop)
> Add the option "Check expression" which should allow verification of a sequence of paranthesis and symbols. The sequence is analyzed by putting its elements into the stack and taking them out (via push and pop actions)

## Stiva Statica - Static Stack

### Operatii Principale - Main Operations

> Sa se afiseze un meniu ce contine doua optiuni corespunzatoare tipului de stiva implementata
> Show a menu which has two options related to each type of stacks

- Static Stack
- Extendable Static Stack

> Din selectarea oricarei optiuni se va afisa meniul ce permite construirea stivei
> By selecting any option it should show the menu which allows building the stack

- Push
- Pop
- Clear

### Operatii Extinse - Extra Options

> Sa se afiseze un meniu ce contine doua optiuni corespunzatoare tipului de stiva implementata
> Show a menu which has two options related to each type of stacks

- Static Stack
- Extendable Static Stack

> Din selectarea oricarei optiuni se va afisa meniul ce permite construirea a doua stive
> By selecting any option it should show the menu which allows building 2 stacks

- Push1 & Push2
- Pop1 & Pop2 (print elements)
- Clear1 & Clear2 (print elements)
- Generate 3rd stack
- Pop3 (print elements)
- Clear3 (print elements)

Stack_1{
id;
quantity;
}
Stack_2{
id;
price;
}

> La selectarea operatiei "Generare stiva 3" se va construi automat o a treia stiva pe baza stivelor 1 si 2 (prin apelul succesiv al functiei "pop" asupra celor 2 stive). Se considera ca elementele stivelor 1 si 2 sunt sortate dupa cod (la introducere).
> When selecting "Generate 3rd stack" a new stack will be generated based on the first two stacks (by calling pop on each of them). It is considered that the 2 stacks are sorted at creation

Stack_3{
id;
quantity;
price;
}

> Daca un produs nu se regaseste in stiva pereche, campul corespunzator se va completa cu -1
> If an item cannot be found in it's pair stack, the field should have the value -1
