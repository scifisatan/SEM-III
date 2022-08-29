![[full adder]]

### mental note
- basically how mux works is an input is selected as output depending on the combination of selector variables
- for 4 inputs we need to have atleast 2 selector variable. 2 selector variable with create 4 unique combinations and we can link each one of those combination as a way to select one of the inputs as output
- so in this full adder we are trying to see that in what combination of A and B is sum/carryout =1 and what the value of Cin is in that instance.
- if you see truth table when a=0 and b=0 and sum = 1, cin is 1. so first input of 4x1 mux would be cin
- second if you see when a =0 and b=1 and sum = 1, cin is 0, that means second input of 4x1 mux would be cin complement 
	 ![[Pasted image 20220829135159.png]]
- in that way the final design of mux would look like
	![[Pasted image 20220829132558.png]]
- similarly for the carry
	![[Pasted image 20220829132624.png]]
