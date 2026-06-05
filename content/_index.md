+++
title = "fluidity"
linkTitle = "home"
description = "fluidity is a local-first desktop workbench for building customized AI-assisted development workflows with projects, workspaces, tiles, and extensions."
menu = "main"
weight = 1
keywords = ["local-first development", "AI-assisted development", "development workbench", "fluidity extensions", "git worktrees", "AI agents"]

[sitemap]
priority = 1.0
changefreq = "weekly"
+++

# <span class="t-typeout" data-typeout aria-label="Your workflow, with fluidity"><span data-typeout-prefix>Your workflow, with </span><span class="t-shimmer" data-text="fluidity" data-typeout-fluidity>fluidity</span></span>

An extendable orchestrator for parallel AI-assisted development workflows.

Free (_coming soon_) and [open source](https://github.com/owenps/fluidity).

<div class="cta-row">
  <button class="button button-disabled" type="button" disabled aria-disabled="true">
    <span class="icon icon-download" aria-hidden="true"></span>
    <span class="label">In Development</span>
  </button>
  <a class="button button-primary" href="https://github.com/owenps/fluidity" rel="me">
    <span class="icon icon-star" aria-hidden="true"></span>
    <span class="label">Star on GitHub</span>
  </a>
</div>

## Why fluidity?

Because your development workflow should belong to you. 

fluidity was born from the simple desire to reduce context switching across multiple applications. Bring the agents, harnesses, and project tools you already use. Give them one local place to work together.

## Built to extend

fluidity is designed so tools can be added without changing fluidity itself.

fluidity ships with a focused core platform, first-party extensions for the basics, and a skill to help you bring in the tools that make your workflow unique.

## Fast by default

Written in Rust for a small footprint and responsive local performance.

## Core primitives

<div class="feature-grid">
  <article class="feature-card">
    <div class="feature-icon feature-icon-branch" aria-hidden="true"></div>
    <h3>Projects</h3>
    <p>Register local project roots and let fluidity remember the Workspaces, Settings, and Extensions that belong to them.</p>
  </article>

  <article class="feature-card">
    <div class="feature-icon feature-icon-copy" aria-hidden="true"></div>
    <h3>Workspaces</h3>
    <p>Keep parallel streams of work separate. Git-backed Workspaces use isolated worktrees by default.</p>
  </article>

  <article class="feature-card">
    <div class="feature-icon feature-icon-menu" aria-hidden="true"></div>
    <h3>Tiles</h3>
    <p>Put terminals, agents, browsers, diffs, and tools into focused movable surfaces.</p>
  </article>

  <article class="feature-card">
    <div class="feature-icon feature-icon-layout" aria-hidden="true"></div>
    <h3>Arrangements</h3>
    <p>Reuse Workspace and Tile layouts with startup actions for common workflows.</p>
  </article>

  <article class="feature-card">
    <div class="feature-icon feature-icon-plug" aria-hidden="true"></div>
    <h3>Extensions</h3>
    <p>Add command-backed Tool Tiles through User Extensions or Project Extensions, with a fluidity extension skill to help create them</p>
  </article>

  <article class="feature-card">
    <div class="feature-icon feature-icon-hotkey" aria-hidden="true"></div>
    <h3>Commands</h3>
    <p>Trigger fluidity actions through stable named Commands from keybinds, menus, automation, and future input sources</p>
  </article>
</div>
