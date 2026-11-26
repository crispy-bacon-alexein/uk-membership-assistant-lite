# UK membership assistant (lite)

A free Claude skill for people who work in UK membership organisations: professional bodies, chartered institutes, trade associations, membership charities, clubs and societies.

Made by [Alexein Ltd](https://www.alexein.co.uk), membership AI and security for UK membership organisations. [What a Claude skill is, and the full version](https://www.alexein.co.uk/skill/). Every Alexein resource is checked by a person before release.

## What it does

When you ask Claude for help with membership work, the skill makes sure Claude:

- **writes in UK membership language**: subscriptions, grades, lapsed members, trustees and Direct Debit, never "dues" or "chapters"
- **protects member data**: it spots names, emails, health details and other personal data in what you share, suggests anonymising it, and keeps it out of the files it produces
- **uses standard definitions** for renewal rate, lapse rate and first-year retention, and says which one it used
- **shows its working**, and ends with a "Check these before you share" list
- **writes renewal reminder emails** as a gentle five-step sequence, with [merge fields] in square brackets and one clear action per email
- **leaves decisions about individual members to you**

## Install in Claude (claude.ai or the Claude app)

1. Download this repository as a zip: click **Code**, then **Download ZIP**.
2. Unzip it, then zip up just the folder `skills/uk-membership-assistant-lite`.
3. In Claude, go to **Settings**, then **Capabilities** (or **Skills**), and upload that zip.
4. Make sure the skill is switched on.

## Install in Claude Code

```
/plugin marketplace add crispy-bacon-alexein/uk-membership-assistant-lite
/plugin install uk-membership-assistant-lite@alexein
```

## Using it

Ask as you normally would, for example "Write our renewal reminder emails. We're a trade association with three grades..." If Claude doesn't seem to be using the skill, start your request with **"Use the UK membership assistant"**.

Before you paste or upload a member export, check that your organisation's AI policy allows it. If you're not sure, remove names, emails and notes first.

## The full version

The full UK membership assistant adds:

- renewal and income reports from your CRM or AMS export, with data quality checks
- member survey analysis
- one-page trustee and board reports
- help choosing a membership system
- the full set of membership metrics and edge cases
- onboarding (first 90 days) and win-back email sequences
- test files, so you can check it yourself

It's licensed for use across your whole organisation, for £79. [See the full version](https://www.alexein.co.uk/skill/).

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can use, share and adapt it, including commercially, as long as you credit "Alexein Ltd (alexein.co.uk)" and link to the licence. See `LICENSE`.

This skill helps with drafting and analysis. It isn't legal or data protection advice. Always check its output before you use it.
