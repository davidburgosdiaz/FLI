**1**

   G = ({S,S',S",A,B}, {a,b}, P, S)
   
   P = {
   
    S -> AS'B | AS"B'
    S' -> AS'B | epsilon
    S" -> AS"BB | epsilon
    A -> a
    B -> b
   
   }
   
**2**

   G = ({S,S',A,B}, {a,b}, P, S)
   
   P = {
   
    S -> aS'bb | aaS'b
    S' -> AS'B | epsilon
    A -> aa | epsilon
    B -> bb | epsilon
   
   }
   
**3**

   G = ({S,S',S",A,B}, {0,1}, P, S)
   
   P = {
   
    S -> 0S'
    S' -> A | B | epsilon
    A -> 0S'
    B -> 0S'1
   
   }
   
**4**

  Del estilo del ejr 10.7 pero con mas casos
