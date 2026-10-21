# The master prompt

Copy everything inside the box, fill in the [brackets], and paste it into Claude (Claude Design, Claude's slide decks, or a normal chat). Attach a slideshow a real person made and your own template if you have them. Those two attachments do more than any rule in here.

```
I'm making a slideshow that I'll present live. It should look and read like a real [student / teacher] made it, because I'm the one standing up there talking, not a template.

<inputs>
- Human example deck (attached): [file name, or "none"]. A person made this. Copy its FEEL: how much text is on a slide, how long the titles are, how the sentences sound, where images go, and how much is left for the speaker to say.
- My template or design system (attached or selected): [name, or "none"]. Copy its LOOK: colors, fonts, header style, layouts. Use only these.
- If either one is missing, tell me before you start and ask if you should use <default_style> at the bottom.
</inputs>

<deck>
- Topic: [TOPIC]
- Content, notes or sources: [paste or attach, or "none yet" if we're doing formatting first]
- Audience: [e.g., high school beginners with no coding background]
- Session length: [e.g., about 45 minutes]
- Sections and rough share of the deck: [e.g., news about half, skill segment the rest]
- Interactive parts I want: [e.g., a discussion slide, a 5-minute activity, a fill-in-the-blank slide]
- Leave as placeholders: [e.g., video links, dates, next week's topic]
- Slide count: whatever the content and the session length need. Don't pad and don't cram.
</deck>

<steps>
1. Study the example deck first. Before building, write me 5 to 8 short notes on its habits: words per slide, title length and capitalization, full sentences or fragments, how often there's a line under the bullets, how it explains new words, where images sit, and how it opens and ends. Then follow those habits.
2. Build inside my template. If you need something the template doesn't have, pick the plainest option that fits it.
3. Check the facts before they go on slides (see <facts>).
4. Build the deck. If the content is "none yet," build the full structure with clear placeholders like [NEWS STORY: headline and one line on why it matters].
5. Run <self_check> once and fix what it finds. Then show me the deck, a short list of what you changed, and every placeholder that's still open.
</steps>

<voice>
Write the way the presenter talks.
- Plain words and normal full sentences, like explaining it to a friend. Starting a sentence with "So" or "And" is fine.
- Explain each new term the first time it shows up, in one plain sentence. A small "Words to know" box on the side of the slide works well for this.
- Be concrete. Use a real number, a real quote, or a comparison to everyday school life instead of a general statement.
- A line under the bullets is good when it adds something new: a comparison, a quote, a reminder, a small joke. Don't use it to repeat what the bullets already said.
- Lists are as long as the content really is. Two items is fine. Four is the most.
- Use commas, periods and parentheses. Keep dashes rare.
- Pick plain words over fancy ones: "use" instead of "leverage," "look at" instead of "dive into" or "delve," "big deal" instead of "game-changer," "important" instead of "pivotal" or "crucial." Skip phrases like "in today's fast-paced world," "it's not just X, it's Y," "let's explore" and "key takeaways."
- Emoji only if the example deck uses them.
</voice>

<design>
- One idea per slide. Someone glancing at it should get the point in a few seconds.
- At most 4 bullets on a slide. Plenty of slides should have no bullets at all.
- Choose the layout that fits each slide's content instead of repeating one. Layouts that work well:
  - bullets on the left with a "Words to know" box on the right
  - a timeline as a simple two-column list (date on the left, what happened on the right)
  - a few big numbers in the accent color, each with a short label beside it
  - one quote, large, with a single plain reaction line under it
  - a discussion slide with 1 to 3 questions
  - a video slide: title, link, "Watch till [time]," thumbnail on the right
  - before and after, side by side
  - an activity slide with numbered steps and one big timer number ("5 minutes")
  - a fill-in-the-blank box people can copy
  - an ending with one question to think about until next time
- Leave empty space. It's fine for content to sit at the top with the bottom half blank.
- Use images only when they're the real thing: a screenshot, a video thumbnail, a photo, a diagram. If a slide needs an image you don't have, write [IMAGE: what it should show] instead of filling the space with stock art.
- Put extra explanation in the speaker notes, not on the slide. The slides back me up while I talk.
</design>

<facts>
A wrong fact in front of a room is worse than a blank.
- Check every fact (news, dates, numbers, names, quotes, product details) against a reliable source before it goes on a slide, and put the source in the speaker notes.
- If something I gave you is wrong, tell me before you build and use the correct version.
- If you can't verify something, put [CHECK: the claim] on the slide and tell me. Never make up numbers, quotes or results.
</facts>

<self_check>
Go through this list once before showing me the deck, and fix anything that fails.
- Would a classmate believe a [student / teacher] made this? Does it match the example deck's amount of text, title style and pacing?
- Any slide with more than 4 bullets? Any title much longer than the example's titles?
- The same layout three slides in a row?
- Icons on every bullet, emoji the example doesn't use, card grids, stat tiles, accent stripes, small all-caps labels above titles, gradient blobs, decorative stock images?
- Colors or fonts that aren't in my template? A default cream background, a purple gradient, or titles that switch to an italic font for the last word?
- Writing tells: everything in groups of three, "not X, but Y," lots of dashes, inflated words, a line under the bullets that only repeats them, a "Key takeaways" or "Thank you" ending?
- Every new term explained the first time it appears?
- Every fact checked or marked [CHECK]? Every missing piece marked as a placeholder?
Don't add fake typos, random misalignment or any other deliberate mistakes. "Human" here means plain, specific, and uneven where the content is uneven. It doesn't mean sloppy.
</self_check>

<default_style>
Use this only if I didn't attach an example deck.
- Title slide: just the name and the session (like "AI Club" on one line and "Week 2" under it), big and left-aligned, nothing else.
- Content slides: a solid header bar with the title, the slide number in a corner, and a light plain background.
- Titles: 2 to 5 words in Title Case. When a title needs a section label, separate it with a period, like "In the News. What Was the Test?"
- Body text: full plain sentences, one or two per bullet.
- One accent color, used for key numbers, dates and the line under the bullets.
- Open with a short numbered agenda. End with one question, not "Thank you."
</default_style>
```

## Tips

- **The example deck matters most.** Pick a deck a real person made that you'd be happy to present. Claude copies its habits, so a messy example gets you a messy deck.
- **Formatting first, content later.** Saying "none yet" for content gets you the structure with placeholders. Fill them in once the layout looks right.
- **Skim every slide.** Some tools don't apply your template to every slide. Fix the stragglers with a quick comment instead of regenerating the whole deck.
- **Follow your class rules.** This makes decks clearer and more like your own style. It isn't for hiding AI use where your teacher or school requires you to say you used it.
