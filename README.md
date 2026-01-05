# Resume Analyzer FastAPI

Resume Analyzer FastAPI is an API service built with FastAPI to analyze resumes. The API accepts resume files (such as PDF or DOCX) and returns structured information or insights to help understand candidate profiles and skill matches.

Live demo: https://ai-resume-analyzer-zeta.vercel.app :contentReference[oaicite:0]{index=0}

## About

This project implements a backend API for analyzing resumes. It reads and parses uploaded documents and returns extracted data through HTTP endpoints. It can be used as part of a larger system for applicant screening, job matching, or resume parsing workflows.

## Features

- Accepts resume uploads through API endpoints
- Parses resume content and returns text or structured insights
- Built with FastAPI for performance and automatic interactive documentation
- Ready to deploy on cloud platforms that support Python web apps

## Technology Stack

- Python
- FastAPI
- Uvicorn
- Python libraries for PDF/Text extraction (as defined in `requirements.txt`) :contentReference[oaicite:1]{index=1}

