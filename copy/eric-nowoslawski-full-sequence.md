# Eric Nowoslawski — full sequence (paste-ready)

From `nowoslawski-icp-service.md` (Growth Engine X). **Follow-ups:** vary the angle, add value, no empty bumps (*Cold Email Follow-Up Strategy for 2026*).

**Merge tags:** `{{first_name}}`, `{{company_clean}}`, `{{icp}}`, `{{service}}`, `{{sender_first_name}}`, `{{sender_last_name}}`  
**Sign-off:** swapped from “Eric” in the source to your **Node Partners** block (same merge pattern as your other templates).

**Suggested waits (from the doc’s assembly table):** after the first send, **+3 days** → F1, **+4 days** → F2, **+5 days** → F3. Set the same in PlusVibe / Smartlead step delays.

---

## Step 1 — subject pool (Eric, 2–4 words)

Use one subject per variant; or one block:

```
{{random|{{icp}} question|quick question|intro|{{company_clean}}|{{service}} quote|new {{icp}}|{{first_name}} – quick one|re: {{company_clean}}}}
```

### Variant A — Email 1 (Creative Ideas, 3 plays)

**Body**

```
{{first_name}},

Saw {{company_clean}} runs {{service}} for {{icp}}. If I were in your
shoes, here are three plays I'd test this quarter:

– Pull a list of {{icp}} who hired a new VP/Director in the last 60 days – they're rebuilding their stack.
– Scrape {{icp}} actively engaging with your top competitor's posts on LinkedIn.
– Target {{icp}} with open roles for the buyer of {{service}} (the easiest "we need this now" signal).

Want me to send you the actual lists for these three?

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

**Subject (if not using the big random line above):** `{{icp}} question`

---

### Variant B — Email 1 collapsed (“too long” fallback)

**Body**

```
{{first_name}},

Saw {{company_clean}} runs {{service}} for {{icp}}. If I were in your
shoes, I'd be pulling a weekly list of {{icp}} who just hired a new
VP/Director – cleanest buy signal for {{service}}.

Want me to send you what that list looks like for {{company_clean}}?

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

**Subject:** `quick question`

---

### Variant C — Email 2 (compliment + curiosity) as first touch

**Body**

```
{{first_name}},

{{company_clean}} doing {{service}} for {{icp}} caught my eye – most
{{icp}} vendors don't bother getting that specific.

Quick one – if there was a way to put more {{icp}} on your calendar
every week, without you running the outbound yourself, would that be
worth a 15-min look?

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

**Subject:** `{{company_clean}}`

---

## Optional — Email 3 (signal-based) as its own send

Use when you have a **real signal** in a custom field; otherwise swap the middle line to match your data (job post, funding, etc.).

**`{{random|…}}` spintax** on the lines below (signature block unchanged).

```
{{first_name}},

{{random|Saw|Noticed|Caught that}} {{company_clean}} is in the {{icp}} space with {{service}} – and
based on {{random|what you posted last quarter|your site|your recent posts}}, I think you're trying to move
upmarket.

If that's right, we've helped {{random|3|a few|three}} other companies selling {{service}}
{{random|land calls with|book calls with|set up calls with}} {{icp}} buyers above $50M ARR. {{random|Quick screenshot|A short Loom|A one-pager}} of the
playbook is on us – {{random|open to me sending it?|want me to send it?|ok if I share it?}}

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

---

## Step 2 — F1 (value bump, +3 days after step 1)

**Subject:** leave blank (same thread) or your platform’s default “Re:”.

**`{{random|…}}` spintax** on the lines below.

```
{{first_name}},

{{random|Forgot to mention|Quick add|One more thing}} – {{random|we pulled|we ran|we built}} a sample list of {{icp}} for one of our
{{service}}-style customers last month and got {{random|a 14%|14%|about 14%}} reply rate just
on the first email.

{{random|Worth me running the same play|Want me to run the same play|Should I run the same play}} on {{company_clean}}'s list and {{random|show you the results?|send you what we pulled?|share what that looked like?}}

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

---

## Step 3 — F2 (permission close, +4 days after F1)

**Subject:** blank / thread.

**`{{random|…}}` spintax** on the lines below.

```
{{first_name}},

{{random|Want me to drop off|Should I drop off|Want me to step away}}, or is this just {{random|bad timing|the wrong week|not a priority right now}}? {{random|Either is totally fine|Either way is fine|Totally fine either way}} – I'll take {{random|one word|a fast yes or no|one line}}.

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

---

## Step 4 — F3 (soft breakup, +5 days after F2)

**Subject:** blank / thread.

**`{{random|…}}` spintax** on the lines below.

```
{{first_name}},

{{random|Going to assume|I'll assume|I'll chalk this up to}} the timing {{random|isn't right|is off|isn't there}} – I'll loop back {{random|next quarter|in a few months|later this year}}.
If anything changes on the {{icp}} side, {{random|you know where to find me|ping me|I'm easy to find}}.

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

---

## PlusVibe-style assembly (Eric’s table)

| Step | Wait after prior | Subject              | Body              |
| ---- | ----------------- | -------------------- | ----------------- |
| 1A   | —                 | `{{icp}} question`   | Creative Ideas 3-pt |
| 1B   | —                 | `quick question`     | Email 1 collapsed   |
| 1C   | —                 | `{{company_clean}}`  | Email 2 compliment  |
| 2    | 3 days            | *(blank)*            | F1                |
| 3    | 4 days            | *(blank)*            | F2                |
| 4    | 5 days            | *(blank)*            | F3                |

Run **1A or 1B or 1C** as your step-1 variant test, then the same F1–F3 chain for each.
