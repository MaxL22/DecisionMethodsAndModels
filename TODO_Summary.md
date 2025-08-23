# I Decision Problems

# II Basic Decision Models

## Structured preferences

### II.1

TODO:
  * Es II.1.3: in generale con più variabili? soluzioni grafiche?
  * Es II.1.5: soluzione analitica? Non solo grafica?
  * Es II.1.6: wtf

### II.2

Go back to the first exercise, write the whole process.

Math prog: graphical representation, you have to practice it bitch

KKT and how to solve KKT problems
  * Linearly independent gradients? What is linear independence, how to check it on gradients
  * How to get KKT?

Process for mathematical programming problems:
  * draw a graphical representation (analisi di funzione :(, wtf, I didn't sign up for this)
  * calculate gradients
  * something about gradients not being zero? 
  * check nonregular points, i.e., check the intersections of each pair of constraints and that all gradients are linearly independent in the intersections
  * Generalized function (?)
  * KKT conditions
  * Solve KKT conditions: start from the simplest constraint and "restrict the field", basically a search tree on the (kinda strict) conditions of $\mu_i g_i = 0$, by dividing them in the cases of:
    1. $u_i = 0$ and $g_i \leq 0$
    2. $u_i > 0$ and $g_i = 0$
  * Compare the value of the function in all candidate points (nonregular points automatically get added to the candidate set)

All points in which the gradients of the active ($= 0$) constraints are linearly independent are regular. Only active constraints must be considered. A point is regular if:
  * no active constraints: trivially regular, interior of the feasible region
  * one active constraint: if that constraint's gradient is $\neq 0$
  * more than one active constraint: the gradients of those constraints have to be linearly independent
