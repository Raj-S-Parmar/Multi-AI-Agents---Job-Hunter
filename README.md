# Multi-AI-Agents---Job-Hunter
Have difficulties finding the best job opportunity according to your Resume? These AI Agents will help you out.
This repository contains the code and workflow developed as part of a project using CrewAI to automate the process of finding, tailoring resumes, and preparing for job applications.
It can be adapted to various job roles and candidate profiles by customizing the agents and tasks.
The assistant covers key stages of job search and application:
- Searching and scraping job postings from the web.
- Extracting and analyzing job requirements and qualifications.
- Profiling the candidate based on resume, external profiles, and personal write-up.
- Strategically tailoring the resume to improve alignment with job descriptions.
- Preparing interview questions and talking points based on the tailored resume and job requirements.

This modular framework leverages natural language processing and web tools to create a comprehensive job application support system.

## Components

### Agents
- **Job Researcher**: Extracts and analyzes job posting details and requirements.
- **Personal Profiler**: Synthesizes candidate information from multiple sources into a detailed profile.
- **Resume Strategist**: Optimizes the resume to emphasize relevant skills and experiences.
- **Interview Preparer**: Generates potential interview questions and key discussion points.
- **Job Postings Finder and Scraper**: Searches and verifies job listings along with direct application links.

### Tasks
- Analyze job posting URLs to extract key skills, qualifications, and experiences.
- Compile a comprehensive personal and professional profile.
- Align and update the resume based on job requirements and candidate profile.
- Create tailored interview preparation materials.
- Collect and list top relevant job postings with valid application URLs.

### Tools and Libraries
- Web search APIs and scraping utilities for extracting job data.
- PDF text extraction and markdown conversion for resume processing.
- Semantic search tools for resume content.
- Large language model (OpenAI GPT) integration for natural language understanding and generation.

## Setup Instructions
1. Install required Python packages:
2. Set up API keys for OpenAI and the search service (e.g., Serper).
3. Prepare the candidate’s resume PDF in the working directory.
4. Run the provided notebook or script to:
   - Extract and convert resume text to markdown for semantic search.
   - Initialize agents and define tasks.
   - Execute the Crew to automate the job application pipeline.

## Usage
- Customize the agents’ roles and goals for different job types or candidate needs.
- Provide candidate information such as GitHub link and personal summary.
- Specify job search queries relevant to the target roles.
- Run the automation to receive:
  - Tailored resume highlighting relevant skills.
  - Interview questions and talking points customized to the candidate's profile.
  - A list of filtered and verified job postings with direct apply links.

## Output
- A resume updated to align with desired job postings.
- Curated interview questions and discussion topics.
- A markdown file listing relevant job opportunities with application URLs.
