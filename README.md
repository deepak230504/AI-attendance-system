# AI-Based Attendance Management System

An AI-powered attendance management application using face recognition and voice recognition.

## Features
- Face recognition for student identification.
- Voice recognition for speaker identification.
- Teacher and student portals.
- Subject and classroom management.
- Attendance recording and tracking.
- Supabase database integration.
- Password hashing using bcrypt.

## Technology Stack
- Python
- Streamlit
- Dlib
- NumPy
- Scikit-learn (SVM)
- Librosa
- Resemblyzer
- Supabase
- bcrypt

## Project Architecture
- `app.py` - Main Streamlit application.
- `src/pipelines/face_pipeline.py` - Face recognition pipeline.
- `src/pipelines/voice_pipeline.py` - Voice recognition pipeline.
- `src/database/db.py` - Database operations.
- `src/screens/` - Teacher and student interfaces.
- `src/components/` - Reusable UI components.

## Original Project Credit
Based on the Apna College AI Attendance Project:
https://github.com/shradha-khapra/ai-attendance-project-app

This repository is maintained as a learning and development project.

## Security
Configure Supabase credentials through Streamlit secrets. Never commit actual credentials to GitHub.
