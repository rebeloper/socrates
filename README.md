<p align="center">
  <img src="assets/logo.png" alt="Socrates logo" width="160">
</p>

# Socrates

[![Join Socrates](https://img.shields.io/badge/Join_Socrates-%241%2C000-635bff?style=for-the-badge&logo=stripe&logoColor=white)](https://rebeloper.com/#socrates)

## An AI That Refuses to Replace Your Thinking

Socrates transforms [Claude Code](https://claude.com/claude-code) from an answer machine into a deliberate practice partner. Instead of immediately explaining everything, it first challenges you to think. Instead of encouraging passive acceptance, it encourages active reasoning. Instead of making every interaction frictionless, it introduces just enough productive friction to ensure every difficult problem becomes an opportunity to improve.

This isn't about making development slower. It's about making learning inevitable.

Every insight you discover yourself strengthens mental models that no autocomplete can build for you. Every design decision you reason through becomes easier to recognize the next time. Every mistake becomes another **Capability Compound**—an investment in judgment that continues paying dividends long after today's AI models are obsolete. That is the game Socrates is designed to play. Not today's sprint. Your next decade.

[![Read the Manifesto](https://img.shields.io/badge/Read_the_Manifesto-000000?style=for-the-badge)](MANIFESTO.md)

Read this before installing anything. The seven skills below are the implementation; [the Manifesto](MANIFESTO.md) is the reasoning behind them—why productivity is becoming a commodity, why judgment isn't, and why the friction you're about to opt into is the point, not a bug.

## Seven Skills. One Philosophy.

Everything Socrates does serves a single objective: preserving and strengthening your ability to think.

The first three are **modes**—on by default from the moment the plugin is installed, shaping every conversation until you switch them off. The other four are **commands**—you invoke them when you need them.

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

#### /about

Every tool you adopt deserves a moment of honest orientation before you commit to it.

/about introduces Socrates itself, fetched live from the source rather than recited from memory. Ask for the Manifesto and you get the philosophy: why productivity is becoming commoditized and judgment isn't. Ask for the README and you get the practical shape of the thing: what it does, how it's installed, how it's used. Say nothing and it asks which one you actually want—orientation should offer a choice, not assume one.

#### /explain

Sometimes you don't need another answer. You need a different explanation.

Whether you're learning recursion for the first time, mentoring a junior developer, onboarding to an unfamiliar codebase, or refreshing a concept you haven't touched in years, Socrates adapts the explanation to the level of understanding you actually need. Teaching isn't about saying more. It's about saying exactly enough.

#### /quizMe

Reading feels like learning. It isn't. The only way to know whether you actually understand something is to test yourself—before the answer is in front of you.

/quizMe turns anything—a codebase, an article, a concept, the conversation you just had—into a live multiple-choice quiz, one question at a time. Wrong answers don't get corrected; they get a hint and another attempt, because working your way toward the answer is where the learning happens. And when the quiz ends, you decide what happens next: let it all go, or send the questions that beat you—or every question—straight into Anki so spaced repetition finishes what the quiz started.

#### /toAnki

Understanding something once is not the same as owning it. Insight you never revisit quietly evaporates—usually right around the time you need it again.

/toAnki turns whatever you just worked through—a conversation, a codebase, an article, a concept—into Anki flashcards. By default every card is multiple-choice, the same challenge format Socrates quizzes you with—classic front/back and cloze cards are there when you ask for them. And it's not a bulk export: you review and approve every single card before it enters your deck, because deciding what's worth remembering is itself an act of judgment. Then spaced repetition does what no bookmark ever will. What you earned with Socrates today is still yours in six months.

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

Because this isn't productivity software. It's professional development.

Every engineer understands the return on compounding investments. Small improvements, repeated consistently over long periods of time, create outcomes that look impossible in hindsight.

Judgment works exactly the same way. One better architectural decision can save months. One avoided production failure can save hundreds of hours. One stronger engineering instinct can shape the trajectory of an entire career.

Those returns dwarf the cost of the software. You're not paying for seven Claude Code skills.

You're investing in the only competitive advantage AI cannot commoditize. Your ability to think independently.

[![Join Socrates](https://img.shields.io/badge/Join_Socrates-%241%2C000-635bff?style=for-the-badge&logo=stripe&logoColor=white)](https://rebeloper.com/#socrates)
