# ChatGPT Clone

A conversational AI web application that replicates the functionality of ChatGPT. Built using Python, Flask, MongoDB, TailwindCSS, and the OpenAI API, this project demonstrates the power of real-time text-based AI interactions with a responsive and modern user interface.

## Features

- **Real-Time Chat**: Engage in conversations with the AI, powered by OpenAI's GPT model.
- **Persistent Chat History**: MongoDB stores chat history for retrieval and analysis.
- **Responsive UI**: Designed using TailwindCSS for a seamless user experience across devices.
- **Scalable Backend**: Flask-based backend ensures modularity and scalability.

## Technologies Used

- **Frontend**: HTML, CSS (TailwindCSS)
- **Backend**: Python (Flask Framework)
- **Database**: MongoDB
- **AI Integration**: OpenAI API (GPT Model)

## How It Works

1. **User Input**: The user types a question in the input field.
2. **API Request**: The question is sent to the backend and checked against the database for existing answers.
3. **AI Processing**:
   - If a match is found in the database, the response is retrieved.
   - Otherwise, the OpenAI API generates a response, which is stored in the database for future use.
4. **Response Delivery**: The AI response is displayed to the user in real-time.

## Installation and Setup

### Prerequisites
- Python 3.x
- Node.js (for managing frontend dependencies like TailwindCSS)
- MongoDB
- OpenAI API Key

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Aaryan004/CHATGPT_CLONE.git
   cd CHATGPT_CLONE
2. Install backend dependencies:
   ```bash
   pip install -r requirements.txt
3. Install frontend dependencies:
   ```bash
   npm install
4. Configure environment variables: Create a .env file in the root directory and add your OpenAI API key:
   ```bash
   OPENAI_API_KEY=your_api_key_here
5. Run the application:
   ```bash
   python main.py 
6. Open your browser and navigate to http://localhost:5001.

## Project Structure
  ```bash
  CHATGPT_CLONE/
  ├── main.py               # Flask application with routes and API logic
  ├── templates/            # HTML files for frontend
  ├── static/               # CSS, JS, and other static assets
  ├── tailwind.config.js    # TailwindCSS configuration
  ├── package.json          # Frontend dependencies
  ├── package-lock.json     # Lockfile for npm packages
  └── .env                  # Environment variables (not included in repo)

