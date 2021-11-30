## Argument from Analogy (version 1)

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

As in prospecting for gold, a scientist may dig with skill, courage, energy and intelligence just a few feet away from a rich vein - but always unsuccessfully. Consequently in scientific research the rewards for industry, perseverance, imagination and intelligence are highly uncertain [^1].

---

### Argument in formal language

```javascript
defeasible_rule(correct(P,C2),[similar(C1,C2),correct(P,C1)])[as(argument_from_analogy_v1)].
```

### Argument in natural language

```html
The proposition <P> is true/false to <C1>. It’s known that <C1> and <C2> are similar. 
Therefore, for analogy, the proposition <P> is also true/false to <C2>.
```


<br/>



## Argument from Analogy (version 2)

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

As in prospecting for gold, a scientist may dig with skill, courage, energy and intelligence just a few feet away from a rich vein - but always unsuccessfully. Consequently in scientific research the rewards for industry, perseverance, imagination and intelligence are highly uncertain [^1].

---

### Argument in formal language

```javascript
defeasible_rule(correct(P,C2),[similar(C1,C2),correct(P,C1),similarity(S)])[as(argument_from_analogy_v2)].
```

### Argument in natural language

```html
There are/is <S> as a similarity between <C1> and <C2>. 
This similarity is relevant to conclude that if the sentence <P> is true for <C1>, 
probably this sentence will be true for <C2> too.
```

[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.10. 2008. 
