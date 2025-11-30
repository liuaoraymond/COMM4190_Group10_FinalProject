# 🧭 Career Compass — AI Career Advisor

## Idea Pitch
Career Compass is an AI-powered career advisor that helps individuals navigate transitions, skill development, and job market opportunities. Using large language models (LLMs), it synthesizes information from job listings, resumes, and skill taxonomies to provide personalized insights. The tool offers resume feedback, skill-gap identification, learning-path recommendations, and mock interview simulations. Unlike static quizzes or keyword job boards, Career Compass holds a reflective conversation to help users craft a coherent professional narrative linking experiences to goals. With a persistent user profile and structured prompts, it delivers targeted suggestions and artifacts (cover letters, interview prep, achievement bullets) that evolve with user input, ultimately reducing uncertainty and accelerating progress toward desired roles.

## Target Users
- **Primary:** College students and early-career professionals exploring or switching paths  
- **Secondary:** Mid-career upskillers and return-to-work candidates  
- **Context:** Unclear goals, time-constrained, need motivation + structure

## What the Application Will Do (Detailed)
1. **Conversational Coaching:** clarify goals, surface strengths, and reframe experiences
2. **Profile & Skill Extraction:** parse resumes/LinkedIn text to structured skills & achievements
3. **Recommendations:** roles to explore, learning paths, projects/portfolio ideas
4. **Artifacts:** resume line rewrites, tailored cover letters, outreach messages
5. **Interview Prep:** mock interviews with adaptive follow-ups and rubric-based feedback
6. **Progress Tracking:** goals, skills, and checkpoints; feedback prompts to refine results

## Data Needed
- **From users:** resume/job history text, goals, industries, skill self-ratings, geographic/constraints
- **From web/other:** job descriptions, skill frameworks (e.g., O*NET), learning resources metadata
- **Handling:** store session/profile locally or in a small DB; prompt-time retrieval; allow export/delete

## Role of LLMs
- Extract structured skills/achievements from unstructured text
- Generate personalized plans, artifacts (cover letters, bullets), and interview questions
- Conduct reflective coaching dialogue; adapt tone; summarize progress
- Tool-use to call retrieval/parsers for resumes, jobs, and learning resources

## Differentiation
- **Vs. non-LLM systems:** goes beyond keyword matching with nuanced, conversational profiling and artifact generation
- **Vs. general LLMs:** persistent profile + domain prompts + guardrails + evaluation rubrics → consistent, task-specific outputs

---

# Usage Scenarios

### Scenario A — Short Description
“From resume dump to skill map & target roles”

**Narrative**  
User pastes a messy resume and says they’re curious about data roles. The app extracts skills, highlights gaps, suggests beginner-friendly titles (e.g., Data Analyst, BI Analyst), and proposes a 6-week learning path with resources and a capstone mini-project. It also rewrites two resume bullets to better reflect impact.

**Step by Step**
- User uploads/pastes resume text + goal (“interested in data roles”)
- LLM parses achievements/skills → creates structured profile
- App compares to role templates → suggests target roles + gaps
- App generates learning path + mini-project + two improved bullets
- User gives 1–5 ratings; app stores feedback + updates plan