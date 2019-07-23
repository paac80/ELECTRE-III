# ELECTRE-III
The ELECTRE-III method for the multicriteria ranking problem

How to run?

electreIII 

Description of the input and output data
The input files shoul be saved in a directory inside the /projects

Example electreIII

Running as electreIII

Input
direction.txt
0:minimization or 1 maximization

g_1

g_2

...

g_m


intercriteria.txt
The space between data is tab [\t]

w_1 w_2 ... w_n

q_1 q_2 ... q_n

p_1 p_2 ... p_n

v_1 v_2 ... v_n

performance.txt
g(a1_1) g(a1_2) ... g(a1_n)

g(a2_1) g(a2_2) ... g(a2_n)

...

g(am_1) g(am_2) ... g(am_n)

problem.txt
4	'number of alternatives

3	'number of criteria

use_veto.txt
specify if the criterion use veto factor (0 do not use veto) or (1 use veto)

g_1

g_2

...

g_m

Output
It is a valued outranking matrix and ranking relation.
