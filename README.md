# resume-matching
AI-driven system to analyze and rank resumes based on their relevance to specific job postings.

In this project, we aim to match resumes to a job posting and identify the most relevant resumes using Gen-AI tools in Python. This task simulates a real-world scenario where recruiters need to filter through multiple resumes to find the best candidates for a given job.

The scoring system evaluates resumes based on their match to the job posting criteria. The criteria are weighted according to their importance:
•	Work Experience (50%): Relevance and duration of work experience in software development.
•	Skills (30%): Proficiency in required programming languages and technologies.
•	Education (20%): Level and field of education relevant to the job requirements.
Each resume is scored on these factors using TF-IDF vectorization and cosine similarity, with custom scores for sections like work experience, skills, and education.
Overall matching is also done using cosine similarity and then added to the custom scores.
