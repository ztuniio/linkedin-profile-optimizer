# linkedin-profile-optimizer

A Claude skill that rewrites LinkedIn profile sections (headline, About, Experience, Skills, Featured) into polished, paste-ready text from a profile, resume, or target job.

Give Claude your profile, a resume, or just the job you want, and get back copy you can paste straight into LinkedIn.

## What it does

- Rewrites your **Headline** (three options, one recommended)
- Rewrites your **About** summary, with a strong opening for the part shown before "see more"
- Rewrites each **Experience** entry as outcome-focused bullets
- Suggests which **Skills** to pin and which to add
- Recommends what to put in your **Featured** section
- Lists anything it couldn't know in a "Needs your input" section instead of guessing

## It never invents facts

If a bullet would be stronger with a number you didn't provide, the skill inserts a placeholder like `[X%]` and tells you to fill it in. It won't make up metrics, titles, or employers.

## Example

*Fictional profile, for illustration.*

**Before**

> **Headline:** Marketing Manager at Brightwave
>
> **About:** Experienced marketing professional with 6 years of experience. Passionate about results-driven campaigns. Team player.
>
> **Experience bullet:** Responsible for managing email campaigns and social media.

**After**

> **Headline:** Lifecycle Marketing Manager | Email & Retention for B2B SaaS | Turning trial users into customers who stay
>
> **About (opening):** I help B2B software teams turn trial users into customers who stay. For six years I've run lifecycle marketing where email, data, and product meet, building the onboarding and retention programs that keep users coming back.
>
> **Experience bullet:** • Rebuilt the onboarding email series for 40,000 trial users, lifting trial-to-paid conversion by [X%]

## Install

1. Download [`linkedin-profile-optimizer.skill`](linkedin-profile-optimizer.skill) from this repo.
2. In Claude (claude.ai or the desktop app), open **Customize > Skills**, add the file, and turn the skill on.
3. Start a chat and try one of the prompts below.

**Claude Code:** copy the `linkedin-profile-optimizer/` folder from this repo into `~/.claude/skills/`.

For current upload steps, see Anthropic's guide: [Create custom skills](https://claude.com/docs/skills/how-to). Menu names can change.

## Try it

- "Optimize my LinkedIn profile" (paste your profile text or attach a screenshot or PDF)
- "Rewrite my LinkedIn About section" (attach your resume)
- "Write me a LinkedIn profile. I'm a nurse moving into health-tech product management."
- "Give me a better LinkedIn headline. I'm a freelance UX designer for fintech startups."

## Tips for best results

- Say who you want to reach (recruiters, clients, peers) and the role or field you're aiming for.
- Include real numbers where you have them: revenue, time saved, team size, growth.
- Check every line before posting. The skill rewrites what you give it, but you know your career best.

## Repo contents

```
linkedin-profile-optimizer/   the skill (SKILL.md)
linkedin-profile-optimizer.skill   packaged file for upload
```

## Contributing

Issues and pull requests are welcome, especially example profiles where the output could be better.

## License

MIT (see `LICENSE`).
