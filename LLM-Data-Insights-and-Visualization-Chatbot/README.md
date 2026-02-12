# LLM Data Insights & Visualization Chatbot

## Overview

This project is an interactive web-based chatbot that leverages LLM (Large Language Model) capabilities to provide data insights and generate visualizations from CSV files. Users can upload their own CSV datasets, ask questions or request specific visualizations, and receive both textual insights and dynamic Chart.js charts in response.

Check out the demo video below to see the chatbot in action:

![Demo Video](assets/demo_video.gif)

## Features
- Upload CSV files (up to 10MB)
- Preview the first few rows of your data
- Ask questions or request visualizations in natural language
- Get concise, AI-generated insights about your data
- Automatically generated visualizations using Chart.js (supports line, bar, pie, candlestick, and more)
- View raw LLM JSON responses for transparency
- Modern, responsive UI with Tailwind CSS

## Setup & Usage

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd LLM-Chat-boat
   ```

2. **Open `index.html` or `test.html` in your web browser.**
   - No build step is required; all dependencies are loaded via CDN.

3. **How to Use:**
   - Upload a CSV file using the file input.
   - Enter your question or visualization request in the prompt box.
   - Click "Generate Insights & Visualization".
   - View the AI-generated insights and interactive charts below.

## License

This project is for educational and demonstration purposes. 