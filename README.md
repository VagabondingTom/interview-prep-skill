# Interview Prep — PM Interview Coaching Skill

A brutally honest AI interview coach that prepares you for product manager interviews through structured coaching and realistic mock interviews. No fluff, no participation trophies—just feedback that makes you ready.

## What It Does

**Interview Prep** is a Claude Code skill that simulates the internal monologue of a skeptical PM interviewer. It:

- **Coaches your answers** in real-time with specific, actionable feedback
- **Runs mock interviews** with full interviewer roleplay and debriefs
- **Challenges weak thinking** — generic answers, missing metrics, unclear tradeoffs
- **Adapts to your company** — all feedback is tailored to the role and company context

Built for product managers preparing for interviews at any company or level.

## Installation

1. **Copy the skill file:**
   ```bash
   mkdir -p ~/.claude/skills/interview-prep
   cp skill.md ~/.claude/skills/interview-prep/
   ```

2. **Restart Claude Code** for the skill to appear

3. **Trigger the skill:**
   ```
   /interview-prep [company name]
   ```
   Or just:
   ```
   /interview-prep
   ```

## How to Use

### Setup (First Time)
When you trigger the skill, it will ask for context:
- **Frameworks** you use (CIRCLES, RICE, Jobs-to-be-Done, etc.)
- **Company context** (recent news, strategy, product metrics)
- **Role description** (paste the job posting)
- **Your background** (relevant PM experience)

The more detail you provide, the better the feedback.

### Two Modes

#### 1. Coaching Mode
You answer a question. The coach responds with:
1. **Strengths** — what worked
2. **Gaps** — what was weak or missing
3. **How to improve** — concrete restructuring advice
4. **Follow-up question** — what a real interviewer would ask next

Best for: practicing specific interview types (product sense, metrics, strategy, behavioral)

#### 2. Mock Interview Mode
Full interviewer roleplay. The coach stays in character, asks follow-ups naturally, and shows realistic skepticism. When you're done, you get a structured debrief covering:
- Structure and clarity
- Depth of thinking
- Handling ambiguity
- Company-specific insights
- Moments where you lost the interviewer
- What a top-tier answer would include

Best for: full interview simulation before the real thing

## Example Usage

```
/interview-prep Google

> You're interviewing for Senior PM, Maps. 
> Provide context: frameworks, role description, your background?

[You provide details]

> Do you want to practice (coaching mode) or mock interview (mock mode)?

> mock interview

[Coach becomes interviewer]
> Tell me about a time you had to make a product decision with incomplete data.
```

## What Makes This Different

- **Brutally honest** — feedback ratio is ~80% constructive, 20% positive
- **Specific, not generic** — challenges vague answers and missing reasoning
- **Interviewer-paced** — feedback mirrors how a real PM interview feels
- **Company-aware** — all coaching is tailored to the company you're interviewing for

This isn't a confidence builder. It's a readiness tool.

## Who It's For

- PMs preparing for interviews at FAANG, startups, or scale-ups
- Career switchers moving into PM roles
- Anyone who wants honest feedback on their PM thinking
- People who'd rather fail in practice than in the real interview

## Requirements

- [Claude Code](https://claude.ai/code) (any version with skill support)
- Internet connection (runs against Claude API)
- 5–10 minutes per session

## License

MIT License — feel free to use, modify, and share.

## Built With

Created with Claude Code and refined through real PM interview prep. Designed to simulate the bar of experienced PM interviewers who've seen hundreds of candidates.

---

**Questions?** This skill works best when you're serious about prep. Use it, get feedback, iterate, and ship.
