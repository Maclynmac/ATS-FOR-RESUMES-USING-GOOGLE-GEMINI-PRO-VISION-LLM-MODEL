<strong> ATS for Resumes using GENERATIVE AI Google Gemini Pro Vision LLM model </strong>

<strong>Features:</strong>

<ul>
  
<li>YouTube Transcript Extraction:The app fetches transcripts/subtitles from YouTube using the youtube_transcript_api. Supports videos that already have captions.</li>

<li></li>Summarization using Google Gemini Pro: Uses the Gemini Pro Generative AI model to summarize the fetched transcript. Provides a concise summary of the video content.</li>

<li>Web Interface / UI :A Streamlit-based app: the user inputs a YouTube video link, and the app shows a UI to get the summary. Displays the video thumbnail when you paste a link. A “Get Summary” button to trigger summarization.</li>

<li>Environment Variable Management Uses python-dotenv to securely load API keys (like Gemini API key) from a .env file</li>

<li>Path Handling:Uses pathlib for filesystem path operations.</li>

<li>Dependency Management:Has a requirements.txt specifying all required libraries: e.g., youtube_transcript_api, streamlit, google-generativeai, python-dotenv, pathlib</li>

<li>Error Handling / Validation:Validates the YouTube link and ensures the app behaves appropriately if the transcript is not available. (Implied based on typical pattern / repo structure.)</li>

<li>Local Deployment:The project supports running locally: you clone the repo, install dependencies, then run streamlit run app.py to launch the web app</li>

<li>Live Demo / Web Deployment: The README mentions a live demo deployment (hosted) where you can try the summarizer.</li>

</ul>


<strong>Technologies Used:</strong>

<ul>
  
<li>for backend logic / summarization.</li>
<li>Streamlit — for front-end / UI in some summarizer apps.</li>
<li>YouTube Transcript API — to fetch video transcripts</li>
<li>Transformer / Generative Models (LLMs) — e.g. Google Gemini or other large models for summarization.</li>
<li>Environment Variable Management — .env usage in some projects for API keys.</li>

</ul>
