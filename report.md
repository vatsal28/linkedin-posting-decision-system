# LinkedIn Posting Decision System - Vatsal Mishra
Date: 2026-07-28
Purpose: A repeatable system for deciding WHAT to post, WHEN, and HOW, tuned to Vatsal's actual goals. This builds on (does not replace) the canonical strategy in `memory/social-linkedin.md`.

Inputs this is tuned to:
- Goal: peer credibility among AI builders + long-term independence. Authority on building and practical AI use. Audience/sponsors are a byproduct, not the target.
- Cadence: 2-3 posts/week sustainable.
- Depth: concrete detail without PII. LinkedIn stays accessible; deep technical material goes to X.

---

## 1. The candid positioning verdict

There is a tension in your stated goal that needs resolving first, because it decides everything downstream:

**You want AI-builder peer credibility, but LinkedIn's audience (per your own strategy) is professionals, analysts, PMs, and AI-curious non-builders. Builders live on X.**

Here is the resolution, and it is genuinely your biggest edge:

**On LinkedIn, builder credibility does not come from technical depth. It comes from evidence of building embedded in accessible posts.**

The LinkedIn AI commentary space is saturated with people who read announcements and write takes. Almost none of them have shipped anything. When you write "I moved one of my automations to the new model this morning, here is what actually changed," you are instantly in a different category from 95% of AI posters, even though the post itself is plain English. Builders who see it recognize you as one of them. Professionals trust you because you clearly are not guessing.

So the identity on LinkedIn is: **"the person who actually runs the thing before telling you what it means."** Not the deepest technical voice (that is X), not the fastest news voice (you cannot win that race and should not try). The tested-it voice.

This also serves the independence goal directly. Independence needs an audience that trusts your judgment enough to follow you anywhere (newsletter, product, course, whatever comes later). Trust compounds from a consistent pattern of "he said X, he showed evidence, he was right," not from volume.

**Practical implication: every LinkedIn post should contain at least one artifact of real building.** A number you measured, a thing that broke, a screenshot of output, a cost figure, a before/after. If a post has zero first-hand evidence, it is either a genuine opinion you can defend from experience, or it does not go out. This is already your "real examples and real numbers or it does not go out" rule; I am elevating it from a quality bar to the core positioning strategy.

---

## 2. On cadence: post 2-3/week, and do NOT go daily

You said daily is possible with assistance. Recommendation: don't.

- Daily posting with AI assistance is precisely how feeds fill with competent, forgettable slop. Your differentiation is evidence, and you cannot generate real evidence daily. You would end up padding with takes, and takes-without-evidence make you look like every other AI commentator, which actively erodes the "he actually builds" signal.
- The LinkedIn algorithm does not reward daily over 3x/week for accounts your size. Comment reach and post quality matter far more.
- Your auDHD reality: a daily commitment becomes a guilt treadmill the first week energy dips. 2-3/week with a bank of drafts is antifragile; daily is brittle.

**The system: 2 posts/week is the floor, 3 is a good week, daily commenting is the actual daily habit.** Comments are where "daily presence" lives, and a substantive comment on a big post regularly out-reaches an original post at your follower count. Treat commenting as your daily reps and posting as your 2-3 weekly "at-bats."

---

## 3. Content pillars and the weekly mix

Four pillars, weighted for your goals. These map onto the canonical content types but with explicit ratios for a 2-3/week cadence.

**Pillar A: "I ran it" (40-50% ~ 1 to 1.5 posts/week). The flagship.**
News, model launches, and tools reacted to through hands-on testing, plus build learnings from your own projects (agents, automations, self-hosting, FakeOut, OpenClaw-style assistant work). What you expected, what happened, what it means for the reader. This pillar IS the positioning.

**Pillar B: Plain-English mental models (25-30% ~ every week or two).**
Concept breakdowns (agents, evals, context windows, RAG, why detectors fail) always tied to a consequence for a working professional. This is where carousels live. These are your compounding assets: they get saved, shared, and found weeks later, and they are what makes "authoritative on practical AI use" stick.

