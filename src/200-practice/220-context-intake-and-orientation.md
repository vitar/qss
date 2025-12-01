# Context Intake and Orientation

Before you design a question space, you need a **sharp picture of the situation**.

Context intake is how you:

- avoid asking clever questions about the wrong thing,
- choose a sane Mode (Setup, Stabilization, Growth),
- and set guardrails for power, safety, and scope.

This chapter gives you a **minimal, reusable intake spine** and shows how to turn it into Orientation.  
It assumes you already skimmed the Theory section; here we stay practical.

## Why context intake matters

If you skip intake, you risk:

- addressing symptoms instead of patterns,
- pulling people into unsafe territory,
- treating structural problems as personal failings,
- or, in the worst case, doing harm by interrogating someone with low power.

A small amount of intake:

- protects participants,
- keeps QSS honest about its limits,
- and makes later design choices (topology, flow, recursion) easier.

You do not need a giant questionnaire. You need a **clear enough picture**.

## A minimal intake spine

You can think of intake as five questions:

1. What is happening, and where?  
2. Who is involved, and how is power distributed?  
3. How safe is it to talk honestly here, and what is out of scope?  
4. What do we want from this space (cognitive + relational)?  
5. What constraints and format are we working with?

We’ll walk these as **Step 1–5**, then show how to convert them into Orientation.

Along the way, there is one small but important “executable” guardrail:  
a **Safety Check** that tells you when not to use direct interrogation patterns.

## Step 1 – Situation snapshot

Goal: get a compact description of what is going on **right now**.

Prompt yourself (or the requester):

- “In one or two sentences, what is happening?”
- “Is this about:
  - starting something new,
  - fixing something that is slipping,
  - or improving something that basically works?”

Capture:

- Domain:
  - work, consulting, internal team, personal, creative.
- Object:
  - project, relationship, decision, pattern, event.
- Temperature:
  - calm, tense, crisis-adjacent.

Mode hint:

- If it is mostly about **starting or framing** → lean Setup.
- If it is mostly about **slip, tension, or escalation** → lean Stabilization.
- If it is mostly about **improvement, direction, or learning** → lean Growth.

You can adjust Mode later, but pick a starting guess.

## Step 2 – Stakeholders and power

Goal: understand **who is in the system** and **how power and risk are distributed**.

Ask:

- “Who is in the room (or in the conversation)?”
- “Who is not in the room but strongly affected?”
- “Who has more formal authority here?”
- “Who carries more risk if things go badly?”
- “Is participation voluntary for everyone?”

You can quickly label power asymmetry on a rough scale:

- Power Asymmetry:
  - Low:
    - peers, similar risk.
  - Medium:
    - some hierarchy, but relatively safe to disagree.
  - High:
    - strong hierarchy, job/contract/grade risk for some participants.

Note:

- High asymmetry is not automatically bad; it just changes which questions are safe.
- Ignoring asymmetry is what causes harm.

## Step 3 – Safety and scope

Goal: define **how safe it is to speak honestly** and **what this space is not allowed to hold**.

Ask:

- “How safe does it feel (for each participant) to:
  - disagree,
  - say ‘I don’t know’,
  - name problems that involve higher power people?”
- “Has anyone been punished directly or indirectly for speaking up in similar situations?”
- “Are there topics that are clearly too sensitive for this format?”
  - clinical/mental health,
  - legal disputes,
  - HR-sensitive incidents,
  - abuse/harassment.

Roughly rate **felt safety**:

- Safety:
  - High:
    - people routinely disagree without punishment;
      someone in power is explicitly protecting the space.
  - Medium:
    - people are cautious but can speak, with some hesitation.
  - Low:
    - visible fear, history of negative consequences, or clear reason not to trust.

### Safety Check (executable rule)

To make this usable for novices or AI, turn the above into a simple check:

```text
Power Asymmetry:  Low / Medium / High
Safety:           Low / Medium / High

Safety Check = (Power Asymmetry == High) AND (Safety == Low)
```

If **Safety Check = true**:

* Treat this as a **WARNING** state:

  * Do **not** use:

    * direct interrogation patterns,
    * questions that single out lower-power individuals in front of higher-power ones,
    * emotionally deep prompts directed at the least powerful person.
* Prefer:

  * system-level questions

    * (“What in our setup makes this hard?” instead of “Why are you not speaking up?”),
  * anonymous or 1:1 inputs for sensitive content,
  * written or async formats where appropriate,
  * or, if stakes are high, **not running the space at all** until safety improves.

This check is deliberately simple:

* It doesn’t solve power or safety.
* It prevents obvious misuses of QSS in contexts where it can do harm.

### Scope boundaries

Explicitly mark what is out of scope:

