# Arguments from Inconsistency




## Argument from inconsistent commitment

"[...] The inconsistency often follows from the proponent's past statements or actions that the opponent brings to light through questioning. In this argumentation, a previously hidden inconsistency may be brought to the surface. In other cases, however, the inconsistency can easily be detected in an arguer's commitment set." The following is the scheme for *argument from inconsistent commitment*: [^1]

```
'a' is committed to proposition 'A' (generally, or in virtue of what she has said in the past).
'a' is committed to proposition '¬A', which is the conclusion of the argument 'b' that 'a' presently advocates.
Therefore, 'a''s argument 'b' should not be accepted.
```

In the following sequence of dialogue, Ed is faced his old commitments, that is, his past support of the communist cause. The two positions is presented as contradictory. [^1]

```
"You admit you are a communist, and you have always supported communism very strongly in the past. 
 Yet, in this case you are not supporting the union cause? Come on, Ed! You can't have it both ways."
```


```javascript
defeasible_rule(argument_refused(C),[is_commited_to(X,A), is_commited_to(X,B), 
                                     is_opposite_to(A,B), is_conclusion_of(B,C)])[as(AS4IC)].
    cq(cq1, not accepted(C)).
```

### Critical Questions

```
CQ1: What are the propositions alleged to be practically inconsistent, and are they practically inconsistent?
CQ2: If the identified propositions are not practically (pragmatically) inconsistent, as things stand, are there at least
     some grounds for a claim of practical inconsistency that can be evaluated from the textual evidence of the discourse?
CQ3: Even if there is not an explicit practical inconsistency, what is the connection between the pair of propositions 
     alleged to be inconsistent?
CQ4: If there is a practical inconsistency that can be identified as the focus of the attack, how serious a flaw is it?
     Could the apparent conflict be resolved or explained without destroying the consistency of the commitment in the
     dialogue?
CQ5: Does it follow from 'a''s inconsistent commitment that his argument should not be accepted?
CQ6: Is the condusion the weaker claim that 'a''s credibility is open to question or the stronger claim that the conclusion
     of his argument is false?
```

<br><br><br>




## Argument from pragmatic inconsistency

"The pragmatic inconsistency introduces a problem, different from one posed by logical inconsistency, of interpretation of
 actions that the commitments supposedly imply. The opposition is not between commitments following from statements, but 
 between present positions adopted and the implications of past commitments or actions."[^2] The following scheme represents 
 the general form of the *argument from pragmatic inconsistency*:

```
  'a' advocates argument b, wich has proposition A as its conclusion.
  'a' has carried out an action, or set of actions, that imply that 'a' is personally committed to '¬A' 
      (the opposite of negation of A).
  Therefore, a's argument b should not be accepted.
```

### Critical Questions

```
  CQ1: Did 'a' advocate 'b' in a strung way by indicating her personal commitment to 'A'?
  CQ2: In what words was the action described, and does that description imply that 'a' is
       personally committed to the oppositte of 'A'?
  CQ3: Why is the pragmatic inconsistency indicated by satisfactory answers to CQ1 and CQ2
       a relevant reason for not accepting argument 'b'?
```

<br><br><br>






## Argument from double standard

The double standard argument may be considered a subspecies of argument from pragmatic inconsistency. In this argument, there is an alleged incoherence
in the policies adopted with respect to two similar cases: the agent, choosing two incompatible courses of action in two similar situations, is presented
as supporting or defending conflicting commitments. The double standard argument may be classified, for this reason, as a species of argument from pragmatic
inconsistency. [^3] The following is the scheme *argument from doubk standard*:

```
  The respondent has one policy with respect to 'a'.
  The respondent has another (different) policy with respect to 'b'.
  'a' is similar to 'b' (or comparable to 'b' in some relevant respect).
  Therefore, the respondent is using a double standard.
```

### Critical Questions

```
  CQ1: What is the respondent's policy with respect to a?
  CQ2: What is the respondent's policy with respect to b?
  CQ3: How is the one policy different from the other?
  CQ4: How is a similar (or comparable) to b?
  CQ5: Can the differences in policies be explained, or is it significant as evidence 
       that the respondent's policies are not consistent in some important way?
```

[^1]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.136. 2008.
[^2]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.137. 2008.
[^2]: WALTON, D.; REED, C.; MACAGNO, F. Argumentation Schemes. Cambridge University Press. p.139. 2008.
