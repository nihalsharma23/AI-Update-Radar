AI Daily Feed Generator (RSS-Based Auto-Filtered Updates)

A simple no-bullshit RSS-powered AI news tracker that keeps you updated only with real AI launches, releases, and feature updates — without marketing noise.

This tool runs directly in Google Colab and generates a clean, clickable HTML report containing only today’s AI updates.

🚀 What This Project Does

✔ Fetches RSS feeds from leading AI sources (OpenAI, Anthropic, Google DeepMind, NVIDIA, ProductHunt AI, arXiv ML/AI, etc.)
✔ Filters results to show only the latest releases, features, and product announcements
✔ Shows only articles published today
✔ Removes marketing fluff, noise, distractions
✔ Outputs a clean HTML file with clickable links
✔ You can add your own RSS feeds
✔ 100% free — no paid tools or APIs

🛠 How It Works (Simple)

You run the Colab notebook

It automatically fetches dozens of AI RSS feeds

It filters news using keywords:

release, update, launch, GPT, LLM, API, beta, integration

It removes noise using negative filters

It checks article publish dates and shows only today’s posts

Generates a Google-Docs-friendly HTML file

You download & read it — done.

📄 Output Format

You get a file:

AI_Today_YYYY-MM-DD.html


Inside it:

Source

Title

Clickable link

Publish timestamp

No ads

No distractions

No bullshit

🔧 Tech Stack

Python

feedparser

dateutil

Google Colab

HTML generation

➕ Add Your Own Feeds

Just edit the feeds = [ ... ] list in the script.

📚 Why This Exists

AI news is exploding.
New models. New launches. New toolkits. New everything.
It's impossible to keep up — and most feeds are full of marketing noise.

This tool helps you:

Stay updated daily

Only see what matters

Avoid FOMO in the AI world

Track real launches, not hype

Discover new tools instantly

🏁 How to Run

Open the Colab notebook

Click Runtime → Run all

Download your daily HTML file

Read it wherever you want
