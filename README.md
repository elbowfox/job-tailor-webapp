# JobTailor - AI Resume & Cover Letter Optimizer

A simple, high-conversion micro-SaaS web app that helps job seekers tailor their resumes to specific job descriptions using AI.

## Problem Solved
Job seekers waste hours customizing resumes for every application. This tool does it in seconds with ATS optimization.

## Monetization (Passive / Low-Touch)
- **Free**: 2 tailors per day
- **Pro**: $9/month or $49/year unlimited + cover letters + multiple versions + LinkedIn optimization
- Payments: Stripe or Lemon Squeezy (add checkout link)
- Target: Job seekers on Reddit (r/resumes, r/jobs), LinkedIn, Product Hunt
- Revenue potential: $2k-10k+ MRR possible with marketing (similar tools exist and make money)

## Tech
- Pure HTML/JS + Tailwind (static, deploy anywhere)
- Client-side AI calls (user provides own API key for privacy/cost control) OR proxy through your backend
- LocalStorage for freemium tracking (upgrade to Supabase for real accounts)

## Deployment
1. Deploy to Vercel, Netlify, or Cloudflare Pages (free)
2. Add custom domain
3. Integrate Stripe Checkout
4. Add privacy policy & terms

## AI Automation
- Can be fully maintained and improved by AI agents
- Add features like bulk processing, industry templates, interview prep later

## Quick Start
Open index.html in browser. For real AI, enter a valid OpenAI API key (gpt-4o-mini is cheap).

**Note**: Direct client-side API key use has security implications for production. Prefer a lightweight backend proxy.
