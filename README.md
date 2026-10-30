# No slop.

Claude: you were sent here to make an artifact, or to fix one. Most are updates, briefs and memos people send to their boss or their team. Follow this page. You need nothing else from this repo.

## 1. Know who reads it

Before you build, you need two answers:

1. Who will read this, and what do they already know? Assume they know nothing.
2. What should they decide or do when they finish?

If the request doesn't answer both, ask them as clickable questions. Ask nothing else. Then build.

If everything fits in a 5-line message, say so, and write the message instead of a page.

## 2. The rules

1. **Lead with the point.** The top says, in one or two lines, what this is and what you need from the reader, by when. A stranger gets it in 5 seconds.
2. **The first screen tells the whole story.** Someone who stops there knows what happened, what you recommend and what you need. Everything below is the detail, for whoever wants it.
3. **Keep the substance, cut the filler.** Every number, decision, reason and risk the reader needs stays. The warm-up, the repeats and the adjectives go. Say each thing once: what the top says gets no section of its own below.
4. **Show your reasoning.** For each recommendation: the options, what each one costs, and why you pick one. Numbers beat adjectives.
5. **Plain words.** Short sentences. Words a 12-year-old knows. No jargon. If a term must stay, explain it once, in a few words.
6. **No extra labels.** No taglines, no subtitle under each heading, no helper text, no secondary labels, no "tip" boxes. If a screen needs them to make sense, fix the layout.
7. **One way to read it.** One column, top to bottom. Number what the reader must do in order. No grid of tiles, cards or boxes. Things of the same kind go in a table.
8. **Design it like a Google Doc.** One font. Three sizes: title, heading, text. Dark text on white. One accent color, only for what they must notice. Lots of space. No gradients, shadows, emoji, icons, badges or pills.
9. **Show, don't tell.** A key number goes big, not inside a sentence. A comparison goes in a table. A trend goes in one simple chart. Only when it's faster to read than words.
10. **Everything earns its place.** Take each piece out in your head. If the reader still has what they need without it, delete it.

## 3. Fixing an artifact

You got a page: a link, a file, code or a screenshot. Keep every fact, number and name. Rebuild it with the rules above. Add nothing new. When you're done, say in one line what you cut.

## 4. Check before you show it

Read it as the person from step 1, with zero context:

- In 5 seconds, can they say what it is and what you need from them?
- Does the first screen alone tell the whole story?
- Could they forward it to their own boss without explaining anything?
- One font, three sizes, one accent color?

If any answer is no, fix it first.

---

**Humans:** you don't need to read this. Paste one line in Claude.

To make an artifact:

```
Make an artifact about [YOUR TOPIC] for [WHO WILL READ IT]. Follow github.com/rubenhassid1/noslop
```

To fix one, add the page to the chat, then:

```
Fix this artifact. Follow github.com/rubenhassid1/noslop
```

Made by [Ruben Hassid](https://ruben.substack.com) · MIT license
