# AI-learning-post-generator-n8n
n8n workflow that automatically generates AI-written learning posts on a schedule and saves or publishes them, with no manual writing
# AI Blogger Auto-Poster (n8n)

An n8n automation that generates blog posts with AI and publishes them automatically, with an email approval step before anything goes live.

## What it does
- Generates a blog post using AI
- Sends an approval email through Gmail
- Publishes the approved post automatically
- Updates a spreadsheet to track each post

## Tools used
n8n, [AI model you used], Gmail, Google Sheets, blogging platform you publish to-> (https://www.mytrendyinfo.com/)

## How it works
1. Trigger: [schedule / manual]
2. AI writes the post
3. Gmail sends an approval request
4. After approval, the post is published
5. The spreadsheet is updated with the post status

## Screenshots
See the `screenshots` folder for the full workflow, the Gmail approval, the updated spreadsheet and the published post.

## How to use
Import the workflow JSON into n8n and add your own credentials (AI, Gmail, Google Sheets, blog platform).

## What I learned
Building end-to-end automation with AI, approval steps and tracking.
