**1)**

  G = ({A,S}, {a,b,c}, P, S)

  P = {

    S -> A | c

    A -> aAb | bAa | c

  }

**2)**

  G = ({S}, {a,b}, P, S)

  P = {

    S -> aSb | aaSb | epsilon

  }

**3)**

G = ({S, A}, {a,b}, P, S)

P = {

  S -> Ab
  
  A -> aAa | aAb | bAa | bAb | a
  
}
**2)**

  G = ({S}, {a,b}, P, S)

  P = {

    S -> Ab

    A -> aAa | aAb | bAa | bAb | a

  }
  
**4)**

**5)**

  G = ({S}, {a,b}, P, S)

  P = {

    S -> SaSbSbS | SbSaSbS | SbSbSaS | epsilon

  }
  
**6)**

  G = ({S,A}, {a,b}, P, S)

  P = {

    S -> AA
    A -> aAb | epsilon

  }

**7)**

  G = ({S,S',S",A,B,C}, {a,b,c}, P, S)

  P = {

    S -> S' | S"
    S' -> AC
    S" -> BC
    A -> aA | aAb | epsilon
    B -> Bb | aBb | epsilon
    C -> cC |epsilon

  }
