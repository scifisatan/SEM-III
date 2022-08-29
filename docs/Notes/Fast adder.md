**Alternative names**: Carry Look Ahead Adder/ CLA adder
**main point of fast adder**: to predict the carry
## Introduction
- For other adders to produce output, it takes certain amount of time and when we combine multiple of them to make an n-bit adder, it is slower as it has to go throught every adder one by one to wait for the carry
- to mitigate this problem fast adder is used and it basically predicts the carry which makes it more different from other adders

![[full adder#Truth Table for full adder]]


- If you see the truth table, when both A and B are high, the carry out is high independent of Cin
	![[Pasted image 20220829133651.png]]
	And the equation from it can be written as:
	![[Pasted image 20220829134235.png]]

- Also when A and B are complement of each other and Cin is 1, Carry out is 1.
	![[Pasted image 20220829134010.png]]
	Similary, the equation becomes:
	![[Pasted image 20220829134251.png]]

- Combining both of the above
	![[Pasted image 20220829134139.png]]
	![[Pasted image 20220829134546.png]]

- For n-bit adder, we can generalize the above equation as:
	![[Pasted image 20220829134515.png]]
	Logic behind this would be carry out of one adder will be carry out of another adder

Let us take 4-bit adder then:
[Carry Lookahead Adder (Part 2)](https://www.youtube.com/watch?v=9lyqSVKbyz8)


