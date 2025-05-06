# ELECTRE-III
The ELECTRE-III method for the multicriteria ranking problem

How to run in Windows?


1) Open CMD program in Windows,
2) move to the directory where your unzip the electreIII-win.zip file and
3) execute the electreIII.exe file.

If you unzip your file in the drive c:\ you can run as follows in the CMD program
c:\electreIII\electreIII

It will run the electre-III with a data test in the input directory. Modify the data files in input directory to use your data.  

Description of the input and output data


Example electreIII

Running as electreIII

## Input
direction.txt
0:minimization or 1 maximization

g_1

g_2

...

g_m


### intercriteria.txt
> The space between data is tab [\t]

w_1 w_2 ... w_n

q_1 q_2 ... q_n

p_1 p_2 ... p_n

v_1 v_2 ... v_n

### performance.txt
g(a1_1) g(a1_2) ... g(a1_n)

g(a2_1) g(a2_2) ... g(a2_n)

...

g(am_1) g(am_2) ... g(am_n)

### problem.txt
4	'number of alternatives

3	'number of criteria

### use_veto.txt
> specify if the criterion use veto factor (0 do not use veto) or (1 use veto)

g_1

g_2

...

g_m

Output
It is a valued outranking matrix and ranking relation.
