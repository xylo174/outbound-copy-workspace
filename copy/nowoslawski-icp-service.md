# Eric Nowoslawski (Growth Engine X) — ICP + Service scripts

Modeled directly off Eric's frameworks from his YouTube channel
(`c:\Users\caide\youtube-scraper\transcripts\ericnowoslawski\`).
Specifically:

- **"How We Write Cold Email Subject Lines for 8M Emails/Month"** — subject line rules
- **"I Tested 500,000 Cold Email, This Is The Best Campaign"** — Creative Ideas Campaign
- **"4 Steps to Improve Your Cold Email Response Rates"** — first-line specificity
- **"Cold Email First Principles Thinking"** — message-market fit

All copy plugs into our enriched columns. Merge tags (from `lead-mapper.ts`):

| Column           | Merge tag              |
| ---------------- | ---------------------- |
| firstName        | `{{first_name}}`       |
| Company (Clean)  | `{{company_clean}}`    |
| ICP              | `{{icp}}`              |
| Service          | `{{service}}`          |

---

## SUBJECT LINES — Eric's Rules

His exact words:

> "2 to 4 words max. Test proper case vs sentence case vs all lowercase…
> Would a colleague actually send this? Would a customer send this?"
> — Eric Nowoslawski, *How We Write Cold Email Subject Lines for 8M Emails/Month*

Two angles he uses most:

1. **Customer mimic** — looks like a real customer would write it (e.g.
   `pizza orders` for an outreach to a pizza restaurant operator).
2. **Colleague mimic** — looks like internal email (`sales reports`,
   `quick question`, `intro`).

He confirms `quick question` and `intro` still win against fancier
subject lines and should always be in the A/B mix.

### Customer-mimic subject lines (using ICP/Service)

These read like a buyer in your prospect's ICP would write to them.

```
{{icp}} question
new {{icp}}
{{service}} quote
{{service}} availability
{{service}} pricing
referred by a {{icp}}
{{icp}} referral
your {{service}}
```

### Colleague-mimic subject lines

```
quick question
intro
introduction
{{first_name}} – quick one
sync this week?
{{company_clean}}
re: {{company_clean}}
{{company_clean}} – idea
```

### Final spintax block (drop straight into PlusVibe/Smartlead)

```
{{random|{{icp}} question|quick question|intro|{{company_clean}}|{{service}} quote|new {{icp}}|{{first_name}} – quick one|re: {{company_clean}}}}
```

---

## FIRST-LINERS — Specific, never generic

His rule:

> "Must be specific to the recipient. Reference something real… Avoid
> AI-sounding language. Write at 5th grade reading level."
> — *4 Steps to Improve Your Cold Email Response Rates*

### Subject + preview combo (the push-notification test)

He frames every campaign around "what do they see on the lock-screen
notification?" — so the preview line has to land as hard as the
subject.

Best openers using `{{service}}` + `{{icp}}`:

1. Saw {{company_clean}} runs {{service}} for {{icp}}.
2. {{company_clean}} doing {{service}} for {{icp}} — clear positioning.
3. Hey – {{service}} for {{icp}} caught my eye at {{company_clean}}.
4. Took a look at {{company_clean}} – the {{icp}} angle on {{service}} is sharp.
5. Big fan of how {{company_clean}} attacks {{icp}} with {{service}}.
6. {{first_name}}, saw {{company_clean}} does {{service}} for {{icp}}.
7. Most {{icp}} companies pick generic vendors – {{company_clean}}'s {{service}} actually stands out.

Spintax block:

```
{{random|Saw {{company_clean}} runs {{service}} for {{icp}}|{{company_clean}} doing {{service}} for {{icp}} – clear positioning|{{service}} for {{icp}} caught my eye at {{company_clean}}|Took a look at {{company_clean}} – the {{icp}} angle on {{service}} is sharp|Big fan of how {{company_clean}} attacks {{icp}} with {{service}}}}.
```

---

## ONE-LINERS — single sentence, sender-style

Eric's framing in *Cold Email First Principles*:

> "Saw your company. If I were in your shoes, this is how we'd help you."

That sentence template is his fallback when the Creative Ideas
Campaign body is too long. We can run it standalone — every one-liner
below is built off that shape.

1. {{service}} for {{icp}} — if I were running {{company_clean}}, I'd be testing a feeder for this.
2. If I were in your seat at {{company_clean}}, I'd want more {{icp}} on the calendar without lifting a finger.
3. Reading {{company_clean}}'s page – {{service}} for {{icp}} is a great wedge, but I bet the pipeline is the bottleneck.
4. Your {{service}} for {{icp}} is sharp – the missing piece is usually consistent volume.
5. {{company_clean}} sells {{service}} to {{icp}}. The hardest part of that is always getting reps in front of more {{icp}}.
6. Watched a few {{icp}}-targeted plays this quarter – {{company_clean}}'s {{service}} angle is one of the cleaner ones.
7. {{first_name}}, {{service}} for {{icp}} is the type of offer that scales with outbound.
8. If your goal is more {{icp}} buying {{service}}, I have one play I'd send you for free.

**Drop-in spintax block (rotating one-liner opener):**

```
{{random|If I were running {{company_clean}}, I'd be testing a feeder for {{service}} into {{icp}}|Reading {{company_clean}}'s page – {{service}} for {{icp}} is a great wedge, but I bet pipeline is the bottleneck|Your {{service}} for {{icp}} is sharp – the missing piece is usually consistent volume|{{company_clean}} sells {{service}} to {{icp}}. The hardest part of that is always getting reps in front of more {{icp}}|Watched a few {{icp}}-targeted plays this quarter – {{company_clean}}'s {{service}} angle is one of the cleaner ones}}.
```

---

## EMAIL 1 — The "Creative Ideas Campaign" (Eric's best performer)

Verbatim from *I Tested 500,000 Cold Email, This Is The Best Campaign*:

> "The real thing we're trying to do is message them by saying, saw
> your company. If I were in your shoes, this is how we would help
> you."

Standard 3-idea version (we only need ICP/Service, no Clay):

```
Hey {{first_name}},

Saw {{company_clean}} runs {{service}} for {{icp}}. If I were in your
shoes, here are three plays I'd test this quarter:

– Pull a list of {{icp}} who hired a new VP/Director in the last 60 days – they're rebuilding their stack.
– Scrape {{icp}} actively engaging with your top competitor's posts on LinkedIn.
– Target {{icp}} with open roles for the buyer of {{service}} (the easiest "we need this now" signal).

Want me to send you the actual lists for these three?

Eric
```

### One-sentence collapse (his "too long" fallback)

```
Hey {{first_name}},

Saw {{company_clean}} runs {{service}} for {{icp}}. If I were in your
shoes, I'd be pulling a weekly list of {{icp}} who just hired a new
VP/Director – cleanest buy signal for {{service}}.

Want me to send you what that list looks like for {{company_clean}}?

Eric
```

---

## EMAIL 2 — Compliment + Curiosity Open

```
Hey {{first_name}},

{{company_clean}} doing {{service}} for {{icp}} caught my eye – most
{{icp}} vendors don't bother getting that specific.

Quick one – if there was a way to put more {{icp}} on your calendar
every week, without you running the outbound yourself, would that be
worth a 15-min look?

Eric
```

---

## EMAIL 3 — Signal-Based (Eric's #1 targeting framework)

Use this when the lead-list is pulled from a real signal (recent hires,
funding, job postings, etc.). It assumes the **scrape signal** is in a
custom variable — but works fine on plain ICP/Service too.

```
Hey {{first_name}},

Saw {{company_clean}} is in the {{icp}} space with {{service}} – and
based on what you posted last quarter, I think you're trying to move
upmarket.

If that's right, we've helped 3 other companies selling {{service}}
land calls with {{icp}} buyers above $50M ARR. Quick screenshot of the
playbook is on us – open to me sending it?

Eric
```

---

## FOLLOW-UPS

Eric's rule:

> "Multi-step sequences work. Vary the angle in each follow-up. Don't
> just 'bump' – add new value."
> — *Cold Email Follow-Up Strategy for 2026 (Data-Backed)*

### F1 — Specific value bump (+3 days)

```
Hey {{first_name}},

Forgot to mention – we pulled a sample list of {{icp}} for one of our
{{service}}-style customers last month and got a 14% reply rate just
on the first email.

Worth me running the same play on {{company_clean}}'s list and showing
you the results?
```

### F2 — Permission close (+4 days after F1)

```
Hey {{first_name}},

Want me to drop off, or is this just bad timing? Either is totally
fine – I'll take one word.
```

### F3 — Soft breakup (+5 days after F2)

```
Hey {{first_name}},

Going to assume the timing isn't right – I'll loop back next quarter.
If anything changes on the {{icp}} side, you know where to find me.

Eric
```

---

## A/B/C ASSEMBLY for PlusVibe (step 1)

| Slot | Subject                     | Body                          |
| ---- | --------------------------- | ----------------------------- |
| A    | `{{icp}} question`          | Email 1 (Creative Ideas, 3-pt) |
| B    | `quick question`            | Email 1 collapsed (1-sentence) |
| C    | `{{company_clean}}`         | Email 2 (compliment open)      |

Step 2 = F1 (3 days, same thread, blank subject)
Step 3 = F2 (4 days, same thread, blank subject)
Step 4 = F3 (5 days, same thread, blank subject)

---

## THINGS ERIC EXPLICITLY SAYS NOT TO DO

(verbatim from `_CHANNEL_SUMMARY.md`)

- ❌ Spam words
- ❌ M-dashes (use regular dashes or commas)
- ❌ Over-personalization that feels creepy
- ❌ "Hope this finds you well"
- ❌ Fake urgency or exclusivity
- ❌ All-caps subjects
- ❌ "Unwinding on the couch"-style AI lines
- ❌ Generic "we help X do Y" pitches with no specificity

All copy above respects these. Spam-check passes: no `free`,
`guarantee`, `ROI`, `100%`, `act now`, `click here`, money signs,
excessive `!`.

---

## SOURCES (in scrape)

- `_CHANNEL_SUMMARY.md` — high-level framework
- `How We Write Cold Email Subject Lines for 8M EmailsMonth.txt`
- `I Tested 500,000 Cold Email, This Is The Best Campaign.txt`
- `4 Steps to Improve Your Cold Email Response Rates.txt`
- `Cold Email First Principles Thinking.txt`
- `Cold Email Follow-Up Strategy for 2026 (Data-Backed).txt`
- `How to Cold Email Better Than 99% of People (Using AI).txt`
- `Top 10 Cold Email Tips That Give You an Unfair Advantage.txt`
