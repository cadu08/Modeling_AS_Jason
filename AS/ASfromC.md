## Argument from Classification

<table>
  <tr>
    <td height="40">Major Premise</td>
    <td height="40">All F's can be classified as G's.</td>
  </tr>
  <tr>
    <td height="40">Minor Premise</td>
    <td height="40">A is an F</td>
  </tr>
  <tr>
     <td height="40">Conclusion</td>
     <td height="40">Therefore, A is a G.</td>
  </tr>
</table>

---

Arguments from classification are based on two main components: the description, or presentation, of the facts or events; and their classification, proceeding from properties presented in the definition itself.[^1]

---

### Argument in formal language

```javascript
defeasible_rule(be(A,G),[class(F,G),be(A,F)])[as(from_classification)].
```

### Argument in natural language

```html
All <F> can be classified as <G>. <A> is an <F>. Therefore, <A> is a <G>.
```

### Example from Walton's book
```
All terrorists can be classified as enemie. Jhon is a terrorist. Therefore, Jhon is an enemie.
```
---

[...] religious discussion where the interlocutor's position is labelled as "heresy." Based merely on this verbal classification, it is concluded that the position itself is wrong, on the implicit basis of the generalization that every heresy is wrong. The opponent's standpoint, in fact, may be heretical on the grounds that everyone, the authorities, or its opponents have classified it under this term. On the other hand, the proponent might have used that definition without any backing [...]. Here, a premise supporting the conclusion can itself be supported only by using the conclusion as a premise[...]. This kind of argument is a device used to avoid the requirement of fulfilling a burden of proof. [^1]

---

[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.67-68. 2008. 
