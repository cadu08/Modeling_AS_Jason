## Defeasible Argument From a Verbal Classification
<table>
  <tr>
    <td height="40"> Major Premise </td>
    <td height="40"> If some particular thing A can be classified as falling under verbal category C, then A has property F (in virtue of such a classification) </td>
  </tr>
  <tr>
    <td height="40"> Minor Premise </td>
    <td height="40"> A can be classified as falling under verbal category C </td>
  </tr>
  <tr>
     <td height="40"> Conclusion </td>
     <td height="40"> A has property F </td>
  </tr>
</table>

---

If there is a problem concerning the definition of a key term, the classification can be questioned, and the argument may be weakened or even defeated. This can be done by attacking the generalization or by questioning whether it fits the particular thing at issue. The two critical questions focus on the application of the generalization to the concrete case, and on its strength. [^1]

---

### Critical Questions

```
CQ1: Does A definitely have F, or is there room for doubt?
CQ2: Can the verbal classification (in the second premise) be said to hold strongly, or is it one of those weak classifications that is subject to doubt?
```

---

[...] the plausibility of the argument resides in the assumption that the classification, implicitly or explicitly, leads by inference to the conclusion claimed. In the heresy case, the fact that heresy is generally considered wrong is the implicit classification that is the concealed basis of the plausibility of the argument.[^1]

---

### Argument in formal language

```javascript
defeasible_rule(property(A,F),[categorie(A,C),property(C,F)])[as(from_verbal_classification)].
  cq(cq1, not doubt(A,F))[as(from_verbal_classification)].
  cq(cq2, not weak(A,F))[as(from_verbal_classification)].
```

### Argument in natural language

```html
All <C> is <F>. <A> can be classified as <C>. Therefore, <A> is <F>.
```

### Example adapted from Walton's book

```html
All <heresy> is <punishable>. 
<John's affirmation> can be classified as <heresy>.
Therefore, <John's affirmation> is <punishable>.
```

It is noteworthy that this argument is similar to the previous one, [Argument from Classification](https://github.com/cadu08/Modeling_AS_Jason/blob/main/AS/ASfromC.md). The difference is the critical question that makes the argument questionable rather than autocratic. Now, e.g., there may be doubts regarding the established relationship between Jhon's affirmation and heresy, making the argument inconclusive and therefore defeasible.

<br>

[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.68. 2008.
