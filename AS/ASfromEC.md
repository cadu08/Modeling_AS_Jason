## Argument from an Exceptional Case

<table>
  <tr>
    <td height="40">Major Premise</td>
    <td height="40">
        If the case of X is an exception, then the stablished rule can be waived in the case of X.
    </td>
  </tr>
  <tr>
    <td height="40">Minor Premise</td>
    <td height="40">The case of A is an exception.</td>
  </tr>
   <tr>
    <td height="40">Conclusion</td>
     <td height="40">Therefore, the stablished rule can be waived in the case of A.</td>
  </tr>
</table>

---

This form of argument is based on argument from verbal classification. The classification of X as an exception allows the application to it of the property "to be waived." The critical questions stem from the classification. [^1].

---

### Critical Questions
```html
CQ1: Is the case of A a recognized type of exception?
CQ2: If it is not a recognized case, can evidence why the established rule does not apply to it be given?
CQ3: If it is a borderline case, can comparable cases be cited?
```

---

The last critical question concerns the problem of the exceptional case. It is the problem of the classification of the situation as falling under the law or rule. The counterargument is a kind of rebuttal of the implicit assumption that the case in question represents an instance of the rule. [^1]

---

### Argument in formal language

```javascript
defeasible_rule(waived_rule(RULE,CASE),[exceptional_case(RULE, CASE)])[as(from_exceptional_case)].
	cq(cq1, recognized_exception(RULE, CASE))[as(from_exceptional_case)].
	cq(cq2, inapplicability_evidence(EVIDENCE))[as(from_exceptional_case)].
	cq(cq2, comparable_cases(CC))[as(from_exceptional_case)].
```

### Argument in natural language

```html
The case <CASE> is an exception to rule <RULE>. Therefore, this established rule can be waived in this case.
```


[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.72. 2008. 
