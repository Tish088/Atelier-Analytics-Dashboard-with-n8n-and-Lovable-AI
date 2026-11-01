# Atelier-Analytics-Dashboard with n8n and Lovable AI
Live Sales Dashboard with Chatbot-Driven Updates

Atelier Analytics is a live dashboard for tracking clients, showpiece orders and revenue. It pulls mock data (for demo) from Google Sheets, and a built-in Chatbot (“Atelier Assistant”) lets users ask questions or make updates in plain language. 
The chatbot sends each request to an n8n webhook, which updates the Google Sheet, and the dashboard refreshes with the new data.
<br><br>
# Problem it solves -
Keeping a dashboard current usually means opening the source spreadsheet and editing it by hand, which is slow and easy to get wrong. This project lets anyone update the data just by chatting, with no spreadsheet skills needed.

<br>

# How does it work?

- The user types a request in the chatbot.
- The request goes to an n8n webhook.
- The n8n workflow processes it and updates the Google Sheet.
- The dashboard syncs and shows the updated numbers.

<br>

# End-to-End Workflow Demo

https://github.com/user-attachments/assets/1e3273bf-201a-4cde-bae8-dbde8cb285de

<br><br>

# Tech stack: 
- n8n (workflow and webhook)
- Lovable (dashboard and chatbot)
- Google Sheets (data source)

<br>

# [NOTE]
All client names and emails are mock data created for demonstration.
