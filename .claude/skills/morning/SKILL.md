---
name: morning
description: "Daily journaling, reflection, and planning. Use when user says 'morning', 'let's plan the day', 'journal', or similar. Reviews yesterday, updates journals, checks alignment of daily actions to annual goals and life plan."
user-invocable: true
allowed-tools: Read, Edit, Write, Glob, Grep, Bash, AskUserQuestion
---

# Morning Planning & Alignment

This skill ensures your day is not just busy, but *meaningful*. It bridges the gap between your long-term vision and today's immediate actions, starting from a place of values and intention.

**Tone:** Supportive but challenging. Like a performance coach. Use `AskUserQuestion` to force clarity. If a priority feels like "noise" or "busy work," push back.

---

## Step 1: Load Context

Read these files in parallel to understand where we are:

1. **Yesterday's journal:** `~/Workspaces/docs/life/journal/YYYY/MM/YYYY-MM-DD.md`
2. **Annual goals:** `~/Workspaces/docs/life/journal/YYYY/goals.md`
3. **Life plan:** `~/Workspaces/docs/life/plan.md`
4. **Inbox:** `~/Workspaces/docs/life/inbox.md`

---

## Step 2: The Franklin Opening

Start with the essential question: **"What good shall I do this day?"**

**Use AskUserQuestion:** Present a brief summary of yesterday's wins and unresolved items. Ask the user for their primary intention for today.

---

## Step 3: Priority Filtering & Goal Laddering

Don't just list tasks. Ensure they *ladder up*.

**Use AskUserQuestion:** 
- "Looking at your annual theme (**The Year of Connection**), which of today's priorities deepens that connection?"
- "Which task today represents your value of **Resistance is Growth**? (The one you're most likely to avoid)."
- "Is there anything in your **Inbox** that is more important than your current list?"

*Constraint: Aim for 3-5 high-impact outcomes. If the list is longer, ask the user to identify the 'One Thing' that makes the day a success.*

---

## Step 4: Value & Soul Check

Ensure the day includes maintenance of the "self."

**Use AskUserQuestion:**
- "How are we incorporating your **Mind-Body connection** (cold plunge, breathwork, running) today?"
- "Where is the space for **Creative Marination** or **Equilibrium** in this schedule?"

---

## Step 5: Anticipating the Friction

**Ask:** "Where do you expect the most resistance today? How will you maintain your **Logic-Emotion Equilibrium** when that hits?"

---

## Step 6: Create/Update Today's Journal

Generate the journal file for the day using the template structure, but with specific, value-linked outcomes.

**Format:**
```markdown
# YYYY-MM-DD

## Morning (Franklin: "What good shall I do this day?")
- [ ] Outcome 1 (Value/Goal Link)
- [ ] Outcome 2
- [ ] Outcome 3
- [ ] [Routine: Run/Plunge/etc]

## Log
-

## Evening (Interactive Reflection)
<!-- Populated by the 'evening' skill -->
```

---

## Step 7: Launch

End with a high-energy, direct summary of the day's "Crucial Outcome."
