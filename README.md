# linkedin-job-description-scrap

===> UPDATED November 29, 2025 <===

## Overview

This project scrapes LinkedIn job listings and generates a wordcloud visualization of the most common requirements for a specific job position. It's a data science study project that helps understand which skills and qualifications are most frequently mentioned in job postings.

## Features

- ✅ Automated LinkedIn login and job search
- ✅ Scrapes multiple pages of job listings
- ✅ Extracts job descriptions
- ✅ Generates wordcloud visualization
- ✅ Exports data to CSV
- ✅ Secure credential management with .env files
- ✅ Automatic ChromeDriver management
- ✅ Comprehensive error handling and logging

## Installation

### Prerequisites
- Python 3.8+
- Google Chrome browser

### Setup

1. Clone this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create your environment file:
```bash
cp .env.example .env
```

4. Edit `.env` and add your LinkedIn credentials:
```
LINKEDIN_EMAIL=your.email@example.com
LINKEDIN_PASSWORD=your_password_here
JOB_POSITION=data scientist
JOB_LOCATION=brazil
```

## Usage

Run the main script:
```bash
python LinkedinScrapping-updated.py
```

The script will:
1. Log into LinkedIn using your credentials
2. Search for jobs matching your position and location
3. Scrape job descriptions from multiple pages
4. Generate a wordcloud image (`wordcloud-job.png`)
5. Export raw data to CSV (`wordcloud-job.csv`)

## Output Files

- `wordcloud-job.png` - Visual representation of most common job requirements
- `wordcloud-job.csv` - Raw job description data

## Important Notes

- **Security**: Never commit your `.env` file to version control
- **Rate Limiting**: LinkedIn may temporarily block access if too many requests are made
- **Compliance**: Use responsibly and in accordance with LinkedIn's Terms of Service

## More Information

Original documentation: link.medium.com/RqNR7YocWib

## Contact

For corrections, suggestions, or questions:
saulodetp@gmail.com


