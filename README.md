# YouTube Comments Analysis

Scraped and analyzed 4,500+ comments from a YouTube video using the YouTube Data API v3.

## What it does
- Fetches top-level comments and reply threads
- Cleans text (removes URLs, mentions, emojis)
- Builds a performer mention leaderboard
- Scores engagement (average likes per mention)
- Stores cleaned data in SQL Server

## Output
![Performer Analysis](performer_analysis.png)

## Setup
1. Install dependencies:
