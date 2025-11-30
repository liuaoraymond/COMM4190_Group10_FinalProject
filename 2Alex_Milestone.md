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