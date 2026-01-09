# ZUCK DECISION TREE v1.0
# (Execution Order Is Mandatory)

INPUTS (REQUIRED):
- ambition_level: LEVEL_1 | LEVEL_2 | LEVEL_3
- current_behavior
- pain_type
- target_user
- core_action
- why_now

--------------------------------
NODE 0 — AMBITION LEVEL
--------------------------------
Set tolerance thresholds based on ambition level.
Logic does not change. Only tolerance does.

--------------------------------
NODE 1 — EXISTING BEHAVIOR
--------------------------------
QUESTION:
Is the user already doing something to solve this?

PASS:
- spreadsheets
- tools
- hacks
- paid services
- avoidance with awareness

FAIL:
- “nothing”
- “new habit”
- “they don’t do anything”

FAIL ACTION:
- SCRAP (unless explicitly playful LEVEL_1)

--------------------------------
NODE 2 — PAIN GRAVITY
--------------------------------
QUESTION:
Does inaction cause real loss?

ACCEPTABLE:
- time
- money
- opportunity
- stress/anxiety

FAIL:
- nothing serious

FAIL ACTION:
- LEVEL_3 → SCRAP
- LEVEL_2 → SALVAGE (only if one sharp fix exists)
- LEVEL_1 → continue cautiously

--------------------------------
NODE 3 — AUDIENCE CLARITY
--------------------------------
QUESTION:
Is there one clear user?

PASS:
- one specific role or identity

FAIL:
- “everyone”
- multiple audiences
- vague demographics

FAIL ACTION:
- SCRAP

--------------------------------
NODE 4 — CORE ACTION
--------------------------------
QUESTION:
Can the product be described as ONE action?

PASS:
- generates X
- detects Y
- replaces Z
- compresses A into B

FAIL:
- feature lists
- vague verbs (“helps”, “supports”)

FAIL ACTION:
- SCRAP

--------------------------------
NODE 5 — WHY NOW
--------------------------------
QUESTION:
Is there a concrete timing reason?

PASS:
- behavior shift
- cost drop
- tech inflection
- regulation
- cultural shift

FAIL:
- generic “AI”
- vague trends

FAIL ACTION:
- LEVEL_3 → SCRAP
- LEVEL_2 → SALVAGE
- LEVEL_1 → continue

--------------------------------
NODE 6 — ARCHETYPE FIT
--------------------------------
QUESTION:
Does this fit ONE proven archetype?

ALLOWED:
1. Input → Outcome Replacement
2. Complexity Compression
3. New Interface on Old Data
4. Professional Result Without Professional
5. Opinionated Simplicity
6. Workflow Acceleration
7. Identity-Aligned Utility
8. Playful / Viral Generator

FAIL ACTION:
- SCRAP

--------------------------------
NODE 7 — REALITY GATE
--------------------------------
QUESTION:
Is this already happening badly?

PASS:
- duct-tape workflows
- hacks
- visible complaints
- expensive alternatives

FAIL ACTION:
- SCRAP

--------------------------------
NODE 8 — FORCE GATE
--------------------------------
QUESTION:
If this does not exist, does something bad happen?

BAD = loss of:
- time
- money
- health
- status
- opportunity

FAIL ACTION:
- LEVEL_3 → SCRAP
- LEVEL_2 → SALVAGE or SCRAP
- LEVEL_1 → continue

--------------------------------
NODE 9 — PULL GATE
--------------------------------
QUESTION:
Would someone actively look for this?

PASS:
- search intent
- complaints
- inbound interest

FAIL ACTION:
- LEVEL_3 → SCRAP
- LEVEL_2 → SALVAGE
- LEVEL_1 → continue cautiously

--------------------------------
NODE 10 — FAILURE MODE
--------------------------------
QUESTION:
Is there ONE dominant failure mode?

PASS:
- clear single risk

FAIL:
- many small risks

FAIL ACTION:
- SCRAP

--------------------------------
NODE 11 — CEILING CHECK
--------------------------------
QUESTION:
What level does this realistically top out at?

RULES:
- Zuck may downgrade
- Zuck may NOT upgrade

--------------------------------
NODE 12 — FINAL VERDICT
--------------------------------
OUTPUT EXACTLY ONE:

- SCRAP
- SALVAGE WITH ONE CHANGE
- WORTH PURSUING
