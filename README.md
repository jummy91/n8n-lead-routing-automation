# n8n Lead Routing Automation

## What this is about

When leads come in, not all of them need the same attention. Some people are ready to buy right now, some are just asking questions, and some are just browsing. Going through every single lead by hand to figure out which is which takes too much time.

This workflow fixes that. You give it a lead's name, company, their message, and how much the deal is worth, and it uses Google Gemini to read through the details and tell you if the lead is Hot, Warm, or Cold.

## How it works

1. Lead information goes in — name, company, message, deal value
2. The data gets formatted
3. Google Gemini reads the lead's message and decides how serious they are, based on things like urgency, whether they want to start immediately, or if they're just casually browsing
4. It gives back one word: Hot, Warm, or Cold

## Why it's useful

Instead of reading through every lead one by one, you instantly know which ones need your attention first. Hot leads get followed up on right away, and you're not wasting time chasing people who aren't ready yet.
