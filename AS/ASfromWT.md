## Argument from Witness Testemony

<table>
  <tr>
    <td height="40">Position to Know Premise</td>
    <td height="40">
        Witness W is in a position to know whether A is true or not.
    </td>
  </tr>
  <tr>
    <td height="40">Truth Telling Premise</td>
    <td height="40">Witness W is telling the truth (as W knows it)</td>
  </tr>
  <tr>
    <td height="40">Statement Premise</td>
     <td height="40">Witness W states that A is true (or false).</td>
  </tr>
  <tr>
    <td height="40">Conclusion</td>
     <td height="40">A may be plausibly taken to be true (or false).</td>
  </tr>
</table>

---

### Critical Questions
```html
CQ1: Is what the witness said internally consistent?
CQ2: Is what the witness said consistent with the known facts of the case (based on evidence apart from what the witness testified to)?
CQ3: Is what the witness said consistent with what other witnesses have (independently) testified to?
CQ4: Is there some kind of bias that can be attributed to the account given by the witness?
CQ4: How plausible is the statement A asserted by the witness?
```

---

### Argument in formal language

```javascript
defeasible_rule(plausible(A,BOOLEAN),[position_to_know(W,A),is_telling_the_truth(W),statement(W,A,BOOLEAN)])[as(as4wt)].
  cq(cq1, is_internally_consistent(A,BOOLEAN))[as(as4wt)].
  cq(cq2, is_consistent_with_the_facts(A,BOOLEAN))[as(as4wt)].
  cq(cq3, is_consistent_with_other_testemonies(A,BOOLEAN))[as(as4wt)].
  cq(cq4, not there_is_some_bias(W,A,BOOLEAN))[as(as4wt)].
  cq(cq5, not how_plausible_is_witness_statement(W,low))[as(as4wt)].
```

### Argument in natural language

```html
  <A> may be plausibly taken to be <BOOLEAN>.
```

[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.310. 2008.
