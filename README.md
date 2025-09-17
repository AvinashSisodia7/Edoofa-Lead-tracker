# Edoofa-Lead-tracker
The prototype includes an AI Lead Summary Generator that simulates processing counselor notes from WhatsApp conversations.

# How This Solution Works:
Data Fetching: The script connects to Google Sheets API to retrieve lead data (simulated in this demo).

WhatsApp Integration: Simulates conversations with leads to extract key information:

Last conversation notes

Course interest level

Parent objections

Next action items

Lead Tracking:

Updates lead stages based on conversation outcomes

Tracks stage update dates and last conversation dates

Calculates days since last update

Stuck Lead Detection: Identifies leads that haven't been updated for more than 7 days

Analytics & Reporting:

Provides funnel visualization by stage

Calculates conversion rates by counselor

Generates insights about pipeline leaks

Google Sheet Updates: Updates the sheet with all the required fields

Implementation Notes:
For a real implementation, you would need to:

Set up Google Sheets API credentials

Integrate with WhatsApp Business API

Use NLP/AI to analyze conversation content

The system can be enhanced with:

Automated alerts for stuck leads

Dashboard for real-time funnel visualization

AI-powered conversation analysis for better objection handling

This solution addresses the core business problems:

Prevents leads from going cold through automated tracking

Provides complete context to leadership

Offers real-time funnel visibility

Identifies pipeline leaks and counselor effectivenes
