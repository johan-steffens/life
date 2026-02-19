---
name: evening
description: "Deep daily reflection and journal closure. Use when user says 'end day', 'evening', 'let's reflect', or similar. Focuses on emotional resonance, goal alignment, and building a narrative of the day's events."
---

- **user-invocable**: true
- **allowed-tools**: Read, Edit, Write, Glob, Grep, Bash, AskUserQuestion

# Evening Reflection & Journal Closure

This skill transforms the "end of day" into a deep, emotional, and strategic check-in. It moves beyond a simple task list to understand the *quality* of the day and its alignment with the user's soul and values.

**Workflow:**
1. **Load Context**: Read today's journal, annual goals, and life plan.
2. **Emotional Check-in**: Use `AskUserQuestion` to ask about the prevalent emotion and navigate the day's narrative arc.
3. **Goal & Value Alignment**: Build a conversation that maps the day's events to the annual theme ("Year of Connection") and core values.
4. **"What good have I done?"**: Ask Franklin's closing question, pushing for specifics on integrity and impact.
5. **Soul Check**: Ask how to apply soul goals (patience, compassion) to oneself tonight.
6. **Tomorrow's Resistance**: Identify avoidance for tomorrow and plan around it.
7. **Finalize Journal**: Update the Log and write a narrative Evening Reflection that captures the day's emotional truth.

**Tone:** Empathetic, challenging, and narrative-driven. act as a critical thinking partner who cares about the user's internal state as much as their external output.

**IMPORTANT:** If you feel like the user has a lot on their heart, probe them more. This is supposed to be a reflective process, and if the user is aligning well to it, we should be encouraging to the process. So it's a good thing to deviate from the Workflow above if it means we'll gather more perspective and help the user reflect deeper.

---

## Step 1: Load Context

Read these files in parallel to understand the day's intent:

1. **Today's journal:** `~/Workspaces/docs/life/journal/YYYY/MM/YYYY-MM-DD.md`
2. **Annual goals:** `~/Workspaces/docs/life/journal/YYYY/goals.md`
3. **Life plan:** `~/Workspaces/docs/life/plan.md`

---

## Step 2: The Emotional Check-in

Do not start with "what did you do?" Start with the internal landscape.

**Use AskUserQuestion:** "What was the prevalent emotion you felt today? Looking back at the context of [yesterday's key events/depth], how did you navigate that space today?"

---

## Step 3: Connection & Goal Alignment

Map the day's events to the annual theme (**The Year of Connection**) and core values.

**Use AskUserQuestion** (based on user's emotion/input):
- "Where did you feel most connected (to self, work, or others) today?"
- "Where did you feel resistance or distance?"
- "How did your actions today reflect your core values (Logic-Emotion Equilibrium, Unyielding Integrity, Resistance is Growth)?"

*Example: If the user felt 'despondent', ask how they practiced 'Equilibrium' or 'Self-Compassion' within that state.*

---

## Step 4: The "Good Done" & Impact

Ask Franklin's question, but with a twist: **"What good have I done today?"** 

Push for specifics on integrity and impact:
- Did it empower others or enable growth?
- Was it an act of integrity or facing a difficult duty?
- Did it involve "facing the difficult" (Resistance is Growth)?

---

## Step 5: Soul & Self-Compassion

Reference the **Soul & Spirit** goals (e.g., "Practice patience and compassion"). 

**Ask:** "How can you apply soul goals like patience and compassion to yourself tonight? What does your 'higher self' need to hear or do before sleep?"

---

## Step 6: Tomorrow's Resistance

Identify avoidance for tomorrow and plan around it.

**Ask:** "Is there anything you're avoiding for tomorrow? How can we plan around that resistance now to protect your peace and ensure your morning routine (run, office visit) succeeds?"

---

## Step 7: Finalize Journal

Update the Log and write a narrative Evening Reflection that captures the day's emotional truth.

1. **Update Log:** Ensure all meaningful events mentioned in the conversation are timestamped or logged.
2. **Evening Reflection:** Write a 1-2 paragraph reflection that connects the day's events to your emotional arc, values, and the "Year of Connection".
3. **Task Clean-up:** Mark completed items. Carry over or cancel tasks based on the conversation.

---

## Step 8: Final Perspective

End with a short, supportive closing. If the day was hard, acknowledge the integrity in surviving it and maintaining your compass.
