# Interview Prep — PM Interview Coaching Skill

A brutally honest AI interview coach that prepares you for product manager interviews through structured coaching, feedback and realistic mock interviews. No participation trophies — just honest "AI" feedback that makes you ready for your next gig.

## What It Does

**Interview Prep** is a Claude Code skill that simulates the interview situation. It's primarly build for product manager preparing for interviews at any company or level.
 
 On top of that, it:

- **Coaches your answers** in real-time with specific, actionable feedback
- **Runs mock interviews** with full interviewer roleplay and debriefs
- **Challenges weak thinking** — e.g., generic answers, missing metrics, unclear tradeoffs
- **Adapts to your company** — all feedback is tailored to the role and company context

 
## Installation

1. **Copy the skill file:**
   ```
   into your Claude directory e.g. ~/.claude/skills/interview-prep
   ```

1a. For Claude Chat or Cowork 
      - Download the skill.md file 
      - go to Chat/Cowork > Customize > Create new skills 
      - Click "+" and "Create Skill", then "upload skill". 
      - Upload the skill.md file

2. **Restart Claude Code** for the skill to appear (not neccessary for Claude Chat or Cowork)

3. **Trigger the skill:**
   ```
   /interview-prep [company name]
   ```
   Or just:
   ```
   /interview-prep
   ```

    Or just:
   ```
   I am interviewing at XYZ. Can you help me prepare? Here's the job posting www.abc.com/jobs
   ```

## How to Use

### Setup (First Time)
When you trigger the skill, it will ask for context:
- **Frameworks you are familiar** (e.g., Oportunity Solution Trees, RICE, Jobs-to-be-Done, Design Thinking, etc.)
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

**Questions?** Contact me via contact@thomaskern.me
