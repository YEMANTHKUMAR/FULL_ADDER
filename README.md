# FULL_ADDER
# Truth Table
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/02ead8f5-d958-4c89-ac51-368ca086cf41)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e427a3bbc)

VERILOG CODE:
``````
module fulladder(a,b,c,sum,carry);
input a,b,c;
output sum,carry;
wire w1,w2,w3;
xor x1(w1,a,b);
xor x2(sum,w1,c);
and x3(w2,a,b);
and x4(w3,w1,w2);
or x5(carry,w3,w2);
endmodule
``````
OUTPUT:

![image](https://github.com/YEMANTHKUMAR/FULL_ADDER/assets/160569469/8357e646-d374-4cd5-83ef-153a9880d24d)
