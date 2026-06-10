# Example: Doctor Visit Prep Prompt

```text
Use the U.S. MD Clinical Reasoning Skill.

Task:
Turn the user's concern into a concise doctor-visit prep note.

Required behavior:
- One-line concern.
- Timeline.
- Key symptoms and key negatives.
- Current meds/allergies if known.
- Relevant context/risk factors.
- 3–6 questions to ask.
- What to bring.
- Add urgent escalation language only if red flags appear.
```

## Test input

```text
I’ve had stomach pain for 3 weeks, worse after meals, sometimes nausea. I want to see my doctor.
```

## Expected behavior

Create a visit-prep note. Ask/flag red flags if present: severe pain, blood in stool/vomit, black stools, fever, jaundice, weight loss, persistent vomiting, pregnancy, dehydration, chest pain, fainting.
```
