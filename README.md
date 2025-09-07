# 🔍 LangGraph Web Scraper

This is a **web scraper** built using **LangGraph**. It uses 3 interconnected nodes as shown in the diagram below:

![Node Diagram](output.png)

## 🧠 Node Structure

1. **Node 1**: Uses **Tavily API** for advanced web search and scraping.  
2. **Node 2**: Uses **YouTube Data API v3** to search and fetch relevant video content.  
3. **Node 3**: Formats the collected data into a clean, structured diagnostic report.

---

## ⚙️ Environment Setup

Create a `.env` file in your project root with the following keys:

```env
TAVILY_API_KEY="your_tavily_api_key"
OPENAI_API_KEY="your_openai_api_key"
YOUTUBE_API_KEY="your_youtube_api_key"
