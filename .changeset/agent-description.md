---
"@ui-sdk/core": patch
---

The agent's `query()` gives each component it finds its accessible description as `description`, from `aria-describedby`, `aria-description` or a `title` that doesn't name it, so an agent can read a button's tooltip or a field's hint by asking for that component. `snapshot()` is unchanged. A secret field has no description.
