class: center
name: title
count: false

.p60[![Symposium](./images/symposium5_vase-ferris.svg)]

.me[.grey[*by* **Nicholas Matsakis**]]
.left[.citation[View slides at `https://nikomatsakis.github.io/talkrepo/`]]

---

# Who am I?

--

* Rust maintainer since 2011

--

* Co-lead of the Rust language design team

--

* Senior Principal Engineer at Amazon

---

# Not here in that capacity

---

# What is Symposium?

--

Two answers:

--

* A tool to install crates/hooks/etc based on your Rust dependencies

---

# Example

*demo*

*demo*

---

# What is Symposium?

Two answers:

* A tool to install crates/hooks/etc based on your Rust dependencies

--

* A Rust toolchain aimed for use with *agents*

---

# A toolchain aimed at agents?

Simplest example:

```bash
> cargo agents crate-info serde
Crate: serde
Version: 1.0.228
Source: /Users/nikomat/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228
```

---

# So *why* do Symposium?

???

---

# Coding is going agentic

???

It is my belief that agentic techniques are going here to stay.

---

# Rust is a popular choice

![Headling from ReversingLabs](./images/reversinglabs.com.png)

--

.abspos.top282.left497.arrow.rotate230[![Arrow](./images/Arrow.png)]

--

.abspos.top321.left544.width300px[![What](./images/what.gif)]

---

# Ambitious goals

> My goal is to eliminate every line of C and C++ from Microsoft by 2030. Our strategy is to combine AI *and* Algorithms to rewrite Microsoft’s largest codebases. Our North Star is “1 engineer, 1 month, 1 million lines of code”.<br>
> <br>
> &mdash; [Distinguished Engineer at Microsoft, talking about a research project](https://www.linkedin.com/posts/galenh_principal-software-engineer-coreai-microsoft-activity-7407863239289729024-WTzf/)

???

Here is one example that was sent around a lot recently -- but there are many.

---

# Fundamentals matter more now

| Losers | Winners |
| --- | --- |
| Incumbents | Fundamentals |

???


---

# What makes Rust a good fit?

* Guardrails

--

.p80[![Greg Brockman saying Rust is a great language for agents](./images/greg-brockman-tweet.jpg)]

---

# What makes Rust a good fit?

* Guardrails
* Efficiency

--

.p60.bordered[![Rust win](./images/rust-win-3.png)]

--
.abspos.top283.left105.p60.bordered[![Rust win](./images/rust-win-2.png)]

--
.abspos.top340.left188.p60.bordered[![Rust win](./images/rust-win-1.png)]

---

# What makes Rust a good fit?

* Guardrails
* Efficiency
* Investment in error messages

--

.center.megamoj[🤔]

---

# Error messages?

![Error message from the Rust compiler](./images/error-messages.png)

--

.abspos.arrow.top183.left260.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top163.left302.bordered.purple[The base error]

--

.abspos.arrow.top353.left298.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top341.left341.bordered.purple[Needed context]

--

.abspos.arrow.top441.left244.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top426.left284.bordered.purple[How to fix]

---

# So if Rust is so good...

> Claude is pretty great at Rust as is. I'd be interested to hear more about what you've found it's bad at.<br>
> <br>
> &mdash; a friend of mine, making a comment I've herad a lot

---

# Sure, Claude is good

## But could it be better?

---

# Guardrails

## But could it be better?
