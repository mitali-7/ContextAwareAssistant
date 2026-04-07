### Debales CLI Chatbot

⚙️ Setup Instructions

1. Clone the Repository
git clone https://github.com/your-username/DebalesChatbot.git
cd DebalesChatbot

2. Create and Activate Virtual Environment
Using Conda:
conda create -n debales_env python=3.10
conda activate debales_env

3. Install Dependencies
pip install -r requirements.txt

4. Set Environment Variables
Create a .env file in the root directory following the .env.example format

5. Run Web Scraper
python scraper.py

This will:
Crawl the Debales website
Extract content from multiple pages
Store data in data.txt

6. Run the Chatbot
python main.py

7. Ask it queries