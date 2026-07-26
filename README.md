<p align="center">
  <img src="assets/logo.png" alt="Socrates logo" width="160">
</p>

# Socrates

[![Join Socrates](https://img.shields.io/badge/Join_Socrates-%241%2C000-635bff?style=for-the-badge&logo=stripe&logoColor=white)](https://rebeloper.com/#socrates)

## An AI That Refuses to Replace Your Thinking

Socrates transforms [Claude Code](https://claude.com/claude-code) from an answer machine into a deliberate practice partner. Instead of immediately explaining everything, it first challenges you to think. Instead of encouraging passive acceptance, it encourages active reasoning. Instead of making every interaction frictionless, it introduces just enough productive friction to ensure every difficult problem becomes an opportunity to improve.

This isn't about making development slower. It's about making learning inevitable.

That's not just philosophy — it's measurable. [Researchers at the University of Chicago and Toronto found](https://time.com/article/2026/04/30/ai-thinking-cognitive-offloading/) that bringing AI in before you've tried a hard problem yourself makes you remember less, narrow your thinking prematurely, and anchor to whatever the model suggests first. Bring it in after — and it helps instead of hollowing you out. That's the exact seam Socrates is built around: challenge first, answer only once you've earned it.

<details>
<summary>Further reading: the research behind this</summary>

**Academic research**
- [AI-overdependence and human cognitive decline: Hazards, evidence, and mitigation strategies](https://www.sciencedirect.com/science/article/pii/S2451958826001764)
- [Tool, Tutor, or Crutch?: A grounded theory of cognitive scaffolding and offloading in AI-assisted programming education](https://link.springer.com/article/10.1186/s40594-025-00592-w)
- [Deskilling, Reskilling or Upskilling?](https://www.sciencedirect.com/science/article/abs/pii/S0268401225001343)
- [From Algorithm Aversion to AI Dependence](https://myscp.onlinelibrary.wiley.com/doi/full/10.1002/arcp.70008)
- [AI Technology and Labor Skill Transformation](https://www.sciencedirect.com/science/article/abs/pii/S004016252600096X)
- [A Survey of AI Reliance](https://arxiv.org/abs/2408.03948)
- [Knowing About Knowing](https://arxiv.org/abs/2301.11333)
- [Brainrot: Deskilling and Addiction are Overlooked AI Risks](https://arxiv.org/abs/2605.03512)
- [A Systematic Review in Computer Science Education](https://www.sciencedirect.com/science/article/pii/S2666920X26000329)

**Articles**
- [Financial Times – The risk of letting AI do your thinking](https://www.ft.com/content/1f731d9f-5534-4435-b440-e1ded13202a8)
- [TIME – Are We Losing Our Minds to AI?](https://time.com/article/2026/04/30/ai-thinking-cognitive-offloading/)
- [The New Yorker – Instead of Taking Your Job, AI Might Transform It](https://www.newyorker.com/culture/open-questions/instead-of-taking-your-job-ai-might-transform-it)
- [New York Times – Technology Weakens Our Minds. It's Time to Resist.](https://www.nytimes.com/2026/03/27/opinion/technology-mental-fitness-cognitive.html)
- [The Atlantic – The Age of De-Skilling](https://www.theatlantic.com/ideas/archive/2025/10/ai-deskilling-automation-technology/684669/)
- [The Week – Deskilling: A dangerous side effect of AI use](https://theweek.com/tech/deskilling-ai-technology)
- [New York Times – I Saw Something New in San Francisco](https://www.nytimes.com/2026/03/29/opinion/ai-claude-chatgpt-gemini-mcluhan.html)
- [The New Yorker – The Hidden Costs of Automated Thinking](https://www.newyorker.com/tech/annals-of-technology/the-hidden-costs-of-automated-thinking)

</details>

Every insight you discover yourself strengthens mental models that no autocomplete can build for you. Every design decision you reason through becomes easier to recognize the next time. Every mistake becomes another **Capability Compound**—an investment in judgment that continues paying dividends long after today's AI models are obsolete. That is the game Socrates is designed to play. Not today's sprint. Your next decade.

[![Read the Manifesto](https://img.shields.io/badge/Read_the_Manifesto-000000?style=for-the-badge)](MANIFESTO.md)

Read this before installing anything. The eight skills below are the implementation; [the Manifesto](MANIFESTO.md) is the reasoning behind them—why productivity is becoming a commodity, why judgment isn't, and why the friction you're about to opt into is the point, not a bug.

## Nine Skills. One Philosophy.

Everything Socrates does serves a single objective: preserving and strengthening your ability to think.

The first three are **modes**—on by default from the moment the plugin is installed, shaping every conversation until you switch them off. The other six are **commands**—you invoke them when you need them.

### Modes

Each mode takes a single `on` or `off` argument—`/socratic-dev off`, `/socratic-talk on`—and stays that way across sessions until you flip it back. The status line always shows which modes are currently active, so you never have to wonder how Socrates is behaving. With all three on, it looks like this:

```
🏛️·🧿·💬42.7K(21.3%)·♻️~12K
```

🏛️ means socratic-MCQs is on, 🧿 means socratic-dev is on, and 💬 means socratic-talk is on—followed by your live context usage and, after ♻️, the tokens socratic-talk has saved you this session. Turn a mode off and its segment disappears.

The context usage number is color-coded so you can read the health of your session at a glance: **sand** below 100K tokens, **amber** from 100K, and **red** from 200K—time to wrap up or start fresh. The ♻️ savings count is always **green**.

#### /socratic-MCQs

Before explaining an architectural decision, diagnosing a bug, or teaching a concept, Socrates asks you to answer a carefully chosen multiple-choice question.

Not to slow you down. To wake your brain up.

Learning isn't created by reading an explanation. It's created by attempting to predict the explanation before you see it. That small act of retrieval transforms passive consumption into active understanding. Mechanical work stays mechanical. If you've already decided on a solution and simply want Claude to execute it, Socrates gets out of the way. Thinking is only required where thinking actually matters.

#### /socratic-dev

Code generation has made complexity dangerously inexpensive. Nested abstractions, unnecessary patterns, premature optimization, and clever designs can now be produced faster than ever before. Socrates continuously pushes generated code back toward timeless engineering principles—KISS, DRY, and YAGNI—not because minimalism is fashionable, but because complexity compounds far faster than simplicity.

The result isn't code that merely works. It's code that's easier to understand six months later.

#### /socratic-talk

Modern AI conversations are surprisingly wasteful. Verbose explanations, unnecessary acknowledgments, and pages of command output consume context without increasing understanding.

Socrates keeps conversations lean. Responses focus on what matters, while noisy terminal output is routed away from your primary context so your sessions remain focused and your token usage stays lower. Less noise. More signal.

### Commands

Commands don't stay on in the background—each one runs when you call it, does its job, and gets out of the way.

#### /explain

Sometimes you don't need another answer. You need a different explanation.

Whether you're learning recursion for the first time, mentoring a junior developer, onboarding to an unfamiliar codebase, or refreshing a concept you haven't touched in years, Socrates adapts the explanation to the level of understanding you actually need. Teaching isn't about saying more. It's about saying exactly enough.

#### /toLesson

An explanation lives in the chat and dies with the chat. Understanding worth keeping needs a home outside the scroll.

/toLesson takes any concept and turns it into a single, self-contained lesson saved as a Markdown file: the intuition behind it, what it is and when to reach for it, a diagram when one earns its place, an implementation when the topic calls for it, the trade-offs worth remembering, and a question that checks whether it actually landed. Same depth levels as `/explain`, so the file speaks to whoever opens it next—including you, in six months, having forgotten all of it.

A good explanation fades once the conversation ends. A lesson you wrote for yourself doesn't.

#### /teachMe

An explanation answers the question you asked. It doesn't build the whole mental model.

/teachMe takes anything—a codebase, an article, a concept—and turns it into a guided journey instead of a single answer. Socrates breaks the material into an ordered sequence of steps, shows you the map before you start, then walks you through it one step at a time, at the depth you choose, pausing after each one so you decide what happens next: move on, go deeper, hear it a different way, or ask what's actually confusing you. Nothing gets dumped on you at once, and nothing moves forward until you're ready for it to.

That includes Socrates itself. Run `/teachMe the Socrates plugin` and get the same guided walkthrough—the philosophy, the skills, how they fit together—one step at a time, instead of a single orientation dump.

#### /quizMe

Reading feels like learning. It isn't. The only way to know whether you actually understand something is to test yourself—before the answer is in front of you.

/quizMe turns anything—a codebase, an article, a concept, the conversation you just had—into a live multiple-choice quiz, one question at a time. Wrong answers don't get corrected; they get a hint and another attempt, because working your way toward the answer is where the learning happens. And when the quiz ends, you decide what happens next: let it all go, or send the questions that beat you—or every question—straight into Anki so spaced repetition finishes what the quiz started.

#### /toAnki

Understanding something once is not the same as owning it. Insight you never revisit quietly evaporates—usually right around the time you need it again.

/toAnki turns whatever you just worked through—a conversation, a codebase, an article, a concept—into Anki flashcards. By default every card is multiple-choice, the same challenge format Socrates quizzes you with—classic front/back and cloze cards are there when you ask for them. And it's not a bulk export: you review and approve every single card before it enters your deck, because deciding what's worth remembering is itself an act of judgment. Then spaced repetition does what no bookmark ever will. What you earned with Socrates today is still yours in six months.

#### /dialogue

Being handed an answer feels like understanding it. It isn't. Real understanding survives being questioned—and the only way to find out if yours does is to have it questioned.

/dialogue takes a claim you actually hold—an opinion, a definition, a design decision you're leaning toward—and turns it into a live conversation instead of a lecture. State it, and Socrates probes: what do you mean by that, what are you assuming, how do you know, what follows if it's true, who would disagree, why does the question even matter. One question at a time, in your own words, with no multiple choice standing between you and the gap in your own reasoning. When a contradiction surfaces, it doesn't get smoothed over—that discomfort is the whole point, not a bug to route around.

The claim you leave with isn't the one you arrived with. It's sturdier, because you're the one who found where it was thin.

## Who Socrates Is For

Socrates isn't designed for everyone.

If your only objective is producing as much code as possible, there are cheaper tools that will happily generate answers all day long.

If you believe engineering is simply typing instructions into increasingly capable models, you'll probably find Socrates unnecessarily demanding.

That's intentional.

Socrates is built for engineers who view their own capability as the most valuable asset they'll ever own.

The ones who understand that every difficult problem is an opportunity to sharpen judgment.

The ones who care as much about the person writing the software as the software itself.

The ones playing a game measured in decades instead of deadlines.

## Why It Costs $1,000

The research earlier in this README isn't an outlier — study after study finds the same pattern: skill that's never exercised erodes, and judgment is a skill like any other. Socrates is priced like what it protects.

Every engineer understands the return on compounding investments. Small improvements, repeated consistently over long periods of time, create outcomes that look impossible in hindsight. Judgment compounds exactly the same way — and unlike a subscription, this is a one-time cost buying a skill that keeps paying out for as long as you're writing code.

Here's how fast it pays back: one better architectural call, one production incident caught before it ships, one design flaw you spot in review before a teammate does — any single one of those is worth more than $1,000 on its own. Most engineers clear that bar inside the first project.

This is also why it's yours to buy, not your employer's. Plenty of companies will expense a course or a certification — something with a name and a receipt they can point to. Almost none will expense a tool whose entire premise is "this makes you slower on purpose today, so you're sharper in five years" — there's no line item for that, and if you change jobs, the company doesn't keep the payoff anyway. You do. Nobody expects their employer to pay for the gym either, for the same reason. The specific stack you use at work — sure, that's the company's to fund. The mind you bring to every stack after this one is yours.

You're not paying for eight Claude Code skills. You're investing in the only competitive advantage AI cannot commoditize — your ability to think independently.

[![Join Socrates](https://img.shields.io/badge/Join_Socrates-%241%2C000-635bff?style=for-the-badge&logo=stripe&logoColor=white)](https://rebeloper.com/#socrates)
