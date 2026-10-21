# humanized-slides

A master prompt (and a Claude skill) for making AI slideshows that look and read like a real student or teacher made them.

AI-made decks are easy to spot: the same card layout on every slide, an icon next to every bullet, words like "pivotal" and "seamless," a "Key takeaways" slide at the end. This prompt fixes that by giving Claude a real person's deck to copy instead of a list of rules to guess from. It was built from a real high school AI Club deck and is meant for classes, clubs and anyone who presents their own slides.

## How to use it

1. **Open [PROMPT.md](PROMPT.md)** and copy the prompt inside the box.
2. **Fill in the [brackets]:** topic, content, audience, session length, sections.
3. **Attach two things** if you have them: a slideshow a real person made (to copy its feel) and your own template (to copy its look).
4. **Paste it into Claude** (Claude Design, Claude's slide decks, or a regular chat that can make slides).

Claude will first tell you what habits it noticed in your example deck, then build the deck, check it against a list of AI tells, and hand it back with a list of anything still left to fill in.

### Using it as a Claude skill

The [skill/humanized-slides](skill/humanized-slides) folder has the same instructions as a skill, so you don't have to paste the prompt every time. Zip that folder and upload it in Claude's settings under skills, or copy it into `~/.claude/skills/` if you use Claude Code.

## What's inside

| File | What it is |
|---|---|
| [PROMPT.md](PROMPT.md) | The master prompt, ready to paste |
| [ai-tells-checklist.md](ai-tells-checklist.md) | The design and writing habits that make slides look AI-made, with sources |
| [slide-patterns.md](slide-patterns.md) | Layouts that feel human, taken from a real deck |
| [examples/ai-club-week-2.md](examples/ai-club-week-2.md) | The real deck this was built from, broken down slide by slide |
| [skill/humanized-slides](skill/humanized-slides) | The same thing as a Claude skill |

## How it's different

There are already good "humanizer" projects for writing, like [blader/humanizer](https://github.com/blader/humanizer), and good anti-slop design skills, like [anti-ai-slop](https://github.com/Vinayak-Shukla-03/anti-ai-slop). This one is narrower:

- **It copies a real person's deck.** Claude matches the amount of text, title style and pacing of a deck you attach, instead of a style the tool picks.
- **It's for classrooms and clubs.** Plain student and teacher voice, defined vocabulary, discussion questions and activities, not pitch-deck polish.
- **Facts get checked.** Claude has to verify facts before they go on a slide and mark anything it can't verify.
- **No install needed.** It's a prompt you paste.

## Things it won't do

- **Add fake mistakes.** Some "humanizer" tricks add typos or messy alignment on purpose. That just looks worse. Human here means plain and specific, not sloppy.
- **Help you hide AI use.** If your class or school says you have to disclose AI use, disclose it. This makes your slides clearer and more like your own style.

## Contributing

Ideas welcome, especially:

- new slide patterns from real human decks
- AI tells you've spotted that aren't on the list yet
- before and after screenshots of a deck made with and without the prompt

Open an issue or a pull request.

## Credits

The AI tells list draws on Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) page by WikiProject AI Cleanup, and on design guidance from Plus AI, Perceptis, anti-ai-slop and Anthropic's frontend-design skill. The design ideas come from Garr Reynolds, Nancy Duarte, Michael Alley and Richard Mayer. Full links are in [ai-tells-checklist.md](ai-tells-checklist.md).

## License

[MIT](LICENSE)