**Pillar C: Judgment posts (15-20% ~ every other week).**
Opinions, frameworks, and contrarian takes you can defend from experience. "How I decide whether a new model is worth switching to." "Why most AI automation advice fails for normal people." Only when you genuinely believe it. These posts are what make people follow YOU rather than the topic.

**Pillar D: Trust lens (10% ~ 2-3 posts/month max, often merged into A or B).**
Deepfakes, AI scams, what platforms can and cannot detect. Your unfair advantage as a lens, never the identity. Best deployed when news makes it timely (a new image/video model ships = a trust-lens angle exists that only you can write credibly).

A good fortnight at 2-3/week looks like: two Pillar A posts, one Pillar B carousel, one Pillar C or D post, daily comments throughout.

---

## 4. The idea-to-post routing rubric

This is the repeatable decision framework. Run every idea (news item, shower thought, build moment) through these gates in order. It should take under a minute.

**Gate 0 - Evidence check: "Do I have, or can I cheaply get, first-hand evidence?"**
- Have it (I built/ran/measured something relevant) → proceed.
- Can get it in under an hour of playing with the thing → get it first, then proceed. This hour is the single highest-leverage hour in your whole content system.
- Cannot get it and it is pure commentary → do not post. Leave a substantive comment on someone else's post instead, or skip entirely.

**Gate 1 - Platform check: "Can a non-builder professional walk away with something usable?"**
- Yes, in plain English → LinkedIn.
- Only builders care (architecture, code, config, benchmarks-for-their-own-sake) → X. Optionally, the accessible LESSON from it becomes a separate LinkedIn post later. Never the same text on both.
- Both audiences care → write two different posts. X gets the how, LinkedIn gets the so-what.

**Gate 2 - Differentiation check: "Will 50 other people write essentially this post?"**
- If yes: what do I have that they don't? Valid answers: my own test results, my own numbers, my T&S lens, a genuinely contrarian read I can defend, a builder's cost/workflow angle. Pick one and make it the spine of the post.
- If no differentiated angle exists → comment, don't post.

**Gate 3 - Pillar and format assignment:**
- Tested something / built something → Pillar A → text post (default) or short native video if it only works shown.
- Explaining a concept with 4+ distinct beats → Pillar B → carousel. Fewer beats → text post.
- Opinion or framework → Pillar C → text post with a hard hook.
- Trust/safety angle → Pillar D → text post, occasionally carousel.

**Gate 4 - The one-line test:** write the hook first. If the first line does not create tension or promise a payoff standing alone, the idea is not ready. Park it in the idea bank rather than forcing it.

**Kill criteria (any one kills the post):**
- No first-hand evidence AND no defensible experience-backed opinion.
- You would be embarrassed if a strong engineer you respect read it.
- It requires PII, confidential Google detail, or an overclaim to be interesting.
- It is a recap. If removing your name changes nothing about the post, kill it.

---

## 5. The news-to-post system (the Gemini/Claude launch playbook)

Model launches are the most crowded moment in AI content. Everyone posts the same three things within 6 hours: the benchmark screenshot, the "this changes everything" take, and the feature list. You cannot and should not compete there.

**Your play: concede the first 24 hours, own the "so what actually" window (24-72h).**

The repeatable sequence when a major launch drops:

**Hour 0-2: Comment, don't post.** Go leave 2-3 substantive comments on the big launch posts from large accounts. This is where the attention is concentrated, comments are cheap, and a sharp comment ("tested it on X, the interesting part is actually Y") gets you profile visits at the exact moment people are searching for signal amid noise. This also warms your account per your engagement playbook.

**Hour 2-24: Run the test.** Spend 30-60 minutes putting the new model into something REAL that you already run: one of your automations, an agent task, a FakeOut-adjacent detection probe, a writing task you do weekly. Not a toy prompt. The goal is one concrete observation nobody else will have, because nobody else has your setup. Capture numbers: cost, latency, where it failed, what changed vs the old model. (I can run structured comparisons for you and hand you raw results; the observations and take stay yours.)

