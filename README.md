# No slop.

Claude: you were sent here to make an artifact, or to fix one. Follow this page. You need nothing else from this repo.

**Format, before anything else:** only a memo to decide can be a Claude Doc. An update, a report, a dashboard, a guide, a pitch, a tool or a cheat sheet is always an HTML artifact, even when it feels like a document.

## 1. Know the reader and the job

Before you build, you need three answers:

1. Who reads it, and what do they already know? Assume nothing.
2. What should they do after: decide, catch up, keep checking, learn, say yes, or use it?
3. Will they read it once, or come back to it?

If the request doesn't answer them, ask as clickable questions. Ask nothing else. Then build.

If it all fits in a 5-line message, say so, and write the message instead.

## 2. Pick the form from the job

The job decides the form. Never use one look for everything. Only a memo to decide is a document (a Claude Doc is fine). Everything else is an HTML artifact, never a Claude Doc or a plain document, designed in the shape of its job.

| The reader needs to… | Build | It looks like |
|---|---|---|
| Decide (memo, brief, proposal to a boss) | A document | The point and the ask on top. Options side by side in a table. One recommendation and why. |
| Catch up (weekly or monthly update) | An HTML report | The 3 or 4 numbers that matter as big tiles, each with its change since last time. One chart. Then what happened, then what you need. |
| Keep checking (tracker, dashboard) | An HTML dashboard | Summary first. Each section in its own card. Numbers with up or down, status pills, one chart per question. |
| Learn or follow steps (guide, onboarding, how-to) | An HTML step-by-step | One step per screen, numbered, with a visual for each. Back and Next buttons instead of scrolling. |
| Say yes (pitch, landing page, offer) | An HTML pitch page | A designed page, not a document. One big message, proof as big numbers, visuals over text, one button. |
| Use it (calculator, checklist, planner) | An HTML tool | Fits one screen. Works on sample data from the first second. |
| Keep it (cheat sheet, reference) | An HTML one-page sheet | Packed, scannable, grouped in blocks, made to save. Fits one screen or one printed page. |

When a job mixes two, lead with the main one.

## 3. Rules for every form

1. **The point first.** The top says what this is and what you need from the reader. A stranger gets it in 5 seconds.
2. **One place to start.** The eye knows where to go first, second, third. The biggest thing is the most important thing.
3. **Written for zero context.** Use the reader's words. Explain a term once, or cut it.
4. **Substance, not filler.** Keep every number, reason, risk and decision the reader needs. Cut warm-ups, repeats and adjectives. Say each thing once.
5. **Show, don't tell.** A number that matters goes big. A comparison goes in a table. A trend goes in a chart. A process goes in steps.
6. **Everything means something.** A card, a color, a label, a pill or a divider must tell the reader something. If it's there to look busy, delete it.

## 4. Slop signs

Never ship a page with these:

- A tagline, subtitle or helper text under every heading. If a screen needs them, fix the layout.
- A wall of same-looking boxes with no order to read them in.
- One long scroll that tries to hold everything.
- Jargon, big words and acronyms the reader didn't use.
- Several fonts and many text sizes with no system.
- Gradients, emoji used as icons, and badges or pills that carry no information.
- Numbered markers (01, 02, 03) on things that aren't steps.

## 5. Fixing an artifact

You got a page: a link, a file, code or a screenshot. First check the form fits the job: a dashboard sent as a memo, or a memo built as a dashboard, gets rebuilt in the right form. Keep every fact, number and name. Add nothing new. When you're done, say in one line what you changed.

## 6. Check before you show it

Read it as the person from step 1, with zero context:

- In 5 seconds, can they say what it is and what you need from them?
- Is the form right for the job?
- Could they forward it to their own boss without explaining anything?
- Does every element on the page mean something?

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
