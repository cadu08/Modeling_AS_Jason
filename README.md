# Modeling argumentation Schemes from Walton

 <br/>

## Argument from sign

<table>
  <tr>
    <td height="40">Minor Premise</td>
    <td height="40">Given data represented as statement A is true in this situation.</td>
  </tr>
  <tr>
    <td height="40">Major Premise</td>
    <td height="40">Statement B is generally indicated as true when its sign, A, is true, in this kind of situation</td>
  </tr>
  <tr>
     <td height="40">Conclusion</td>
     <td height="40">Therefore, B is true in this situation.</td>
  </tr>
</table>

---

The major premise is a conditional statement that if A is true, then generally, but subject to exceptions, B is also true. This generalization is defeasible. The tracks could have been planted on the trail by tricksters. But in the absence of evidence of some trickery, it is reasonable to provisionally draw the conclusion that a bear passed along the trail. [^1]

---

> Argument in formal language

```javascript
defeasible_rule(passed(A,B),[there_are(A_Marks,B)])[as(from_sign)].
    cq(cq1, not planted(A_Marks)).
```

> Argument in natural language

```html
There are <A_Marks> on the <B>. Therefore, a <A> passed along the <B>.
```


 <br/>



## Argument from analogy (version 1)

<table>
  <tr>
    <td height="40">Major Premise</td>
    <td height="40">Generally, case C1 is similar to case C2.</td>
  </tr>
  <tr>
    <td height="40">Minor Premise</td>
    <td height="40">Proposition A is true/false in case C1.</td>
  </tr>
   <tr>
    <td height="40">Conclusion</td>
     <td height="40">Proposition A is true/false in case C2.</td>
  </tr>
</table>

---

As in prospecting for gold, a scientist may dig with skill, courage, energy and intelligence just a few feet away from a rich vein - but always unsuccessfully. Consequently in scientific research the rewards for industry, perseverance, imagination and intelligence are highly uncertain. [^2]

---

> Argument in formal language

```javascript
defeasible_rule(correct(P,C2),[similar(C1,C2),correct(P,C1)])[as(argument_from_analogy_v1)].
```

> Argument in natural language

```html
The proposition <P> is true/false to <C1>. It’s known that <C1> and <C2> are similar. Therefore, for analogy, the proposition <P> is also true/false to <C2>.
```


<br/>



## Argument from analogy (version 2)

<table>
  <tr>
    <td height="40">Major Premise</td>
    <td height="40">Generally, case C1 is similar to case C2.</td>
  </tr>
   <tr>
    <td height="40">Relevant Similarity Premise</td>
    <td height="40">The similarity between C1 and C2 observed so far is relevant to the further similarity that is in question.</td>
  </tr>
  <tr>
    <td height="40">Minor Premise</td>
    <td height="40">Proposition A is true/false in case C1.</td>
  </tr>
   <tr>
    <td height="40">Conclusion</td>
     <td height="40">Proposition A is true/false in case C2.</td>
  </tr>
</table>

---

As in prospecting for gold, a scientist may dig with skill, courage, energy and intelligence just a few feet away from a rich vein - but always unsuccessfully. Consequently in scientific research the rewards for industry, perseverance, imagination and intelligence are highly uncertain. [^3]

---

> Argument in formal language

```javascript
defeasible_rule(correct(P,C2),[similar(C1,C2),correct(P,C1),similarity(S)])[as(argument_from_analogy_v2)].
```

> Argument in natural language

```html
There are/is <S> as a similarity between <C1> and <C2>. This similarity is relevant to conclude that if the sentence <P> is true for <C1>, probably this sentence will be true for <C2> too.
```

<br/> <br/>

[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.10. 2008. 

[^2]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.56. 2008.

[^3]: WALTON, D.; REED, C.; MACAGNO, F. apud KUBIE, 1954, p. 111. Argumentation Schemes. Cambridge University Press. p.59. 2008.
