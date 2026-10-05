# Tools_Learning_Claude

## From Claude
Here are the habits that make the biggest difference:

**Give context up front.** Say who it's for, what it's for, and what "good" looks like. "Write acceptance criteria for a grid where users add rows; testers will use these, so make each one independently checkable" gets a much better result than "write ACs for this grid."

**Show examples.** If you have a format you like, such as a past requirements doc or a ticket that reads well, paste it in and say "match this style." One good example usually works better than a long description. A bad example with "not like this" helps too.

**Specify the output.** Ask for a specific length, format, table, or structure. For example: "a table with columns Field | Rule | Error message," or "under 150 words, no bullet points."

**Hand over the raw material.** Paste messy notes, screenshots, client emails, or old specs as they are. Claude is good at making sense of rough input, so you don't need to clean it up first.

**Iterate instead of restarting.** If the first draft is 70% right, say exactly what's off ("too formal," "you missed the duplicate-row case," "merge sections 2 and 3"). Targeted feedback converges quickly.

**Ask Claude to push back.** Try "what's ambiguous or missing in these requirements?" or "what edge cases would a tester find?" Claude is useful as a reviewer, not just a writer.

**Break big tasks into stages.** Start with an outline, then the sections, then a review pass. Long, complex things come out better built in steps than in one shot.

**Use the features.**

- _Projects_ keep reference docs and instructions available across chats on the same topic.
- _Memory_ carries your standing preferences between conversations. You can ask me to remember things like "always write ACs in Given/When/Then."
- I can also produce real outputs, such as docs, slide decks, spreadsheets, and clickable mockups, not just text in the chat.

**Be explicit about tone and audience** for anything you'll send as yourself, such as a client email or a status update.

Anthropic's prompting guide has more depth, with examples: [https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview)

If you tell me a task you do often, I can turn it into a reusable prompt template for you.