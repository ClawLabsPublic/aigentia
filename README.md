# Aigentia

> AI-powered marketing agency on autopilot for everyone

## Overview
Aigentia is a full-stack AI marketing agency platform that takes businesses from idea to published content — entirely guided by artificial intelligence. Built on Next.js 15 App Router and powered by Anthropic's Claude models, it's designed for founders and small teams who don't have marketing expertise but need professional-grade results.

## How It Works
Users create a project and feed it context (website, notes, GitHub). Claude AI then extracts that context and generates a tailored marketing strategy, an actionable plan broken into tasks, and specialized content via 108 AI agents covering SEO, copywriting, social media, email, and ads. Content is then scheduled and published via Buffer or direct integrations. A Zustand-powered state layer with Supabase persistence ensures multi-project management stays seamless. Channel tokens are encrypted with AES-256 and never exposed client-side.

The platform offers three automation modes — Manual (AI proposes, you approve), Semi (AI handles routine tasks), and Autopilot (AI decides and acts daily based on real KPIs) — giving users full control over how much they delegate.

## Use Cases
- **Solo founders** launching a product who need a complete marketing strategy without hiring an agency
- **Small businesses** wanting to maintain consistent social media and SEO content at scale
- **Agencies** managing multiple client brands from a single multi-project dashboard
- **Startups** running Google/Meta Ads campaigns with AI-generated creatives and SEO checklists
- **Non-marketers** who want guided, step-by-step marketing execution powered by Claude AI

[🌐 Live site](https://aigentia.app/) · [📄 Project page](https://clawlabs.site/projects/aigentia)

## Features
- 108 specialized AI marketing agents (SEO, copy, ads, email, social)
- AI-generated strategy and actionable marketing plan
- Content Engine with batch generation and multi-platform editing
- Multi-channel publishing via Buffer with visual drag-and-drop calendar
- Three automation modes: Manual, Semi, and Autopilot
- AES-256 encrypted channel connections and monthly AI budget controls

## Tech stack
`Next.js 15` `React 19` `TypeScript` `Tailwind CSS v4` `Zustand` `Anthropic Claude SDK` `Supabase` `Clerk` `Radix UI` `Recharts` `Vercel` `Vitest`

## FAQ

### Can I use Aigentia if I have no marketing experience?
Yes — Aigentia is specifically designed for non-marketers. The platform guides you step by step from creating a project to publishing content, with AI handling the strategy, planning, and content generation along the way.

### How does Aigentia generate a marketing strategy for my business?
You provide context about your business — your website, notes, or GitHub repo — and Claude AI extracts key information to generate a tailored marketing strategy and actionable task-based plan automatically.

### What social media and marketing channels does Aigentia support?
Aigentia supports multi-channel publishing through Buffer and direct integrations, covering social media, SEO content, Google and Meta Ads creatives, and email campaigns from a single dashboard.

### Is my API key and social media account data safe in Aigentia?
Yes. All channel tokens and credentials are encrypted using AES-256 encryption and stored server-side via Supabase. They are never exposed to the client browser.

### Can I manage multiple brands or clients in Aigentia?
Aigentia supports multi-project management, allowing you to manage several brands or client accounts each with their own context, content library, strategy, and AI budget settings.

### How much does it cost to use the AI features in Aigentia?
You control AI spend with a configurable monthly budget per project. You can also choose between model tiers (free, economic, optimized, premium) to balance quality and cost based on your needs.

---

_Project info maintained with [ClawLabs](https://clawlabs.site/projects/aigentia) — an AI-first project manager for vibe coding._
