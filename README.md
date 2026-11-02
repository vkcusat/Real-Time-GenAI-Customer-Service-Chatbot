# Real-Time Gen AI Customer-Service Chatbot & Emotion Detection

An end-to-end Python customer support pipeline featuring automated session management, real-time emotion detection, Hinglish transliteration keyword parsing, an automated ticketing priority engine, version-controlled RAG document retrieval, and prompt injection security guards.

## 🚀 Project Architecture

*   **Module 1 (Security & Emotion Filters):** Tracks user session lifetimes, calculates emotion metrics, and implements multi-lingual Hinglish word tracking.
*   **Module 2 (Automated Ticketing System):** Creates support tickets and updates priority scores based on user frustration and queue waiting times. Masks user IDs for data privacy.
*   **Module 3 (Knowledge Base Manager):** Tracks version-controlled documents (`v1.0` and `v1.1`), runs an anti-hack prompt guard, and handles system updates or rollbacks.
*   **Module 4 (RAG Retrieval & Vector Engine):** Simulates vector database matching via keyword overlap sets and prints exact document version citations.
*   **Module 5 (System Integration Engine):** Connects all modules into a single, unified execution pipeline function (`end_to_end_customer_pipeline`).
*   **Module 6 (Live App Simulation Terminal):** Runs 4 benchmark test scenarios (Normal, Update, Attack, and Rollback) to verify code resilience.

## 💻 Technical Stack
*   **Language:** Python 3
*   **Libraries:** NumPy, Pandas, Time

## 🛠️ How to Run
1. Open the code in Google Colab or a Jupyter Notebook environment.
2. Ensure `numpy` and `pandas` are imported.
3. Run the consolidated script block cells to view the live terminal UI traces printed to the screen.
