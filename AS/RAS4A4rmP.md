## Refutation Scheme for Argument from Precedent

<table>
  <tr>
    <td height="40">Major Premise</td>
    <td height="40">Generally, according to the stablished rule, if x has property F, then x also has property G.</td>
  </tr>
  <tr>
    <td height="40">Minor Premise</td>
    <td height="40">Is this legitimate case, A has property F but does not have property G.</td>
  </tr>
   <tr>
    <td height="40">Conclusion</td>
     <td height="40">Therefore, an exception to the rule must be recognized, and the rule must be appropriately modified or qualified.</td>
  </tr>
</table>

---

The following critical questions represent strategies to defend the argument from established rule by attacking the opponent's argument.[^1]

### Critical Questions
```html
CQ1: Does the established rule really apply to this case?
CQ2: Is this case cited legitimate, or can it be explained as only an apparent violation of the rule?
CQ3: Can the case cited be dealt with under an already recognized category of exception that does not require a change in the rule?
```

---

### Argument in formal language

```javascript
defeasible_rule(must_modify(RULE,CASE),[usual_consequence(X,PropertyF,PropertyG),property(X,PropertyF)])[as(refut_4A4rm_precedent)].
  cq(cq1, apply(RULE,CASE))[as(refut_4A4rm_precedent)].
  cq(cq2, legitimate(CASE))[as(refut_4A4rm_precedent)].
  cq(cq2, already_recognized_category(CASE))[as(refut_4A4rm_precedent)].
```

### Argument in natural language

```html
Generally, according to the stablished <RULE> rule, if <X> has property <PropertyF>, then <X> also has property <PropertyG>.
However, in <CASE> case, the <X> does not have property <PropertyG>.
Therefore, an exception to the rule must be recognized, and the rule must be apropriately modified or qualified."
```

[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.73. 2008. 
