# LLM-Project
# Objective

Convert long historical text (e.g. Wikipedia articles, historical records, biographies) into a structured timeline showing events with dates and descriptions.
# Technologies Used:

Python
NLP/LLM APIs: OpenAI GPT, Google Gemini, or Hugging Face
LangChain (for chaining prompt logic)
Streamlit or Flask (for UI)
Timeline Libraries (e.g. Plotly, TimelineJS, vis.js)
# Workflow:

Input: Historical text (pasted, uploaded, or from a URL)
Text Processing:
Split text into paragraphs/sentences.
Use LLM or regex to extract date-event pairs.
Sort Events: Chronologically sort events by date.
Timeline Visualization:
Create an interactive timeline.
Show [Date | Event | Description].