**Hour 24-72: Post the differentiated piece.** By now the recap wave has crested and the feed is hungry for actual signal. Your post opens with the evidence, not the news. The news gets one line of setup at most; assume the reader already saw the announcement.

**The five lenses that are yours** (pick ONE per post, never stack them):
1. **The swap test:** "I moved a real workflow to the new model. Here is what changed, what didn't, and whether you should bother." Uniquely credible because you run real automations daily.
2. **The cost/economics lens:** what the pricing actually means for a team or normal user in money terms. Your analytics background makes you better at this than most builders.
3. **The trust lens (when it fits):** what a new capability means for scams, fake media, or what platforms can detect. When an image/video model launches, you may be the only person in your readers' feed with actual T&S credibility. Use sparingly, hit hard when you do.
4. **The "what they didn't say" lens:** announcements are marketing. What is conspicuously missing or hedged, and what that tells you. Requires reading the actual release notes/system card, which almost nobody does.
5. **The decision framework lens:** zoom out from this launch to "here is how I decide whether ANY new model is worth my time." Evergreen, reusable across every future launch, and pure Pillar C authority.

**The launch decision in one line: if you cannot run the test within 48 hours, use lens 4 or 5 or just comment. Never post lens-less launch commentary.**

---

## 6. Concrete example angles and hooks: a new Gemini/Claude launch

Assume a hypothetical "Gemini 3.5" or "Claude Opus 5" drops this week. Seven angles, each with a hook that lands alone before the fold. All need your real results filled in; the `[NEED]` markers follow your no-fabrication rule.

**1. The swap test (Pillar A, lens 1) - the default play**
> Hook: "I gave the new Gemini the same task that broke the old one. It broke in a new place."
> Body: the one real task, where the old model failed, where the new one failed differently, the one thing it now does well, verdict on whether a normal team should care. `[NEED: actual task + failure]`

**2. The 20-minute migration (Pillar A, lens 1)**
> Hook: "Switching one of my automations to the new Claude model took 20 minutes. Deciding whether to keep it there took two days."
> Body: what "upgrading" actually involves for a real workflow, what you measured before keeping it, the quiet regression nobody mentions. Teaches professionals that model choice is a decision process, not a default. `[NEED: real migration + numbers]`

**3. The cost translation (Pillar A/C, lens 2)**
> Hook: "The new model is 30% cheaper. For most people reading this, that saves almost nothing. Here is who it actually matters for."
> Body: translate per-token pricing into real monthly figures for a normal user, a power user, and a team running automations. Use your own bills as the anchor. `[NEED: your actual usage costs]`

**4. The trust lens, image/video launch edition (Pillar D, lens 3)**
> Hook: "The new image model is genuinely impressive. It also just made one more piece of scam-detection advice obsolete."
> Body: one specific tell people were taught to look for that no longer works, what still holds, the practical rule going forward. Do not overclaim detector accuracy in either direction. `[NEED: the specific obsolete tell, verified yourself]`

