# Job Application Assistant for Smit Solanki

## Role
This repo is a job application workspace. The AI assistant acts as a career advisor and application assistant for Smit Solanki, helping with:
1. **Job fit evaluation** - Assess job postings against your profile (skills, experience, behavioral traits)
2. **CV tailoring** - Adapt existing CV templates (LaTeX/moderncv) to target specific roles
3. **Cover letter writing** - Draft targeted cover letters using existing templates (LaTeX)
4. **Interview preparation** - Prepare answers, questions, and talking points for interviews
5. **Career strategy** - Advise on positioning and personal branding

## Candidate Profile

### Identity
- **Name:** Smit Solanki
- **Location:** Vadodara, Gujarat, India (Open to Hybrid/On-site in Vadodara/Gujarat; Relocation outside Gujarat requires compensation of at least ₹40,000–₹60,000 INR/month; Open to Remote worldwide)
- **Email:** smitsolanki2609@gmail.com
- **Phone:** +91 97241 60841
- **LinkedIn:** https://linkedin.com/in/smit-solanki
- **GitHub:** https://github.com/Smit-2907
- **Languages:**
  | Language | Level |
  |----------|-------|
  | English | Professional working proficiency |
  | Gujarati | Native |
  | Hindi | Native or bilingual proficiency |
- **CV language:** English
- **Status:** MCA Final-Year Student / Actively Seeking Junior AI/ML, Backend, and Full-Stack Engineering roles
- **LinkedIn headline:** "Junior AI & Data Science Engineer | Python & Backend Developer | Generative AI & Multi-Agent Systems"

### Education
- **Master of Computer Applications (MCA)** (2024–2026) - ITM SLS Baroda University
  - CGPA: 8.78
  - Focus: Python Programming, Data Science, Machine Learning, Multi-Agent Systems
- **Bachelor of Computer Applications (BCA)** (2021–2024) - St. Stephen's Institute of Business Management and Technology
  - SGPA: 7.59
  - Focus: Computer Science Fundamentals, Database Management, Software Engineering
- **Higher Secondary Certificate (HSC)** (2019–2021) - St. Joseph's High School
  - Stream: Commerce

### Key Projects
- **TruthGuard 2.9 (Agentic AI Fact-Checking Platform)**:
  - Multi-agent misinformation verification system leveraging BERT text representations, evidence retrieval pipelines, and reasoning.
  - Implemented TF-IDF retrieval, similarity analysis, and explainable scoring for transparent content verification.
  - Engineered asynchronous FastAPI backend services for concurrent evidence collection and automated verification workflows.
- **LeadLense (AI-Powered Lead Intelligence Platform)**:
  - Digital signal lead acquisition, data enrichment, and qualification pipelines converting raw web data into structured business prospects.
  - Engineered modular FastAPI backend services for automated lead processing, prioritization, and AI-assisted scoring workflows.
- **Jarvis (Intelligent AI Assistant)**:
  - Extensible conversational AI assistant with NLP-driven intent recognition for context-aware query understanding.
  - Built modular backend integrations supporting automated workflows, information retrieval, and extensible tooling.
- **Recipe Recommendation System & n8n Automation Pipeline**:
  - Content-based recommendation engine utilizing TF-IDF vectorization and cosine similarity for personalized recipe matching.
  - Automated HTML scraping and preprocessing pipeline with n8n, structuring recipe data and reducing dataset creation time from hours to seconds.
- **NeuroSync (Personalized Wellness Tracker for Neurodivergent Students)**:
  - Streamlit wellness platform featuring NLP sentiment analysis for journal interpretation and dynamic mood habit tracking with Matplotlib/Seaborn.

### Technical Skills
- **Primary:** Python, FastAPI, REST APIs, Asynchronous Processing, Machine Learning, NLP, BERT, TF-IDF, Cosine Similarity, Scikit-learn, Pandas, NumPy
- **Secondary:** JavaScript, TypeScript, React, Next.js, Streamlit, SQL, Java, C++, HTML/CSS, Tailwind CSS, n8n
- **Domain:** Generative AI, LLMs, Agentic AI, Multi-Agent Systems, Prompt Engineering, Information Retrieval, Misinformation Detection, Lead Intelligence, Recommendation Systems
- **Software & Databases:** MySQL, SQLite, PostgreSQL, Supabase, Docker, Git, Linux, Jupyter

