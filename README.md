# Creative Brief

**A Claude skill that grades, pressure-tests, and writes creative briefs and social hooks against a real strategic standard, not a template.**

Most briefs are complete and lifeless. Every field filled, and nothing that moves the person who has to make the work. This skill makes Claude read a brief the way a senior creative strategist would: it reframes the problem, catches an observation pretending to be an insight, finds the tension, and hands back the hard questions the brief can't answer yet. Then it does the same for social hooks.

It is not a "write me a brief" prompt. The whole point is the standard underneath it.

---

## See the difference

A normal, complete-looking brief:

```
Objective:  Increase awareness and sign-ups for our language app
Audience:   Adults 25–45 who want to learn a language
Insight:    People are busy and want a convenient way to learn
Message:    Learning a language has never been easier or more fun
```

The same brief, run through the skill:

```
Verdict: Not yet a brief.

THE REAL PROBLEM
It assumes people don't know the app exists. They do. Almost everyone in
this audience has already started a language and quit. The real problem is
the shame of the abandoned attempt, not awareness.

INSIGHT — missing
"People are busy and want convenience" is an observation. No tension, and
every competitor already says it. The turn it's missing: people think they
quit because they ran out of time. Actually they quit the moment the app
made them feel like a beginner with nothing to show for it.

QUESTIONS IT CAN'T ANSWER YET
• Who specifically, and what made them quit last time?
• What does this push against — the streak-shaming the whole category does?
• What is the one thing we want them to think, feel, or do?

FIX ONE THING
Stop briefing awareness. Brief the shame of the quit attempt, and the relief
of the first real conversation.
```

Same idea on a social hook. From the template the model writes on autopilot, to one engineered to fire a real driver:

```
Before:  "Learn a language fast with our app!"
After:   "You've started Spanish four times. Here's why week two always wins."
         (callout + hard truth → fires self-recognition and curiosity)
```

---

## What it does

Two actions, two layers, one engine.

- **Grade** — paste a brief or a set of hooks and get a real critique: a verdict, a problem reframe, a score against the standard, and the questions it still owes. Graded "Strong" is rare on purpose.
- **Build** — stuck at a blank page? It interviews you toward a brief, pushing on weak answers instead of handing you a template to fill in.
- **Social layer** — the same engine for short-form video, UGC, and performance creative. Funnel-aware hook matrices, where the hook is treated as a tension resolved in the first three seconds, plus the seed, and the visual / text / sound delivery most briefs forget.

---

## Install

**Claude Code:** clone this repo into your skills directory.

```bash
git clone https://github.com/efesorjm/creative-brief.git ~/.claude/skills/creative-brief
```

**Claude apps:** download `creative-brief.skill` from the latest [release](../../releases) and add it from the skills menu.

Skill install paths change as the product evolves. If a menu has moved, check the current [Anthropic skills docs](https://docs.claude.com).

---

## Use it

Once installed, just talk to Claude. The skill triggers on its own.

- "Is this brief any good?" *(paste the brief)*
- "Grade these three hooks for a cold TikTok audience."
- "Help me write a brief for our Q3 launch, I don't know where to start."
- "Write a hook matrix for retargeting people who looked at the bundle."

It will reframe, score, interrogate, and push. That is the job.

---

## What's inside

The skill is a lean router plus four focused files Claude reads only when needed:

- **`SKILL.md`** — the modes, the routing, and the bar.
- **`references/standard.md`** — the IIOB standard (Idea, Insight, Objective, Benefit), the four moves that separate a brief that moves from one that informs, and a worked teardown.
- **`references/social.md`** — the social layer: how a social brief differs, the funnel-position rule, the hook matrix, and the Five A's.
- **`references/hooks.md`** — the craft of hooks: the drivers that actually stop a scroll, a mechanism palette, a writing method, and a grading rubric. Distilled from a thousand viral hooks, with the templates thrown away and the judgment kept.

The standard is opinionated, because a standard that isn't has nothing to enforce.

---

## Why it exists

Random creativity is expensive luck. A great idea with no system behind it is a coin flip you paid for. This skill is one piece of a system: the part that makes sure the thinking is good before anyone spends weeks, or a budget, building on top of it.

It comes out of fifteen years leading brand and creative teams, and a simple belief: the work that survives the age of infinite AI output is the judgment about what is worth making. The model does the volume. A human holds the gate. This is the gate, written down.

More on the thinking behind it: [portfolio-link]

---

## License

MIT. Use it, fork it, build on it.

If it makes your briefs sharper, a star helps other people find it.
