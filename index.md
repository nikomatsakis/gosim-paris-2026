class: center
name: title
count: false

.p60[![Symposium](./images/symposium5_vase-ferris.svg)]

.me[.grey[*by* **Nicholas Matsakis**]]
.left[.citation[View slides at `https://nikomatsakis.github.io/gosim-paris-2026/`]]

---

# What is Symposium?

* Extended Rust toolchain for agentic development

--


* Marquee feature:
    * Installing skills, hooks, etc based on your dependencies

--


* Member of the Rust Foundation's Innovation Lab

![RIL](./images/RIL.png)

---

# Why Symposium?

---

# Who am I?

One of the lead designers of Rust

.center[.p80[![Ferris](./images/ferris.svg)]]

---

# Who am I?

Senior Principal Engineer at Amazon

.center[.p80[![Ferris](./images/spheres.jpg)]]

---

# Not heard of Rust?

.abspos.top25.left519.width300px[![Rust](./images/rust-logo-512x512.png)]

*Low-level enough for a kernel...*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *usable enough for a GUI*

---

# Rust has been on a roll lately

* Reliable, memory safe

--

.bordered[![Rust in Android](./images/rust-in-android-banner.png)]

.bordered.abspos.top331.left274.width500px[![Chart](./images/rust-in-android-chart.png)]

--

.abspos.arrow.top370.left371.rotate135[![Arrow](./images/Arrow.png)]

--

.abspos.arrow.top386.left434.rotate135[![Arrow](./images/Arrow.png)]

--

.abspos.arrow.top415.left496.rotate135[![Arrow](./images/Arrow.png)]

---

# Rust has been on a roll lately

* Reliable, memory safe
* Efficient by default

--

.abspos.top196.left28.width600px.bordered[![Rust win](./images/rust-win-3.png)]

--
.abspos.top304.left150.width600px.bordered[![Rust win](./images/rust-win-2.png)]

--
.abspos.top379.left286.width600px.bordered[![Rust win](./images/rust-win-1.png)]

---

# Rust has been on a roll lately

* Reliable, memory safe
* Efficient by default
* Productive and versatile

--

> When I got to know about it, I was like 'yeah this is the language I've been looking for'. This is the language that will just make me stop thinking about using C and Python. So I just have to use Rust because then **I can go as low as possible as high as possible**.<br>
> <br>
> &mdash; Software engineer and community organizer in Africa

---

# But two main things have been holding us back

* "Rewrites are expensive"

--
* "Learning curve"

---

# But lately... things have been looking a bit different