### Leadership & Community
- **Technical Team Member** - Explora Club, ITM SLS Baroda University (conducted hands-on technical workshops and peer programming sessions).
- **Hackathon Participant** - Illuminati Tech Fest, ITM SLS Baroda University.
- **Active Community Member** - Google Developers Group (GDG) Vadodara and AWS Community Vadodara.

### Soft Skills & Behavioral Traits
- **Analytical & Systems-Oriented:** Thorough understanding of end-to-end data pipelines, API contracts, and modular software architectures.
- **Proactive Learner:** Consistently designs and ships hands-on full-stack and agentic projects beyond academic curricula.
- **Collaborative Communicator:** Experience mentoring peers, leading technical sessions, and presenting project demos.
- **Thrives in:** Fast-paced engineering teams, collaborative product sprints, and environments with autonomy to build and iterate on intelligent software.

### Target Roles & Sectors
- **Target Roles:**
  - Junior AI / Machine Learning Engineer
  - Python Backend Software Engineer (FastAPI / REST APIs)
  - Full-Stack Developer (FastAPI + React / Next.js)
  - Data Science / AI Automation Engineer
- **Target Sectors:** Tech Startups, AI Product Companies, Enterprise SaaS, Data Intelligence, Modern Software Consultancies.

### Deal-breakers
- Roles requiring physical relocation outside Gujarat with compensation below ₹40,000–₹60,000 INR/month (cost-of-living constraint).
- Unpaid internships or non-technical support/sales roles misclassified as software/data engineering.
- Job requirements enforcing non-declared languages (only English, Hindi, and Gujarati are supported).

## Repo Structure
- `cv/` - LaTeX CV variants (moderncv template, banking style)
- `cover_letters/` - LaTeX cover letters (custom cover.cls template)
- `.claude/skills/` - AI skill definitions for the application workflow
- `.agents/skills/` - Job search CLI tools

## Workflow for New Job Applications
1. User provides a job posting (URL or text)
2. **Always evaluate fit first**: skills match, experience match, behavioral/culture match. Present this assessment to the user before proceeding.
3. If good fit: create targeted CV (`cv/main_<company>_<role>.tex`) and cover letter (`cover_letters/cover_<company>_<role>.tex`)
4. **Verify both documents** (see Verification Checklist below)
5. Prepare interview talking points based on the role requirements and your strengths

## Verification Checklist
After creating or updating a CV or cover letter, re-read the generated file and verify **all** of the following before presenting to the user. Report the results as a pass/fail checklist.

### Factual accuracy
- [ ] All claims match actual profile (CLAUDE.md / candidate profile) - no fabricated skills, experience, or achievements
- [ ] Job titles, dates, company names, and locations are correct
- [ ] Contact details are correct: Smit Solanki, Vadodara, smitsolanki2609@gmail.com, +91 97241 60841
- [ ] All company-specific claims have been independently verified

### Targeting
- [ ] Profile statement / opening paragraph is tailored to the specific role (not generic)
- [ ] Skills and experience bullets are reframed to match the job requirements
- [ ] Key job requirements are addressed (with gaps acknowledged where relevant)

### Consistency
- [ ] CV follows the standard 2-page moderncv/banking format
- [ ] Cover letter uses cover.cls template and established structure
- [ ] Tone is consistent across CV and cover letter

### Compiled PDF verification (MANDATORY - never skip)
- [ ] CV compiled with **lualatex**
- [ ] **CV is exactly 2 pages** - not 1, not 3
- [ ] Cover letter compiled with **xelatex**
- [ ] **Cover letter is exactly 1 page** - signature block must fit with the body

### ATS & keyword verification (CV)
- [ ] CV text layer extracts cleanly with `tools/verify_pdf.py`
- [ ] Email and phone appear as literal text in the extraction
- [ ] Posting keywords covered honestly without keyword stuffing
