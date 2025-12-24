# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

TrueStory is a static marketing website and demo platform for a QA orchestration tool based on the TRACE (Test-linked Requirements And Continuous Evaluation) methodology. The site showcases AI-powered test generation and QA gate workflows.

## Technology Stack

- Pure HTML5/CSS3/JavaScript (no build tools)
- React 18 via CDN (for interactive demos)
- Babel Standalone (JSX transformation in browser)
- Firebase Hosting for deployment

## Deployment Commands

```bash
# Deploy to Firebase Hosting
firebase deploy

# Firebase CLI setup (one-time)
npm install -g firebase-tools
firebase login
```

Firebase project ID: `truestory-dc749`

## Project Structure

All static content lives in `public/`:
- `index.html` - Main landing page with TRACE flow visualization and feature showcase
- `truestory-qa-dashboard.html` - Interactive React-based QA dashboard demo
- `truestory-realistic-simulation.html` - Workflow simulator demonstrating QA gates

## Architecture Notes

**No Build Process:** Edit HTML files directly. All CSS is inline within HTML files. JavaScript animations use Intersection Observer API.

**Design System (CSS Variables):**
- Dark theme: `--bg-primary: #0a0e14`, `--bg-secondary: #151b24`, `--bg-card: #1a2332`
- Accent colors: `--accent-green: #00ff9d` (primary), `--accent-yellow: #ffb800`, `--accent-red: #ff3860`
- Typography: JetBrains Mono, Space Mono, DM Sans (Google Fonts)

**React Demos:** Dashboard and simulator pages load React 18 + Babel via CDN. JSX is transformed in-browser—no compilation step needed.

**Responsive Breakpoint:** 768px for mobile layouts