> My goal is to eliminate every line of C and C++ from Microsoft by 2030. Our strategy is to combine AI *and* Algorithms to **rewrite Microsoft’s largest codebases**. Our North Star is “1 engineer, 1 month, 1 million lines of code”.<br>
> <br>
> &mdash; Distinguished Engineer at Microsoft, [talking about a research project](https://www.linkedin.com/posts/galenh_principal-software-engineer-coreai-microsoft-activity-7407863239289729024-WTzf/) (emphasis mine)

---

# *Really* different

> If you’ve already tried Rust and found the learning curve too steep, give it another try with Claude Code or Codex as your pair programmer. **The experience is different when you have an AI that can navigate ownership and borrowing patterns** while you focus on building things.<br>
> <br>
> The tools finally catching up to the promise of the language.<br>
> <br>
> &mdash; Tigran Bayburtsyan, ["Coding Rust with Claude Code and Codex"](https://tigran.tech/coding-rust-with-claude-code-and-codex/) (emphasis mine)

---

# What is happening?

**With AI, coding is faster,**

---

# What is happening?

**With AI, coding is faster,**

...so nobody will use libraries and we'll just let agents write assembly language for max performance!

--

.abspos.top269.left455[![Marisa is skeptical](./images/marisa-skeptical.gif)]

---

# What is happening?

**With AI, coding is faster,**

--

...so fundamentals matter **more**, not **less**.

.abspos.top233.left391.width400px[![Sold!](./images/sc-sold.gif)]

---

# Rust + LLM = dream-team?

* Guardrails

--
template:guardrails

.p80[![Greg Brockman saying Rust is a great language for agents](./images/greg-brockman-tweet.jpg)]

.footnote[
    Co-founder and president of OpenAI.
]


---

# Rust + LLM = dream-team?

* Guardrails
* Versatility

--

.abspos.width600px.bordered.top212.left150[![Codex adopts Rust](./images/codex-rust-rewrite.png)]

---

# Rust + LLM = dream-team?

* Guardrails
* Versatility
* Efficiency

--

.abspos.top247.left52.width600px.bordered[![Rust win](./images/rust-win-3.png)]

.abspos.top349.left112.width600px.bordered[![Rust win](./images/rust-win-2.png)]

.abspos.top415.left187.width600px.bordered[![Rust win](./images/rust-win-1.png)]

---

# Rust + LLM = dream-team?

* Guardrails
* Versatility
* Efficiency
* Investment in error messages

--

.center.megamoj[🤔]

---

# Error messages?

![Error message from the Rust compiler](./images/error-messages.png)

--

.abspos.arrow.top183.left260.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top163.left302.textbox.purple[The base error]

--

.abspos.arrow.top353.left298.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top341.left341.textbox.purple[Needed context]

--

.abspos.arrow.top441.left244.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top426.left284.textbox.purple[How to fix]

---

# So... Rust + agents are good

## But could they be better?


---
name:toasty

# Example: Toasty

![Toasty](./images/toasty-blog.png)

---
template:toasty
.abspos.arrow.top326.left303.rotate135[![Arrow](./images/Arrow.png)]

---
template:toasty

.abspos.arrow.top389.left168.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top491.left175.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top546.left193.rotate135[![Arrow](./images/Arrow.png)]

---
name: using-toasty
# Example: Using Toasty

![Toasty](./images/toasty-use.png)

---
template: using-toasty
.abspos.arrow.top143.left237.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top129.left280.textbox.purple[Macros and custom syntax]

---
template: using-toasty

.abspos.arrow.top372.left369.rotate230[![Arrow](./images/Arrow.png)]

.abspos.arrow.top425.left352.textbox.purple[New methods]

---

# Toasty is a good example of what is cool about Rust

* **Guardrails:** API enforces type-safety, correct column names, etc
* **Versatility:** High-level and declarative
* **Efficiency:** Compiles to efficient code

.footnote[
    But don't ask about the *Error messages* -- getting good error messages from a macro-heavy library
    like this is a whole 'nother talk!
]
---

# Claude doesn't even know it exists

"What library do you recommend for working with sqlite in Rust?"

![Answer](./images/claude-sql-recs.png)

.footnote[
    For the record, these too are all excellent libraries!
]

---

# Claude, can you use toasty?

![Answer](./images/claude-make-executable-prompt.png)

---

# Claude, can you use toasty?

![Answer](./images/claude-make-executable-work.png)

--

.abspos.arrow.top163.left572.textbox.purple[That's a lot of tokens...]

---

# Claude, can you use toasty?

![Answer](./images/claude-make-executable.png)

--

.abspos.arrow.top278.left613.rotate110[![Arrow](./images/Arrow.png)]

---

# Toasty on crates.io

![Answer](./images/toasty-on-cio.png)

--

.abspos.arrow.top295.left160.rotate110[![Arrow](./images/Arrow.png)]

.abspos.arrow.top295.left160.rotate110[![Arrow](./images/Arrow.png)]

---

# The world is moving faster than ever

## Training data can't keep up

--

![Answer](./images/claude-make-executable.png)

--

.abspos.arrow.top584.left228.rotate180[![Arrow](./images/Arrow.png)]

.abspos.arrow.top591.left280.textbox.purple[Rust 2024 hit stable Feb 2025]

---

# Common failings I see

* Using old versions of crates
* Using old versions of Rust
* Writing GC-like patterns in Rust
    * Claude 💖 mutexes
    * Niko does not

---

# Most frustrating thing of all?

## ...the Rust org cannot help

.center[![Help me obi-wan kanobe, you're my only help](./images/help-me-obi-wan.gif)]
.abspos.arrow.top366.left313.textbox.purple[&nbsp;&nbsp;Anthropic<sup>1</sup>&nbsp;&nbsp;]

.footnote[
    <sup>1</sup> I should say: I tried that toasty example twice, and the second time, Claude did use Toasty 0.5. But it still made a Rust crate in the 2021 edition.
]

---

# Core axiom: Extensibility wins

.center["Everybody has something unique to offer"]

.center[.p60[![Release the river](./images/release-the-river.gif)]]

.abspos.arrow.top518.left305.textbox.purple[*"Release the Rust ecosystem!"*]


---

# ..and this is where Symposium comes in

.center[.p60[![Symposium](./images/symposium5_vase-ferris.svg)]]

---

# Install symposium

```
$ cargo binstall symposium
```

--

```
$ cargo agents init
Setting up symposium for your user account.

Which agents do you use? (space to select, enter to confirm):
> [x] Claude Code
  [ ] Codex CLI
  [ ] GitHub Copilot
  [ ] Gemini CLI
  [ ] Goose
  [x] Kiro
  [x] OpenCode
```

---

# Symposium gives general guidance

* General Rust guidance, e.g.,
    * Use Rust 2024
    * Use `cargo add` to add crates so you get the latest version
    * Run `cargo fmt` after making edits

---

# Symposium syncs skills

![Toasty skill](./images/toasty-skill.png)

--

.abspos.top195.left28.arrow[![Arrow](./images/Arrow.png)]

---

# Symposium syncs skills

```
$ ls
Cargo.lock      Cargo.toml      src

$ cargo agents sync
ℹ️  scanning 1 workspace dependencies
🟢 ~/.claude/settings.json: hooks already registered
✅ installed skill find-crate-source → ~/dev/toaster/.claude/skills/find-crate-source
✅ installed skill rust-best-practice → ~/dev/toaster/.claude/skills/rust-best-practice
✅ installed skill toasty-guidance → ~/dev/toaster/.claude/skills/toasty-guidance
🟢 ~/.kiro/agents/symposium.json: hooks already registered
✅ installed skill find-crate-source → ~/dev/toaster/.kiro/skills/find-crate-source
✅ installed skill rust-best-practice → ~/dev/toaster/.kiro/skills/rust-best-practice
✅ installed skill toasty-guidance → ~/dev/toaster/.kiro/skills/toasty-guidance
```

--

.abspos.top176.left236.arrow.rotate135[![Arrow](./images/Arrow.png)]


---

# Symposium syncs skills... automatically

* Install hooks:
    * After every tool use, `cargo agents sync` runs automatically
    * When the agent runs `cargo add`, new skills appear

---
name: crate-info
# Symposium provides APIs to help agents

```bash
> cargo agents crate-info serde
Crate: serde
Version: 1.0.228
Source: /Users/nikomat/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228
```

---
template: crate-info

.abspos.arrow.top169.left221.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top150.left265.textbox.purple[Correct version used by your code]

---
template: crate-info

.abspos.arrow.top257.left340.rotate210[![Arrow](./images/Arrow.png)]

.abspos.arrow.top308.left373.textbox.purple[Let the agent browse full sources]

---

# Symposium provides for interoperability

As a library author, write one set of extensions that work across agents...

--

...good luck with that.

---

# Even AGENTS.md is not universally supported

.abspos.bordered.width600px[![Agents](./images/agents.md.png)]

--

.abspos.bordered.width600px.top315.left224[![Agents](./images/agents.md.scoll.png)]

---

# Niko to vendors...

.abspos.top165.left222[![Help me help you](./images/help-me-help-you.gif)]

---

# Symposium does the best we can

* Library (crate) provides extensions
    * MCP servers
    * Skills
    * Hooks
--


* User picks agent

--


* Symposium adapts
    * Load skills into the right directories for the agent user chose
    * Converts between hook formats

---

# Conclusions

* Rust + LLM = peanut butter + chocolate
--

* Symposium:
    * Bring the collective wisdom of the Rust ecosystem to bear on making your agent code better
--
* Extensibility FTW:
    * Everyone has something unique to offer

--

Use Rust? Try it now!

```
$ cargo binstall symposium
$ cargo agents init
```

.abspos.top353.left459[![Make it so](./images/make-it-so.gif)]