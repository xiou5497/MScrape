# 📊 MScrape - Find Business Leads on Google Maps

[![](https://img.shields.io/badge/Download-MScrape-blue.svg)](https://github.com/xiou5497/MScrape)

MScrape collects business information from Google Maps. It finds data like names, addresses, phone numbers, and websites for businesses in your area. This tool automates the process of gathering leads. You do not need to write code to use it.

## 🛠 Prerequisites

Your computer needs a few components to run MScrape. 

1. **Windows 10 or 11**: The software works on current versions of Windows.
2. **Python**: This is the engine that runs the scraper. Download it from the official Python website. Ensure you select the option to "Add Python to PATH" during installation.
3. **Web Browser**: Use Google Chrome or Microsoft Edge for the best results.

## 📥 Downloading the Tool

Follow these steps to get the software:

1. Visit the [MScrape repository page](https://github.com/xiou5497/MScrape).
2. Look for the green "Code" button near the top right of the page.
3. Click "Download ZIP".
4. Save the folder to a location on your computer, such as your Desktop.
5. Right-click the downloaded folder and select "Extract All".

## ⚙️ Setting Up Your Environment

Once you extract the files, follow these steps to prepare the tool:

1. Open the folder named `MScrape-main`.
2. Find the file named `requirements.txt`. This file tells your computer what extra tools the scraper needs.
3. Open your Windows Command Prompt. Press the Windows key, type `cmd`, and press Enter.
4. Type `cd` followed by a space, then drag the `MScrape-main` folder into the command window. Press Enter.
5. Type the command `pip install -r requirements.txt` and press Enter. Wait for the computer to finish installing these components.

## 🚀 Running the Application

You are now ready to start scraping data.

1. In the same command window, type `streamlit run app.py` and press Enter.
2. Your default web browser will open automatically. You will see the MScrape interface.
3. Enter your search term, such as "Coffee Shop," and your target city in the provided boxes.
4. Click the "Start Scraping" button.
5. The software will display results on your screen as it finds them.

## 🔍 Understanding the Features

MScrape includes tools to manage your data:

* **Global Search**: Search for any business type in any city. 
* **Geolocation**: The tool automatically maps addresses to coordinates for better accuracy.
* **Email Extraction**: When a business has a website, the tool visits it to find contact email addresses.
* **Blacklist Filter**: You can add specific websites or businesses to a list so the tool ignores them in future searches.

## 📂 Exporting Your Data

After the scraper finishes, you can save your results. Look for the "Download CSV" button on the web interface. This creates a file you can open in Excel or Google Sheets. This file contains all the business details gathered during your session.

## 💡 Common Questions

**Does the tool cost money?**
MScrape is free to use.

**How many leads can I collect?**
You can collect as many as Google Maps allows for your search terms. 

**What if the tool stops?**
If the scraper stops, check your internet connection. Refresh the browser page and restart the process.

**Can I run this on a Mac?**
The current instructions focus on Windows. While the code is Python-based, specific steps for Mac differ.

Keywords: lead generation, google maps scraper, b2b, automation, data extraction, business leads, sales prospecting