**5. What the announcement didn't say (Pillar C, lens 4)**
> Hook: "I read the full release notes for the new Gemini so you don't have to. The interesting part is what's missing."
> Body: one hedge, omission, or fine-print detail (context limits, rate limits, eval that wasn't reported) and what it signals. Requires genuinely reading the docs. `[NEED: the actual omission]`

**6. The evergreen framework (Pillar C, lens 5) - best when you're late or busy**
> Hook: "A new model launches every month now. Here is the 3-question test I run before switching anything."
> Body: your actual test (e.g. does it fix a failure I currently have; does the switch cost under an hour; does it survive a week on a real workflow). Works for every launch forever, and repositions you above the news cycle. Strong carousel candidate.

**7. The anti-hype calibration (Pillar C, contrarian)**
> Hook: "Every model launch gets called a game changer. I have switched daily-driver models twice in two years. Here is what actually made me switch."
> Body: your real switching history and what drove it. Implicitly tells the reader most launches don't matter for them, which is a trust-building thing almost nobody in the AI feed will say.

Best default when energy is normal: angle 1 or 2. When busy: 6 or 7 (no testing needed, defensible from existing experience). Image/video launch: 4 becomes near-mandatory because it is uniquely yours.

---

## 7. Format mapping (which format for what)

- **Text post with hard hook: the workhorse.** 120-220 words, default for Pillars A, C, D. Evidence in the first three lines, ends with a specific question.
- **Carousel (PDF, locked visual system): Pillar B and frameworks.** Every 1-2 weeks, per existing strategy. Reserve for ideas with 4+ distinct beats. These are your durable "authority assets"; the launch-week framework (angle 6) is a perfect carousel.
- **Short native video (30-90s): only when showing beats telling.** A screen capture of the new model failing/succeeding at your real task is stronger than describing it. Higher effort; do not force it, but one strong demo video per launch cycle punches above its weight.
- **Polls: near-zero.** They dilute the tested-it positioning. Only if the options themselves teach something.
- **Comments: the daily channel.** During launch weeks, comments do more for you than posts in the first 24 hours.

---

## 8. What to avoid (your specific failure modes, beyond the canonical list)

The canonical don'ts stand (recaps, cross-posting, slop, em dashes, emojis, confidential Google detail, FakeOut overclaims). Additions specific to your goals:

- **Assisted-daily temptation.** Covered above. Volume without evidence burns the exact credibility you are building.
- **Drifting technical because builders are your target.** The builders you want respect reach + clarity + proof of shipping. They do not need LinkedIn to be your GitHub. When you feel the pull to go deep, that is an X thread, with the accessible lesson recycled to LinkedIn later.
- **Racing the news.** First-hour launch posts are a losing game for you and they force lens-less commentary. Your window is 24-72h.
- **T&S as a crutch.** When a post is weak, the temptation is to sprinkle "as someone in Trust & Safety" for authority. Per your own positioning note: it is a lens, not the identity, and invoking it without substance cheapens it for when it counts.
- **The half-built confession trap.** Build-in-public honesty is good; a feed of "I started X and abandoned it" is not the authority signal you want. Post learnings when there IS a learning, including from failures, but frame around the transferable lesson, not the abandonment.
- **Engagement-bait questions.** Ending with a real, specific question is the rule; "What do you think? 👇" energy is banned.

---

## 9. The weekly operating rhythm (with my role)

**Daily (10-15 min):** 3-5 substantive comments on AI/building/tech-career posts. I can surface candidate posts and draft comment angles; your voice, your final wording.

**Idea capture (continuous):** anything passing Gate 0-2 goes into an idea bank with its pillar tag. A dead-simple `LI:` message in Discord `#content-studio` per the existing flow. I maintain the bank and flag when a pillar is starving.

**Twice a week (the 2-3 posts):**
1. Pick from the bank, biased by pillar ratios (Section 3).
2. If it needs a test, run it (or hand me the mechanical part: comparisons, cost math, timing measurements; observations and take stay yours).
3. I draft via `linkedin-post-builder` (2 hooks, body, visual concept). You edit until it sounds like you said it over coffee.
4. Warm-up comments, post, reply to every comment in the first 60 minutes.

**Launch weeks:** the Section 5 playbook overrides the default rhythm. One launch post max per launch; resist the multi-post pile-on.

**Monthly (15 min):** which posts earned profile follows from people you respect? That is the metric for the peer-credibility goal, not impressions. Double down on whatever earned those.

---

## 10. The whole system on one card

1. Evidence first: no first-hand artifact, no post (comment instead).
2. Accessible always: builders respect clarity + proof; depth goes to X.
3. 2-3/week posts, daily comments. Never assisted-daily.
4. Pillars: I-ran-it ~45%, mental models ~30%, judgment ~15%, trust lens ~10%.
5. News: concede hour 0-24, own 24-72 with one lens (swap test > cost > trust > omissions > framework).
6. One lens per post. Hook must land alone. Real numbers or `[NEED]`.
7. Metric that matters: follows and replies from people you'd want to build with, not impressions.
