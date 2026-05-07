# Post-Evaluation Module
Part of the E-Defense System

Overview
The Post-Evaluation Module is a centralized information management system designed to handle the critical transition between the defense proceedings and final institutional clearance. It automates the collection, consolidation, and processing of evaluation data from panelists and secretaries into a single, standardized official report.

By eliminating manual data entry errors and ensuring consistency through departmental rubrics, the module provides a secure environment where the Research Coordinator manages data integrity via "data-locking," and the Panel Chair issues final verdicts and book-binding clearances.

## Tech Stack
- **Language:** PHP / JavaScript
- **Framework:** Laravel (Backend API) / React (Frontend)
- **Database:** MySQL
- **Architecture:** Layered Service Architecture (Report Generation Service, Consolidation Engine, Access Control)

## Installation Guide

# Clone the repository
git clone https://github.com/Aandreyjiwoo/Post-Evaluation-Module---Quintela.git
cd Post-Evaluation-Module---Quintela

# Install dependencies
composer install       
npm install            

# Set up environment
cp .env.example .env
# Update .env with your local MySQL credentials

# Initialize Database
php artisan migrate --seed

# Run the application
php artisan serve      
npm run dev

## Contributors
| Name | Role |
|------|------|
|Lea Roncesvalles  | Developer / Project Manager |
|Janna Mae Asa     | Frontend Developer / UI-UX Designer |
|Andrey Quintela   | Backend Developer / Database Engineer |
|Dalia Mae Miralles| Developer / Documentation Specialist |
