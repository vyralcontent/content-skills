[![Stop guessing what to post. Steal from the videos that blew up.](https://raw.githubusercontent.com/vyralcontent/content-skills/main/assets/header.png)](https://vyralcontent.com)

# Vyral Content skills

[![skills.sh](https://skills.sh/b/vyralcontent/content-skills)](https://skills.sh/vyralcontent/content-skills)

A free, open set of Agent Skills for short-form video creators, sponsored by [Vyral Content](https://vyralcontent.com).

We scraped and studied more than 200,000 viral TikToks, Reels, and YouTube Shorts. The patterns that show up again and again in content people save, finish, and share are distilled into the skills in this repo. They plug into the AI you already use: Claude, Cursor, and anything else that supports the SKILL.md standard.

Each skill is scoped to one job: hooks, scripts, captions, ideation, or one specific platform.

## Skills

### viral-short-form

The umbrella skill. Brainstorm and write high-retention short-form video and carousels: generates several diverse hook options from proven patterns, shapes scripts for retention (hook, escalation, payoff, CTA), adapts to the platform you're posting on, and gives an honest read on where a draft loses people. Works across formats: talking head, demo, unboxing, before/after, tutorial, storytime, listicle, carousel, and meme.

Use it when:

- You need a batch of hook options for a video and don't want to stare at a blank page.
- You want a script structured to hold attention through to the payoff.
- You have a draft and want to know where viewers will drop off.
- You want to turn a longer piece into a short-form carousel.

See [./skills/viral-short-form](./skills/viral-short-form).

### viral-tiktok-content

TikTok-specific scripts, hooks, and trend reads. Built around how the FYP actually ranks content: the three signal categories (user interactions, video information, device and account), completion-rate math by video length, trending-sound timing, native features (duets, stitches), TikTok Shop pacing, and the AI disclosure regime.

Use it when:

- You want a script or hook shaped for TikTok specifically, not a generic short-form draft.
- You're deciding if a clip belongs on TikTok or somewhere else.
- You want to read which TikTok trends are worth riding this week.
- You're diagnosing why a TikTok flopped.

See [./skills/viral-tiktok-content](./skills/viral-tiktok-content).

### viral-youtube-shorts

YouTube Shorts strategy with the long-form funnel built in. Covers what the Shorts algorithm rewards now that the Shorts feed runs separately from long-form, how Shorts retention is measured (VVSA, Engaged Views), and the monetization math (Creator Pool, licensed-music revenue split, RPM).

Use it when:

- You want a script tuned for the Shorts Feed, not a TikTok clone.
- You're trying to route Shorts viewers into your long-form videos.
- A Short is flopping and you need to know why.
- You're choosing between music tracks and want to understand the revenue hit.

See [./skills/viral-youtube-shorts](./skills/viral-youtube-shorts).

### viral-instagram-reels

Reels-specific writing, testing, and diagnosis. Sends Per Reach as the metric that buys non-follower reach. Trial Reels for cold-testing before public posting. The Original Content Guidelines (watermark penalty, repost cap, 30-day recovery). The Edits app and the upgraded Reels Insights.

Use it when:

- You want a Reel shaped for cold-audience reach, not just your existing followers.
- You're deciding if a draft is worth testing with Trial Reels first.
- A Reel got reach but no follows and you need to know why.
- You're stuck choosing audio and need to know what your account type allows.

See [./skills/viral-instagram-reels](./skills/viral-instagram-reels).

### viral-hooks

Write and critique the opening 1 to 3 seconds of a short-form video. Hook generation, named-creator archetypes (Kallaway, MrBeast, Hormozi, and others), the three-layer hook (visual + verbal + on-screen text), and the anti-patterns that tank retention before the first cut. Cross-platform.

Use it when:

- You need a batch of hook options and don't want one guess.
- You're picking which hook archetype fits a video idea.
- You want a critique of a draft hook against proven patterns.
- You're trying to fix a weak opening line.

See [./skills/viral-hooks](./skills/viral-hooks).

### viral-short-form-ideas

The ideation engine. The systems prolific creators use to never run out of ideas: pillars and themes, mining (audience comments, Reddit, search autocomplete, competitor outliers), the repurposing engine, and the evergreen-vs-trend balance.

Use it when:

- You're stuck for ideas and need a batch fast.
- You want a content pillar system built for your niche.
- You're trying to turn one idea into five angles.
- You're deciding what to post this week.

See [./skills/viral-short-form-ideas](./skills/viral-short-form-ideas).

### viral-captions-and-ctas

The text layer around the video: captions, on-screen text, hashtags, CTAs, and the pinned comment. The layer that decides whether a good video gets distributed, saved, and sent.

Use it when:

- You need a caption that earns sends and saves, not just likes.
- A CTA is hurting your reach and you don't know why.
- You're wondering what hashtags actually do anymore (and how many to use).
- You want to know if a line is engagement bait before it tanks your video.

See [./skills/viral-captions-and-ctas](./skills/viral-captions-and-ctas).

## Install

```
npx skills add vyralcontent/content-skills --skill <skill-name>
```

For example:

```
npx skills add vyralcontent/content-skills --skill viral-tiktok-content
```

Works in Claude, Cursor, and any agent that supports the SKILL.md standard.

## Want it scoped to your niche?

These free skills work from general patterns across short-form. The premium version, Vyral, runs the same kind of workflows on the same 200,000+ viral video library, narrowed to your specific niche. Every hook and edit comes back cited to the actual source video and ranked by save rate. Check it out [here](https://vyralcontent.com).

## License

MIT. See [LICENSE](./LICENSE).
