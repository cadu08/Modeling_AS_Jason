## Argument from Sign

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

The major premise is a conditional statement that if A is true, then generally, but subject to exceptions, B is also true. This generalization is defeasible. The tracks could have been planted on the trail by tricksters. But in the absence of evidence of some trickery, it is reasonable to provisionally draw the conclusion that a bear passed along the trail [^1].

---

### Argument in formal language

```javascript
defeasible_rule(passed(A,B),[there_are(A_Marks,B)])[as(from_sign)].
    cq(cq1, not planted(A_Marks)).
```

### Argument in natural language

```html
There are <A_Marks> on the <B>. Therefore, a <A> passed along the <B>.
```


[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.10. 2008. 
