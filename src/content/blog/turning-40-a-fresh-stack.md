---
title: "Turning 40: A Fresh Stack"
date: 2026-04-07
description: "Midlife crisis, but make it developer tooling."
---

People turn 40 and buy a sports car. I deleted my `.zshrc`.

Same energy, different invoice.

I'd been meaning to clean up my setup for years. But "meaning to" is a coping mechanism. Then my birthday arrived, and I thought: if not now, when I'm already in the mood to question everything, then when?

So I did the whole thing. New terminal, new shell, new editor. A full stack rotation, without changing a single line of product code. Very efficient. Very me.

---

## Terminal: Ghostty

I spent a decade with iTerm2. Reliable, configurable, bloated. Split panes, infinite tabs, a preferences panel that loads a plugin for every checkbox. Classic software that grew up to be furniture.

Then I briefly dated Warp. Fast, pretty, AI built in — which I thought I wanted until the AI kept offering to autocomplete my SSH commands. Hard pass.

Ghostty landed and it clicked instantly. Native, GPU-accelerated, no Electron runtime sweating in the background, no subscription tier for the ability to open a new tab. It's a terminal. It does terminal things. That's the whole pitch, and it's enough.

---

## Shell: Fish

My zsh config had plugins I installed in 2017 and never touched since. Oh My Zsh, Powerlevel10k, zsh-autosuggestions, zsh-syntax-highlighting, a `.zshrc` that sources four other files before breakfast. The startup time was fine, technically. The cognitive overhead was not.

Fish ships with autosuggestions. Fish ships with syntax highlighting. Fish ships with a working tab completion that doesn't need a plugin to know what `git checkout` does. The defaults are the good part.

I deleted all the submodules. I deleted `.zshrc`. I deleted `.zprofile`, `.zshenv`, `.aliases`, `.functions`. I deleted the `profiles/` directory that had per-employer shell config accumulated like geological strata.

The replacement is a `config.fish` and a `~/.localrc.fish`. That's it. The fish is happy. I am too.

---

## Editor: Zed

VS Code was my main tool for years. It's good software. But somewhere around the 4 GB RAM mark and the forty-seventh extension doing slightly overlapping things, I started to feel it.

Zed is written in Rust, runs native, opens instantly. No extension marketplace to spelunk, no Electron process farm. It has LSP support, a built-in terminal, AI assistance — and it doesn't feel like it's apologizing for existing.

I keep waiting to miss something from VS Code. So far: nothing I can name.

---

## Agentic Dev

The bigger shift isn't the tools. It's the workflow.

I spend less time writing code by hand and more time describing what I want, reviewing what the agent produces, and steering. Claude Code running in Ghostty, with Fish completions for the CLI flags, editing in Zed when I want to get hands-on. The loop is tight.

At 40, I'm not trying to type faster. I'm trying to think more clearly and delegate the rest. A 20-line function I describe in two sentences and review in ten seconds is more valuable than one I wrote in fifteen minutes and half-reviewed. The craft moved up the stack.

---

## The Thread

Ghostty, Fish, Zed — they don't have much in common on the surface. But the pattern is consistent: native over Electron, defaults over plugins, simplicity over surface area.

Every tool I removed was a tool I didn't have to configure, update, debug, or explain to myself at 11pm when something broke. That's not laziness. That's the accumulated wisdom of someone who has debugged too many shell startup files.

Forty is fine, actually. The stack is cleaner than it's ever been.
