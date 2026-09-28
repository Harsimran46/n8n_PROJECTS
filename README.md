n8n AI Automation Projects

A collection of production-style n8n workflows that automate lead generation, lead qualification, outreach, scheduling, and ad research for marketing and sales teams. Each workflow is exported as an importable .json file.

Built by: Harsimran Singh Saini Portfolio: harsimran.digital

Tech Stack

n8n (self-hosted) · OpenAI / LLM Agents · ElevenLabs · Twilio · Telegram Bot API · Google Sheets · Google Calendar · Google Maps · Gmail · Instagram scraping

Projects at a Glance
#	Workflow	What it does
1	Ad Campaign Researcher	Researches ad campaigns in a niche and turns the findings into insights for planning new campaigns.
2	AI Scoring Agent (Website Form)	Scores leads from a website contact form with AI, stores qualified ones, and alerts the owner on Telegram.
3	AI Telegram Appointment Scheduler	A Telegram chatbot that books appointments, sends a confirmation email, and adds the slot to Google Calendar.
4	Instagram Lead Generator	Finds Instagram accounts by niche and location and saves filtered leads to Google Sheets.
5	Lead Generator using Google Maps	Scrapes local business details from Google Maps into Google Sheets.
6	Lead Scorer	Uses AI to rate and prioritize leads so sales teams focus on the best ones first.
7	Outbound Agent with Twilio	An AI outbound calling agent that contacts leads by voice and logs the results automatically.
Project Details
1. Ad Campaign Researcher

Automates ad research by collecting and analyzing campaigns in a niche. Saves hours of manual research and helps shape better creatives and targeting.

2. AI Scoring Agent (Website Form)

Flow: website contact form → webhook → AI agent sends a confirmation email → second AI agent scores the lead. Low-scoring leads are discarded; qualified leads are saved to Google Sheets and sent to Telegram with full details.

3. AI Telegram Appointment Scheduler

End-to-end booking inside Telegram: conversation → detail confirmation → email confirmation → Google Calendar event. Ideal for clinics, salons, and service businesses.

4. Instagram Lead Generator

Enter a niche and location; the workflow finds relevant Instagram accounts and filters them by minimum followers and/or no website in bio, which makes them ideal targets for web and marketing services. Results are saved to Google Sheets.

5. Lead Generator using Google Maps

Builds targeted local lead lists by keyword and location. Each lead includes business name, address, email, phone number, business type, rating, and review count, saved straight to Google Sheets.

6. Lead Scorer

Filters out low-quality leads automatically using AI, so only leads worth following up on reach the sales pipeline.

7. Outbound Agent with Twilio

Collects customer info through a form, then places an AI voice call (powered by ElevenLabs) that sounds like a real person. The agent gathers the customer's requirements and logs everything in Google Sheets.

How to Use
Install or self-host n8n.
Download any .json workflow from this repository.
In n8n, go to Workflows → Import from File.
Add your own credentials (OpenAI, Google, Telegram, Twilio, ElevenLabs, etc.).
Activate the workflow.
Results
Replaces hours of manual prospecting and follow-up with automated pipelines
Qualifies and prioritizes leads instantly using AI
Connects lead generation, scoring, and outreach into one funnel
Contact

Harsimran Singh Saini 🌐 harsimran.digital
