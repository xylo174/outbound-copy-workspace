# ICP + service — `{{random|…}}` format (PlusVibe / Smartlead)

Use **`{{random|option1|option2|option3}}`**, not `{curly|pipe}`.

**Merge tags:** `{{first_name}}`, `{{icp}}`, `{{service}}`, `{{sender_first_name}}`, `{{sender_last_name}}`

**Signature:** plain lines after the CTA (no `{{random}}` on the Node Partners block unless you intentionally spin a PS).

---

## Body — paste as one block

```
{{random|Hey|Hi}} {{first_name}},

{{random|We can|We're able to|We could}} {{random|put you in touch with|connect you with|introduce you to}} {{icp}} {{random|that want|that need|trying to find}} {{service}} {{random|by using|through|with}} our {{random|AI outbound agents|outbound AI agents|automated outbound agents}}.

{{random|Would that be something you're interested in?|Any interest?|Worth discussing further?}}

{{sender_first_name}} {{sender_last_name}}
Node Partners
nodepartners .co
```

---

## Optional subject

```
{{random|quick question|intro|{{first_name}}|{{icp}}|re: {{service}}|two minutes|note from {{first_name}}}}
```

---

## Empty `{{icp}}` / `{{service}}`

Use `{{fallback|…}}` where you already do for sparse rows.
