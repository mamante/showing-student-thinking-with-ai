# Showing Student Thinking with AI
## Gemini diagnostic prompts · NYSCATE 2026

These prompts match the classroom workflow **Collect → Investigate → Verify → Respond**. They help a teacher investigate patterns in observable reasoning; they are not grading rubrics or AI-detection tests.

Use only district-approved tools, de-identify classroom work before sharing, and verify suggestions against the original evidence. Evidence bands describe responses, not student ability.

### 1. Class-set diagnostic
Group comparable explanations into provisional reasoning bands.

```text
You are my instructional diagnostic partner, not a grader. I am providing anonymized explanations to the SAME coding question, with relevant code excerpts.

1. Quote exact evidence that supports each pattern.
2. Group responses into provisional bands: OUTCOME DESCRIBED, PROCESS DESCRIBED, or MECHANISM EXPLAINED. Do not label students or assign scores.
3. Note exceptions, unclear cases, and missing evidence.
4. Suggest one 5-minute instructional response for each recurring pattern and one follow-up question to test it.

Do not invent frequencies, treat a band as an ability level, or claim mastery.

[Paste anonymized class-set excerpts here.]
```

### 2. Probe the mechanism
Check whether students can explain why a fix works.

```text
Review the following anonymized coding explanation alongside its relevant code. Separate what the student changed from why that change affects behavior. Quote only visible evidence.

Propose one prediction question and one causal why-question about the mechanism. Explain what each answer could clarify, and note what remains uncertain.

Do not grade the student or assume a working program proves understanding.

[Paste code and explanation.]
```

### 3. Test an edge case
Identify a boundary condition that can challenge an assumption.

```text
Inspect this program without changing or executing it. Suggest five tests appropriate to the code: normal input, boundary input, blank input, invalid input, and canceled/missing input (if relevant).

Predict behavior only from visible code, clearly label unexecuted predictions, and propose one follow-up question about the most revealing case.

[Paste relevant code.]
```

### 4. Compare two designs
Find tradeoffs without declaring one student the winner.

```text
Compare these two anonymized implementations of the same programming task. Quote specific lines that show similarities or differences. Identify the design tradeoffs (for example, error messages in a graphics window versus the console).

Generate one question for each approach that investigates the design decision. Note incomplete code and alternative explanations. Do not rank the students.

[Paste two solutions and task requirements.]
```

### 5. Plan tomorrow’s instruction
Turn verified response patterns into an actionable teaching move.

```text
I have verified the following patterns across comparable student explanations. Use these patterns to suggest a short next-lesson plan.

For each pattern, provide: (1) a 5-minute reteach, trace, or extension; (2) one question that checks understanding; and (3) what evidence I should collect to determine whether the next step worked.

Treat the patterns as provisional evidence, not student ability labels. Do not assign grades.

[Paste VERIFIED pattern summary.]
```

### 6. Transfer to my subject
Keep the assignment and add a short reasoning checkpoint.

```text
I teach [subject / grade]. Students complete [existing assignment]. The current final product is [deliverable].

Suggest one two-minute checkpoint that captures a prediction, process, justification, test, or revision reason. Propose one prompt for investigating patterns across anonymized responses, and one teacher follow-up to verify the interpretation.

Keep the original assignment and avoid adding a long reflection or grading burden.
```

### Teacher verification checklist
- Does the analysis quote the original evidence accurately?
- Are **Outcome described**, **Process described**, and **Mechanism explained** applied to observable explanations only?
- Are exceptions and uncertainties acknowledged?
- What specific instruction and follow-up question would confirm the interpretation?
- No student work or presentation slides are included in this public resource packet.