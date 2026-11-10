---
name: linkedin-profile-optimizer
description: Rewrites LinkedIn profile sections (headline, About summary, Experience entries, Skills, and Featured recommendations) into polished, keyword-aware text that is ready to paste into LinkedIn. Use this skill whenever the user mentions LinkedIn, their LinkedIn profile, headline, About section, or summary, wants to improve how they show up to recruiters or clients, or shares a resume, profile text, profile screenshot, or LinkedIn PDF export and asks to improve, rewrite, polish, or "optimize" it, even if they never say "LinkedIn" explicitly. Also use it when someone gives only a target job or goal and wants a profile written from scratch.
---

# LinkedIn Profile Optimizer

Turn whatever the person has (a profile, a resume, or just a goal) into rewritten LinkedIn sections they can paste straight into their profile. The deliverable is the rewritten text itself, not a critique. Keep any explanation short, because the person came for finished copy.

## Step 1: Work out what you were given

Inputs vary, so identify which of these applies and read accordingly:

- **Pasted profile text**: use it as is.
- **Screenshot or PDF of a profile**: read it first (see the file-reading and pdf-reading skills if the content isn't already in context). If part of it is cut off or unreadable, say which part and work with the rest.
- **Resume or background description**: treat it as source material and translate it into LinkedIn's format. LinkedIn copy is more personal and more skimmable than resume copy.
- **Target job or goal only**: ask for the minimum needed (current or most recent role, key experience, notable achievements) before writing. A profile built on guesses helps no one.

## Step 2: Pin down the target

Good optimization depends on who the profile is for: the role, industry, and audience (recruiters, clients, peers). Infer this from the material when you can and state your assumption in one line. Ask one short question only if the target is truly unclear and the answer would change the writing.

## Step 3: Write the sections

Rewrite all five sections unless the person asks for specific ones. Reasons for each choice are given so you can adapt to unusual profiles.

**Headline** (about 220 characters max). It appears next to every comment, message, and search result, so it does more work than any other line. Default to "Role | Specialty or value | Proof or niche" rather than just a job title. Offer three options and mark one as recommended.

**About** (about 2,600 characters max). Only the first two to three lines show before "see more", so open with the strongest hook: what the person does and for whom, or a specific result. Write in first person. Then cover what they're good at, a sense of how they work, and one or two proof points. Close with a clear next step (how to reach them, or what they're looking for). Use short paragraphs, since walls of text get skipped.

**Experience entries**. For each role, keep the title and company as given (never alter facts) and write 3 to 5 bullets that lead with a strong verb and show outcome over duty: "Cut onboarding time 30% by..." beats "Responsible for onboarding." Omit "I" in bullets. Give older or less relevant roles fewer bullets.

**Skills**. Suggest the top 3 to pin (the ones the target audience searches for), then up to 15 to 20 more, grouped by type. Favor terms that appear in real job postings for the target role.

**Featured**. You can't write this content, so recommend 3 to 5 types of items worth featuring for this person (a case study, talk, portfolio piece, article, certification) and what to pull from their background.

## Writing rules

- **Tone**: confident and professional by default. Confident means specific and plain-spoken, not boastful. If the person asks for a different voice, follow that.
- **Never invent facts.** When a bullet would be stronger with a metric the person didn't give, write a placeholder like `[X%]` or `[team size]` and list it under "Needs your input" at the end. Fabricated numbers can embarrass someone in an interview.
- **Skip clichés** that recruiters skim past: "passionate," "results-driven," "team player," "guru," "ninja," "think outside the box."
- **Keywords**: work in the terms people in this field would search for, naturally. Keyword stuffing reads badly and hurts credibility.
- **Language**: write in the language the profile is in.
- **Platform fit**: LinkedIn does not render markdown. Inside paste-ready text use plain text only, with "•" for bullets and blank lines for spacing.

## Output format

Use this structure so the person can copy each block cleanly:

```
## Headline
(3 options in code blocks, recommended one marked)

## About
(code block)

## Experience
### [Role], [Company]
(code block with bullets, one per role)

## Skills
Pin these 3: ...
Then add: ...

## Featured
(3 to 5 recommendations)

## Needs your input
(placeholders to fill, facts to confirm)
```

After each section, add one or two lines on the main change and why ("Led with your result instead of your job title so it works in search results"). Skip long explanations.

## Edge cases

- **Early career or thin experience**: lean on projects, coursework, volunteering, and internships, and say so honestly. Never inflate titles.
- **Career changer**: lead with transferable strengths and the direction they're heading, and put the new target in the headline.
- **Gaps or short stints**: don't draw attention to them or invent cover stories. Focus on what each role produced.
- **Sparse or contradictory input**: flag the contradiction and ask, rather than picking one version.
- **Confidential details**: if a bullet might reveal client names or internal numbers, write it in anonymized form (such as "a Fortune 500 retailer") and mention it.
