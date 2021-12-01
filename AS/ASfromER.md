## Argument from an Established Rule

<table>
  <tr>
    <td height="40">Major Premise</td>
    <td height="40">
        If carrying out types of actions including the state of affairs A is the established rule for X, then (unless the case is an exception), X must carry out A.
    </td>
  </tr>
  <tr>
    <td height="40">Minor Premise</td>
    <td height="40">Carrying out types of actions including the state of affairs A is the established rule for a.</td>
  </tr>
   <tr>
    <td height="40">Conclusion</td>
     <td height="40">Therefore, a must carry out A.</td>
  </tr>
</table>

---

It can be seen that the pattern of this scheme is similar to that of argument from verbal classification. But it differs from the latter because it belongs to a different kind of dialogue, that of deliberation, and because the missing premise itself, the generalization, is differently supported. The critical questions are directed against the generalization in the rule. [^1].

---

### Critical Questions
```html
CQ1: Does the rule require carrying out types of actions that include A as an instance?
CQ2: Are there other stablished rules that might conflict with, or override, this one?
CQ3: Is this case as exceptional one, that is, could be there be extenuating circumstances or an excuse for noncompliance?
```
The last critical question concerns the problem of the exceptional case. It is the problem of the classification of the situation as falling under the law or rule. The counterargument is a kind of rebuttal of the implicit assumption that the case in question represents an instance of the rule. [^1]

### Argument in formal language

```javascript
defeasible_rule(carry_out(X,A),[rule(X,A)])[as(exceptional_case)].
		cq(cq1, requirements_rule(A))[as(exceptional_case)].
		cq(cq2, not conflicting_rule(B))[as(exceptional_case)].
		cq(cq2, not excuses(E))[as(exceptional_case)].
```

### Argument in natural language

```html
The <A> was established for <X>. Therefore, the <X> must carry out <A>.
```

### A relevant example from Walton's book

``Student:`` I don't think I will be able to get my essay in on Tuesday. Would it be OK if I handed it in next week?<br/>
``Professor:`` We all agreed at the beginning of the year that Tuesday is the deadline. That is the rule.<br/>
``Student:`` But I had a bad case of the flu last week, and I have a note from my physician to prove it.


**_obs:_** The student reply elucidates the argumentation scheme _known as argument from an exceptional case_.[^2]  


[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.81. 2008. 
[^2]: WALTON, D. Argument Structure: A Pragmatic Theory. Department of Philosophy. University of Winnipeg. p.92. Canada. 1996.
