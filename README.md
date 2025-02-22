# FinAI Analyst Pro

**FinAI Analyst Pro** is an advanced AI-powered tool for analyzing financial PDF documents. Built with Streamlit, it integrates Google Gemini for trend analysis and FinBERT for sentiment scoring, delivering actionable insights through an interactive dashboard, visualizations, and a Q&A assistant. Whether you're a financial professional or an enthusiast, this tool simplifies complex financial data interpretation.

## Features
- **PDF Processing**: Extracts text and financial metrics from PDFs while preserving layout.
- **Financial Metrics**: Calculates key ratios (e.g., debt-to-equity, profit margin) from extracted data.
- **AI Insights**: Provides trend analysis via Google Gemini and sentiment analysis via FinBERT.
- **Interactive Visualizations**: Displays financial health with gauges, radar charts, and trend lines using Plotly.
- **Q&A Assistant**: Allows users to ask questions about the report with AI-generated responses.
- **Exportable Reports**: Downloads analysis as JSON files for further use.

## Tech Stack
- **Backend**: Python, PyPDF2, Pandas, Transformers (Hugging Face), Google Generative AI
- **Frontend**: Streamlit, Plotly, Streamlit-Chat
- **AI Models**: Google Gemini (trend analysis), FinBERT (sentiment analysis)
- **Deployment**: Pyngrok for tunneling, Chromium for optional web scraping

## Installation

### Prerequisites
- Python 3.8+
- Google API Key (for Gemini)
- Hugging Face API Key (for FinBERT)
- Ngrok Auth Token (for public deployment)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/finai-analyst-pro.git
   cd finai-analyst-pro
