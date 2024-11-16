# Glimpse-Now---News-Application
# Glimpse Now - News Application

## Overview
Glimpse Now is a Python-based news application that delivers concise, real-time news updates directly to the user’s desktop. With an easy-to-use interface, users can quickly browse summarized news articles and opt to read the full article in their default web browser.

## Features
- **Real-Time News Updates**: Fetches the latest news articles using a public news API.
- **User-Friendly Interface**: Simple GUI built with Tkinter for seamless interaction.
- **Integrated Image Display**: Displays article images alongside summaries.
- **Read More Option**: Directs users to the full article for comprehensive reading.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/Glimpse-Now.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Glimpse-Now
   ```
3. **Install required dependencies**:
   Ensure that you have `Pillow`, `requests`, and `Tkinter` installed.
   ```bash
   pip install pillow requests
   ```

## Usage
Run the application using:
```bash
python News_App.py
```

## How It Works
1. The application fetches news articles using the `requests` library from a specified API.
2. Displays news headlines and images in the Tkinter window.
3. Users can click a button to read the full article in their browser.

## Example API
Ensure you have a valid API key and replace it in the code where necessary:
```python
self.data = requests.get('https://newsapi.org/v2/everything?q=bitcoin&apiKey=YOUR_API_KEY').json()
```
