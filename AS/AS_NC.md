## Necessary Condition Schema

<table>
  <tr>
    <td height="40">Goal Premise</td>
    <td height="40">
        Bringing about Sn is my goal.
    </td>
  </tr>
  <tr>
    <td height="40">Means Premise</td>
    <td height="40">In order to bring about Sn, I need to bring about Si.</td>
  </tr>
   <tr>
    <td height="40">Conclusion</td>
     <td height="40">Therefore, I need to bring about Si.</td>
  </tr>
</table>

The 'need to' in the conclusion expresses what is called a "practical ought," conveying the idea that if the rational agent is prudem, it ought to bring about Si;
if it is committed to both premises of the argumentation scheme for practical reasoning. [^1]

### Necessary-condition Schema [^1]

```
(N1) My goal is to bring about A (Goal Premise).
(N2) I reasonably consider on the given information that bringing about at least one of [B0, B1, B2] is necessary to bring about A (Alternatives Premise)
(N3) I have selected one member Bi as an acceptable, or as the most acceptable necessary condition for A (Selection Premise)
(N4) Nothing unchangeable prevents me from bringing about Bi as far as I know (Practicality Premise).
(N5) Bringing about A is more acceptable to me than not bringing about Bi (Side-Effects Premise).
Therefore, it is required that I bring about Bi (Conclusion).
```

Practical reasoning is put forward by a rational agent, typically in a deliberation dialogue with another rational agent or group of agents. The respondent agent can then
pose critical question in dialogue. Following the analysis of Walton (1990) [^2], five critical question are given.

### Critical Questions [^2]

```
Other-Means Question: Are there alternative possible action to bring about Si that could also lead to the goal?
Best-Means Question: Is Si the best (or most favorable of the alternatives?)
Other-Goals Question: Do I have goals other than Si whose achievement is preferable and that should have priority?
Possibly Question: Is it possible to bring about Si in the given circumstances?
Side Effects Question: Would bringing about Si have known bad consequences that ought to be taken into account?
```

---

### Argument in formal language

``` javascript
defeasible_rule(goal(Sn),[necessary_condition(Sn,Si)])[as(n_condition)].
	cq(cq1, not alternatives(Si))[as(n_condition)].
	cq(cq2, best(Si))[as(n_condition)].
	cq(cq3, not other_preferable_goal(Sj))[as(n_condition)].
	cq(cq4, possible(Si))[as(n_condition)].
	cq(cq5, not bad_consequences(Si))[as(n_condition)].
```

### Argument in natural language

``` html

Bringing about <Sn> is my goal.
In order to bring about <Sn>, bring about <Si> is necessary. 
Therefore, I need to bring about <Si>.

```

---

As practical reasoning is used in a given case, the putting forward of an argument having the form of practical reasoning shifts a weight of plausibility from the premises
to the conclusion, indicating that the agent should provisionally go ahead with committing to Si. However, practical reasoning is commonly defeasible, subject to further 
dialogue. Asking any one of these five critical questions can defeat the argumentation, at least temporarily. Once the proponent gives an adequate answer to the question, 
however, the burden shifts back to the respondent. He must then commit to the conclusion unless he asks another appropriate critical question. This process can continue until
the dialogue reaches the closing stage. Except under closure conditions, practical reasoning is a defeasible form of argumentation. It can default, or be defeated, at any
point during the argumentation stage of a dialogue, as long as that stage continues.[^1]


[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.95. 2008.
[^2]: WALTON, D. The Journal of Philosophy. Department of Philosophy at Columbia University. 1990.