* “This space will not:

  * give legal advice,
  * diagnose health conditions,
  * replace therapy,
  * or handle acute crisis or abuse cases.”

If any of those are present:

* acknowledge them,
* and consider pausing or redirecting:

  * “This sounds heavier than what this conversation is designed to hold.
    It might be better to talk to [HR / doctor / therapist / lawyer / trusted person] about that part.”

## Step 4 – Intent (cognitive and relational)

Goal: define **why** you are opening this space.

Ask:

* “If this conversation went well, what would be different afterwards?”
* “What do we want to understand, decide, or map?”
* “What do we want the emotional/relational tone to be?”

Capture:

* Cognitive goals:

  * examples:

    * shared picture of the problem,
    * agreed trade-offs,
    * identified patterns, not just incidents,
    * clearer decision criteria.
* Relational goals:

  * examples:

    * preserve working relationship,
    * restore predictability,
    * give people a way to be heard,
    * reduce fear, not increase it.

This is where you apply your **personal sense of intention**:

* “Why am I asking these questions at all?”
* “Am I trying to help, to explore, or to win?”

If the intent feels off (for example, “prove they’re wrong”), pause and reconsider.

## Step 5 – Constraints and format

Goal: respect real-world limits.

Ask:

* “How much time do we actually have?”
* “How many people will be involved?”
* “Is this:

  * live,
  * async,
  * written,
  * recorded?”
* “Can people decline to answer or step out?”

Capture:

* Timebox:

  * 15 min, 30 min, 60 min, multi-session.
* Format:

  * 1:1, small group, big group, email, survey, async notes.
* Recording:

  * whether notes or recordings will exist,
  * who sees them.

Constraints help you **right-size** the space:

* You can’t run a deep Growth-mode redesign in a 15-minute escalation slot.
* You can, however, do:

  * a short Stabilization step,
  * and design deeper follow-ups later.

## Turning intake into Orientation

Once you have Steps 1–5, you can synthesize Orientation in one sentence:

> “In this [Mode] situation, with [power picture and safety level],
> I want this space to help [cognitive goals] in a way that feels [relational goals],
> within [time/format], while staying within scope (no [out-of-scope areas]).”

Example – client–vendor reset:

> “In this Stabilization situation, with the client holding commercial power and the vendor under delivery pressure,
> I want this space to help us see how we drifted and agree on one or two stabilizing changes,
> in a way that is honest but non-blaming,
> within a 60-minute joint call, staying within work context (no legal renegotiation, no therapy).”

Example – personal role reflection:

> “In this Growth-ish personal situation, where I’m considering staying, shifting, or leaving my current role,
> I want this space to help me see how this path fits my values, energy, and plausible futures,
> in a way that is honest and kind to myself,
> within a 45-minute written reflection, staying within work/career and not trying to solve my entire life story.”

Orientation is your **compass**:

* it guides topology selection,
* shapes flow,
* and grounds recursion:

  * when you review later, you can ask:

    * “Did this space actually serve its Orientation?”

## Short intake forms for common contexts

You can keep micro-templates for recurring domains.

### Client / consulting context

* What is happening?
* Mode guess:

  * Setup / Stabilization / Growth.
* Who is in/out of the room?
* Power asymmetry:

  * Low / Medium / High.
* Safety:

  * Low / Medium / High.
* Safety Check:

  * true / false.
* What outcome would make this conversation valuable for:

  * the client,
  * you,
  * the relationship?
* Timebox and format:

  * 30–60 min, remote/in-person.
* Out of scope:

  * legal renegotiation, contract drafting, HR incidents, clinical topics.

### Internal team / leadership context

* Situation in one sentence.
* Mode:

  * Setup / Stabilization / Growth.
* Who is here?

  * manager? ICs? cross-team?
* Power asymmetry:

  * Low / Medium / High.
* Safety:

  * Low / Medium / High.
* Safety Check:

  * true / false.
* What do we want:

  * cognitively,
  * relationally?
* Constraints:

  * weekly slot vs one-off,
  * recording yes/no.

### Personal reflection

* What am I reflecting on?
* Why now?
* Mode:

  * mostly Setup, Stabilization, or Growth?
* Who else is affected?
* Emotional state:

  * calm / tense / overwhelmed.
* Any red flags:

  * health, harm, legal, abuse?
* What do I want by the end:

  * clarity, options, one small step?

Even when working solo, you can apply a **light Safety Check**:

* “Is what I’m touching here too heavy to handle alone with questions?”
* “Should my next step be:

  * journaling,
  * talking to someone I trust,
  * or professional help?”

The more you reuse these small intake patterns, the more natural Orientation becomes.
Designing question spaces then feels less like improvisation and more like using a **reliable scaffolding** that still leaves room for your judgment and style.
