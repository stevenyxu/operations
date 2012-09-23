operations
==========

Given a sequence of numbers, figure out how to get a target total using only +, -, *, /, and parentheses.

Example usage
-------------

Run `ruby ./example.rb`. Output:

```
OPERATIONS
----------

Using number sequence 1 2 3 4 5 6 7

Ways to get 100
---------------
100=-1+2.superplus(3)*4*5-6+7
100=1+2.superplus(3)*4*5+6-7
100=-1*2+3*4*5+6*7
100=-1+2*3*4+5.superplus(6)*7
100=-1*2-3+4.superplus(5).superplus(6)*7
100=1-2*3+4.superplus(5).superplus(6)*7
100=-1*2.superplus(3)+4.superplus(5).superplus(6)*7
100=1*2.superplus(3)*4*5+6/7
100=1*2.superplus(3)*4*5-6/7
100=1+2.superplus(3)*4*5+6.superminus(7)
100=-1+2.superplus(3)*4*5-6.superminus(7)
100=-1*2.superplus(3)*4*5*6.superminus(7)
100=-1*2.superplus(3)*4*5/6.superminus(7)

1 way to get each number up to 100
----------------------------------
1=1/2-3-4-5+6+7
2=1.superminus(2).superminus(3)*4+5+6+7
3=-1-2-3*4+5+6+7
4=-1*2-3*4+5+6+7
5=-1.superminus(2)*3-4+5+6+7
6=1/2-3*4+5+6+7
7=-1-2*3-4+5+6+7
8=-1-2-3-4+5+6+7
9=-1*2-3-4+5+6+7
10=1-2-3-4+5+6+7
11=1/2-3-4+5+6+7
12=-1+2-3-4+5+6+7
13=-1.superminus(2)*3+4+5+6+7
14=-1-2+3-4+5+6+7
15=-1-2*3+4+5+6+7
16=-1-2-3+4+5+6+7
17=-1*2-3+4+5+6+7
18=1-2-3+4+5+6+7
19=1/2-3+4+5+6+7
20=-1+2-3+4+5+6+7
21=1*2-3+4+5+6+7
22=-1-2+3+4+5+6+7
23=-1*2+3+4+5+6+7
24=1-2+3+4+5+6+7
25=1/2+3+4+5+6+7
26=-1+2+3+4+5+6+7
27=1*2+3+4+5+6+7
28=1+2+3+4+5+6+7
29=1+2*3+4+5+6+7
30=1/2+3*4+5+6+7
31=1.superplus(2)*3+4+5+6+7
32=1*2+3*4+5+6+7
33=1+2+3*4+5+6+7
34=-1.superplus(2).superplus(3)*4+5+6+7
35=1-2+3+4*5+6+7
36=1/2+3+4*5+6+7
37=-1+2.superplus(3)*4+5+6+7
38=1*2.superplus(3)*4+5+6+7
39=1+2.superplus(3)*4+5+6+7
40=1+2*3+4*5+6+7
41=-1+2*3*4+5+6+7
42=1*2*3*4+5+6+7
43=1+2*3*4+5+6+7
44=1.superplus(2)*3*4-5+6+7
45=-1-2+3.superplus(4)*5+6+7
46=-1*2+3.superplus(4)*5+6+7
47=1-2+3.superplus(4)*5+6+7
48=1/2+3.superplus(4)*5+6+7
49=-1+2+3.superplus(4)*5+6+7
50=1*2+3.superplus(4)*5+6+7
51=1+2+3.superplus(4)*5+6+7
52=1+2+3*4+5*6+7
53=1.superminus(2).superplus(3)*4*5+6+7
54=1.superplus(2)*3*4+5+6+7
55=1*2*3*4.superplus(5)-6+7
56=1+2*3*4.superplus(5)-6+7
57=-1+2.superplus(3).superplus(4)*5+6+7
58=1*2.superplus(3).superplus(4)*5+6+7
59=1+2.superplus(3).superplus(4)*5+6+7
60=1-2+3*4*5-6+7
61=1/2+3*4*5-6+7
62=-1+2+3*4*5-6+7
63=1.superplus(2).superplus(3).superplus(4)*5+6+7
64=1+2+3*4*5-6+7
65=-1+2+3+4.superplus(5)*6+7
66=-1+2*3*4.superplus(5)+6+7
67=1*2*3*4.superplus(5)+6+7
68=1+2*3*4.superplus(5)+6+7
69=1*2*3.superplus(4)*5+6-7
70=-1-2+3*4*5+6+7
71=-1*2+3*4*5+6+7
72=1-2+3*4*5+6+7
73=1/2+3*4*5+6+7
74=-1+2+3*4*5+6+7
75=1*2+3*4*5+6+7
76=1+2+3*4*5+6+7
77=-1*2+3.superplus(4).superplus(5)*6+7
78=1-2+3.superplus(4).superplus(5)*6+7
79=1/2+3.superplus(4).superplus(5)*6+7
80=-1+2+3.superplus(4).superplus(5)*6+7
81=-1.superplus(2).superplus(3)*4*5-6+7
82=-1+2*3.superplus(4)*5+6+7
83=1*2*3.superplus(4)*5+6+7
84=1+2*3.superplus(4)*5+6+7
85=-1.superplus(2).superplus(3).superplus(4).superplus(5)*6+7
86=1*2+3.superplus(4)*5.superplus(6)+7
87=1+2+3.superplus(4)*5.superplus(6)+7
88=1+2.superplus(3)*4*5-6-7
89=1/2+3*4+5.superplus(6)*7
90=-1+2.superplus(3).superplus(4).superplus(5)*6+7
91=1*2.superplus(3).superplus(4).superplus(5)*6+7
92=1+2.superplus(3).superplus(4).superplus(5)*6+7
93=-1.superplus(2).superplus(3)*4*5+6+7
94=1.superplus(2)*3*4.superplus(5)+6+7
95=1.superminus(2).superplus(3)*4*5.superplus(6)+7
96=-1+2.superminus(3).superplus(4)*5*6+7
97=1*2.superminus(3).superplus(4)*5*6+7
98=1+2.superminus(3).superplus(4)*5*6+7
99=1*2.superplus(3)*4*5+6-7
100=-1+2.superplus(3)*4*5-6+7
```
