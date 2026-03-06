# Build with AI: Infinite Flight Simulator Starter

This is the starter repository for the **Build with AI: Flight Simulator Workshop**.

## Overview
This template provides the base architecture needed to build an AI-powered flight simulator:
- **Frontend:** A minimalist setup of [CesiumJS](https://cesium.com/platform/cesiumjs/) to render the 3D globe.
- **Backend:** A Python Flask server configured with Google Earth Engine and Vertex AI (Imagen) for terraforming operations.

You will use Gemini to build out the Heads Up Display (HUD), tune the flight physics, implement the terraforming bridge, and manage memory constraints.

## Prerequisites & Setup

Before we write code, ensure your local development environment is ready.

### 1. Local Requirements
You must have the following installed on your computer:
- **Python 3.9+** (Check with `python --version` or `python3 --version`)
- **Git**
- An IDE like **VS Code** or **Cursor**
- The **Gemini Code Assist** extension installed in your IDE, or access to the **Gemini web interface**. Optionally, you can install the **Gemini CLI** if you prefer terminal-based AI.

### 2. Get the Code
Open your terminal (or IDE terminal), and clone this starter repository:
```bash
git clone <your-repository-url>
cd gdg-flight-sim-starter
```

### 3. Open the Codelab (Instructions)
We have a built-in codelab to guide you through the process.
- Open the folder in your IDE.
- Double click or right-click `slides.html` and select **Open in Default Browser** (or use a Live Server extension) to read the instructions side-by-side with your code.

### 4. Install Dependencies (Python)
We need to install the required Python libraries for our backend. It is recommended to use a virtual environment (`venv` or `uv`).
```bash
# Optional: Create a virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`

# Install requirements
pip install -r requirements.txt
```

### 5. Start the Server
*(Note: You will need to complete the Google Cloud Setup steps in the Codelab to generate your `service-account-key.json` and API keys before this will fully work).*
```bash
python app.py
```

### 6. Preview the App
Open your web browser and navigate to:
**[http://localhost:8080](http://localhost:8080)**

---

## Instructions for Gemini (`.gemini/GEMINI.md`)
Please see `.gemini/GEMINI.md` for AI agent instructions on how to interact with this project.
