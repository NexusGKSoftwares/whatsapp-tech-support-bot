# WhatsApp Technical Support Bot

A WhatsApp chatbot built with Flask and Twilio to handle common technical issues for customers.

## Setup

1. Clone the repository.
2. Create a virtual environment and activate it.
3. Install dependencies: `pip install -r requirements.txt`
4. Add your environment variables to `.env`.
5. Run the app: `flask run`

## Testing
Run `python -m unittest discover tests` to test the bot's functionality.

## Deployment
Set up with a cloud service (like Heroku or AWS) and configure the Twilio webhook to point to `/whatsapp`.
