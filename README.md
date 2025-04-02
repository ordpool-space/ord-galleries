# Ord Galleries

A curated, open-source list of inscribed Ordinal Galleries.

This repository curates a list of **Ordinal Galleries** — inscriptions that group other inscriptions into meaningful collections, directly on-chain.

## Why this repository?

Many existing collections lack an on-chain parent/child relationship and rely solely on off-chain indexing (most notably by platforms like Magic Eden).
**Ordinal Galleries** [were introduced](https://github.com/ordinals/ord/pull/4212) to bring this metadata on-chain — as self-contained inscriptions that describe and reference other inscriptions.

However, it’s difficult to determine:
- Which galleries are **authentic** or **official**
- What **title**, **category**, or **preview image** to use
- Who submitted the data and for what purpose

This repository solves these issues by offering:
- Transparent, pull request-based submissions
- Public review and discussion
- Fully open data under the [CC0 1.0 Universal](LICENSE) license


## How to submit a new gallery

1. Navigate to this page: [New Gallery Submission](https://github.com/ordpool-space/ord-galleries/issues/new?template=gallery-submission.yml)  
2. Fill out the form with the required gallery information  
3. Confirm the CC0 license  
4. Submit the form  

A bot will automatically convert your issue (with the form data) into a pull request that updates the repository.  
Moderators will review the submission and provide feedback if needed.


## How to propose changes to existing galleries

If you'd like to suggest changes (e.g. a corrected title, updated preview, or improved category):

1. Navigate to a gallery file in `galleries/`  
2. Click the **pencil icon** (✏️) in the top right  
3. GitHub will automatically fork the repo and help you create a pull request


**Rules to follow:**
- Fields must remain valid and minimal  
- Avoid deleting existing galleries unless clearly spam or broken  
- Keep descriptions concise and plain-text (no markdown or HTML)


## Philosophy: Replacing Gallery IDs

This project aims to document **established collections as faithfully and permanently as possible**.

Galleries should ideally represent the **state of a collection at the time of mint** — not at an arbitrary later point, and not altered retroactively.
If an existing submission contains only a partial snapshot — for example, **999 out of 10,000** inscriptions — we highly encourage the community to inscribe a **corrected gallery** that includes the **full set**, and then update the existing entry in this repository.
We will therefore **reject any attempts to replace a complete gallery** (e.g. 10,000 inscriptions) with a reduced or modified version (e.g. 999), even if a project later decides to "remove" an inscription (e.g. due to theft or policy changes).

> A Picasso remains a Picasso — even when it’s stolen.  
> The same applies to inscriptions. **Collections should be treated as immutable.**

**Important:** Submissions must be accurate and complete.  
If someone attempts to sneak in unauthorized or unauthentic inscriptions, they will be **permanently banned** from contributing.


## Get involved

This is an open, community-driven project. Everyone is welcome to participate:

- [Submit new inscribed galleries](https://github.com/ordpool-space/ord-galleries/issues/new?template=gallery-submission.yml)
- [Suggest a new category](https://github.com/ordpool-space/ord-galleries/issues/new?template=suggest-category.yml)
- [Propose improvements](https://github.com/ordpool-space/ord-galleries/discussions)
- [Review or moderate pull requests](https://github.com/ordpool-space/ord-galleries/pulls)
- [Suggest new features](https://github.com/ordpool-space/ord-galleries/issues/new)
- [Fork this repository](https://github.com/ordpool-space/ord-galleries/fork) and build something better — but you **must** retain the original license!

Let’s build a decentralized and trustworthy registry of on-chain gallery metadata.


**License:** [CC0 1.0 Universal](LICENSE) — Public Domain Dedication

## [→ Submit a Gallery](https://github.com/ordpool-space/ord-galleries/issues/new?template=gallery-submission.yml)
