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


# Output


<img width="5284" height="2708" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/a3d74378-f88a-44e3-9041-b6afeb590f63" />

<img width="5336" height="2704" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/75f0d562-224a-41ca-a315-3bc93bf36422" />

<img width="5316" height="2740" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/c056f31b-89ca-4f5f-ad4d-84f3b0d70e9e" />

<img width="5356" height="2700" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/6cd4f062-32f7-4427-9033-e3f3ee2bfd54" />

<img width="5244" height="2735" alt="Screenshot (72)" src="https://github.com/user-attachments/assets/f92d4dff-1721-4896-ae30-d2c3d68f5ec7" />

<img width="5240" height="2676" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/0296b6a3-55cc-495d-9537-a581a88ba92b" />

<img width="5332" height="2736" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/b6f3e3ec-f6db-44d8-909d-ff357a0eecd7" />

<img width="5324" height="2736" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/a6e41793-3630-4c61-a6e0-2fd7b64aa2a6" />





