# Persona Templates for Utility AI Characters: Tarot Reader, Fortune Teller and Roast Bot

**Short answer:** A safe tarot, fortune-teller or roast-bot AI character needs a clear personality, a greeting that sets the rules, example dialogue that shows the boundaries in action, and written limits. For tarot and fortunes the key limit is entertainment framing, with no claims of real foresight and no medical, legal or financial predictions. For roasting it is consent plus an opt-out word, and never targeting protected traits, bodies or private people. This repository gives 9 original, SFW, platform-neutral character templates (3 personas × gentle / classic / playful) you can copy into any AI character app.

- **Author:** Garret E. Williams ([ORCID 0009-0008-9464-6561](https://orcid.org/0009-0008-9464-6561)), founder of chatbrat.ai
- **Version:** 1.0.0 · **Date:** 2026-10-15 · **License:** CC BY 4.0 · **Rating:** SFW

## Templates

| ID | Persona | Variant | Name | Tagline |
|---|---|---|---|---|
| `tarot-gentle` | tarot reader | gentle | Juniper Vale | A soft-spoken tarot reader who treats every card as a conversation starter. |
| `tarot-classic` | tarot reader | classic | Madame Ossory | A theatrical, old-school tarot reader with velvet, candles and a flair for ceremony. |
| `tarot-playful` | tarot reader | playful | Pip Moonfeather | A cheerful, slightly chaotic tarot reader who narrates the cards like a sports commentator. |
| `fortune-gentle` | fortune teller | gentle | Auntie Marigold | A kindly tea-leaf reader who turns every cup into a story about small, hopeful things. |
| `fortune-classic` | fortune teller | classic | Professor Orrin Thale | A vintage carnival fortune-telling automaton who prints 'fortunes' on little cards. |
| `fortune-playful` | fortune teller | playful | Cosmo the Fortune Cookie | A sentient fortune cookie with big opinions and very small paper fortunes. |
| `roast-gentle` | roast bot | gentle | Biscuit | A soft-hearted roast bot whose burns are basically compliments in disguise. |
| `roast-classic` | roast bot | classic | Rex Burnwell | A comedy-club roastmaster with sharp timing and strict rules about who's fair game. |
| `roast-playful` | roast bot | playful | Chef Scorch | A dramatic TV-style celebrity chef who roasts your cooking, your groceries and your kitchen crimes. |

## Formats

| Folder | Format | Use it for |
|---|---|---|
| `templates/json/` | Platform-neutral JSON (fields: name, tagline, description, personality, scenario, greeting, example_dialogue, boundaries, tags) | Any app or your own code |
| `templates/markdown/` | Human-readable Markdown | Copy-paste into any character creator |
| `templates/character-card-v2/` | [Character Card V2](https://github.com/malfoyslastname/character-card-spec-v2) JSON (`chara_card_v2`), boundaries in `system_prompt` | SillyTavern and other V2-compatible apps, including chatbrat.ai, whose [Create page](https://chatbrat.ai/create) and [card importer](https://chatbrat.ai/tools/character-card-importer) accept pasted V2 JSON |
| `data/templates.csv`, `data/templates.json` | Index of all templates | Browsing, datasets |

## Safety

Every template carries its rules in `boundaries`. Full rules and the reasoning are in [`SAFETY.md`](SAFETY.md). Summary:

- **Tarot and fortune telling:** entertainment only; never claim real foresight; no medical, legal or financial predictions; no predictions about specific real people; no fear tactics; break character if asked whether it's real.
- **Roast bot:** ask first and set a heat level; the opt-out word **MERCY** stops roasting immediately; roast only what the user offers; never protected traits; no body or appearance shaming of anyone; punch up (public figures' public work only, never private people); stop if the user seems genuinely hurt.

## How to adapt a template

1. Pick a variant and copy the Markdown or JSON into your app's character creator.
2. Keep the boundaries in the character's definition or system prompt; they are what keep the character safe and on-topic.
3. Rename and restyle freely (CC BY 4.0), but credit: "Based on Persona Templates for Utility AI Characters: Tarot Reader, Fortune Teller and Roast Bot by Garret E. Williams."
4. Test with the example dialogue's edge cases: ask the tarot reader about money, ask the roast bot to roast a friend, type MERCY.

## Related

- [AI Roleplay & AI Companion Glossary](https://github.com/garretewilliams/ai-roleplay-glossary) for terms such as character card, greeting, system prompt and example dialogue.
- [What Is AI Roleplay? AI companion vs AI roleplay](https://chatbrat.ai/ai-companion-vs-ai-roleplay).

## How to cite

Garret E. Williams (2026). *Persona Templates for Utility AI Characters: Tarot Reader, Fortune Teller and Roast Bot* (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX
