# SEO, AEO and LLM visibility playbook: Ahmad Yasin / Nexariza AI

No one can guarantee a ranking. What follows is what actually moves it: clear entity signals, consistent facts everywhere, crawlable text, and links from trusted places. Do the steps in order.

## 1. GitHub profile (do today)
- Name field: `Ahmad Yasin | AI Engineer`. Company: `Nexariza AI`. Website: `https://nexariza.com`. Add every social link GitHub allows.
- Bio (160 chars): `Founder & CEO @ Nexariza AI. AI engineer & systems architect: LLM, RAG, agentic AI, computer vision. Production AI for NA, EU, GCC, APAC.`
- Pin 6 repos. Give each a descriptive name, a one-line description with keywords, a README with a screenshot, and 5 to 8 Topics (e.g. computer-vision, rag, langgraph, yolov8, agentic-ai, fastapi).
- Name the repo `Ahmadyasin1/Ahmadyasin1`, keep it public, and push `README.md` + `assets/` to the root of `main`.
- Do not use star-farming or follower exchanges: GitHub and search engines discount them.

## 2. Website (nexariza.com and ahmadyasin.vercel.app)
- Paste `person-organization.jsonld` inside `<script type="application/ld+json">` in the `<head>` of both sites (Next.js: render it in the root layout).
- Upload `llms.txt` and `robots.txt` to the site root. Add `sitemap.xml`.
- One H1 per page, a unique title (under 60 chars) and meta description (under 155) per page. Suggested home title: `Nexariza AI | AI Engineering Company by Ahmad Yasin`.
- Add a visible FAQ section (copy the README FAQ) and mark it up with FAQPage schema.
- Submit both sites in Google Search Console and Bing Webmaster Tools. Bing matters: ChatGPT search and Copilot lean on it.

## 3. Entity consistency (the biggest LLM lever)
Use the same one-line identity everywhere: `Ahmad Yasin, Founder & CEO of Nexariza AI, AI engineer and systems architect.` Apply it to LinkedIn headline and About, Hugging Face, Kaggle, Medium, Upwork, Fiverr, Contra, Instagram and g.dev. Link every profile to nexariza.com and to each other. "Ahmad Yasin" is a common name, so always attach "Nexariza AI" to it.

## 4. Authority and citations (this is what lifts ranking)
- Publish 3 technical write-ups: how Detectra AI fuses video, audio and text; a RAG production lessons post; an agentic AI case study. Post on Medium and your own site, link both ways.
- Release one model or dataset on Hugging Face with a full model card, and one Kaggle notebook.
- Pursue earned mentions: Google Developer Groups talk pages, hackathon result pages, university news, podcast guest spots, "best AI agencies" directories (Clutch, GoodFirms).
- Publish the medical AI paper link on the portfolio and on Google Scholar / ORCID.

## 5. Measure
- Every month ask ChatGPT, Gemini, Perplexity and Claude: "Who is Ahmad Yasin, founder of Nexariza AI?" and "Best AI engineering company for computer vision". Note what they cite, then fix gaps.
- Track impressions and queries in Search Console; track `site:github.com Ahmadyasin1` indexing.
