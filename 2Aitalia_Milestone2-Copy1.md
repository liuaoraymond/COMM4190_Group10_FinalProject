### Scenario A

**Scenario:** Graphing Users' Social Network

**Narrative:** The user engages in a casual conversation with Career Compass, sharing recent social interactions. The LLM extracts names, relationship details, and social dynamics to build a personalized ego network. This network helps the user identify potential career allies—mentors, collaborators, or referral sources—based on relationship strength, shared interests, and professional relevance.

**Step-by-Step Interaction**
- User shares stories about recent social interactions
- LLM extracts entities (names, roles, organizations)
- Follow-up questions clarify relationship details and the depth of the connection
- Career relevance scored ("How well does the connection's experience aid the user's?")
- Suggestions offered ("Ask ___ for a portfolio review”, "Is there anyone else ____ can connect you to?").
- Session summary includes updated graph and actionable career suggestions.

**Data Description:**
Data Needed
- User profile (career goals, industries, skills)
- Chat transcript (free-text input)
- Consent and privacy settings
- Relationship heuristics (Helps to identify the depth of relationships)

**Data Created:**

- Career relevance scores
- Suggested actions (e.g., outreach drafts, meeting prompts)
- Logs of data histories
  
**Evaluation:**
- Success Criteria
- Accurate information extraction and relationship inference
- Relevant career suggestions based on network insights

**Potential Complications:**
- Ambiguous names or roles
- Sparse data or ambiguous users
- Sensitive relationships requiring discretion

### Scenario B

**Scenario:** Switching Career Trajectory

**Narrative of Scenario:**
The user engages in a conversational session with Career Compass to explore a shift in their career path. The LLM will prompt dialogue to help the user reflect on past roles and future aspirations. Creating insights from users’ experiences, skills, and emotional tone, LLM will build a personalized career map. In the background, the app constructs a dynamic profile and opportunity graph, identifying skill gaps, transferable strengths, and potential pathways. The conversation identifies mentors, job roles, and actionable suggestions aligned with the user’s evolving goals.

**Step-by-Step Breakdown:**
- User initiates session by expressing interest in changing careers.
- LLM prompts reflection on past roles, motivations, and current challenges
- User shares experiences
- LLM extracts key data: roles, skills, emotional tone, industries, values
- Skill gap analysis performed: compares current skills to target roles.
- LLM suggests pathways with tailored action recommendations
- Session ends with summary and option to continue iterating or move forward with goals.

**Data Description:**
Data Needed
- User input via chat: reflections on past jobs, current feelings, reason for shift, future goals.
- Career history
- Skill inventory: from job descriptions, user statements, or resume.
- Emotional tone: sentiment analysis to detect burnout, excitement, uncertainty.
- Lifestyle preferences: work hours, remote vs. in-person, salary expectations.
- Privacy preferences

Data Created
- Profile graph
- Skill gap report: missing competencies for target roles.
- Suggested pathways: role transitions, learning plans, networking strategies.
- Session logs: transcript, decisions made, edits, timestamps.

**Evaluation:**
- Clarity of recommendations: user understands suggested roles and actions.
- Relevance: suggestions align with user’s stated interests and constraints.
- Emotional resonance: user feels heard and supported.
- Engagement: user continues with follow-up sessions or actions.
- Accuracy: skill gaps and role matches reflect real-world expectations.

**Potential Complications:**
- Ambiguous input: vague statements/goals
- Overwhelm results: too many suggestions or unfamiliar terms.
- Mitigation: use confidence scores, flag uncertain inferences.