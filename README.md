# Virtual Travel Assistant

A comprehensive virtual travel assistant designed to simplify group tour planning by providing personalized recommendations, real-time itinerary building, and destination insights. This project leverages machine learning to offer tailored travel suggestions, drag-and-drop scheduling, and a smart chatbot for instant support. It is built using **FastAPI** for the backend and **React.js** for the frontend, with integrated APIs like **Google Maps** and **Gemini or Gpt**.

---
## Features

- **Personalized Recommendations**: Tailored suggestions based on user preferences, interests, and budget.
- **Real-Time Itinerary Builder**: Drag-and-drop interface for planning optimized schedules with must-visit attractions.
- **Smart Chatbot**: Provides instant answers to travel-related questions using natural language processing.
- **Budget Estimation**: Predicts costs and offers budget-friendly options.
- **Integrated APIs**: Google Maps for location services, OpenAI GPT for conversational AI.

---

## Tech Stack

- **Backend**: FastAPI, Python
- **Frontend**: React.js
- **Machine Learning Models**: scikit-learn, OpenAI GPT API , Gemini API
- **APIs**: Google Maps, OpenAI GPT
- **Tools**: Docker, Jupyter Notebooks

---

## How to Run the Project

1. **Clone this repository**:
   ```bash
   git clone https://github.com/upadhyayutkarsh2005/Travel-Assistant.git
   cd Travel-Assistant
   ```

2. **Setup the Backend**:
   - Navigate to the `backend` directory:
     ```bash
     cd backend
     ```
   - Set up a Python virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # Mac/Linux or venv\Scripts\activate for Windows
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Start the FastAPI server:
     ```bash
     uvicorn main:app --reload
     ```

3. **Setup the Frontend**:
   - Navigate to the `frontend` directory:
     ```bash
     cd ../frontend
     ```
   - Install frontend dependencies:
     ```bash
     npm install
     ```
   - Start the React.js development server:
     ```bash
     npm start
     ```

4. **Testing**:
   - Test backend APIs using tools like Postman or Thunder Client in VS Code.

5. **Deployment**:
   - For local testing or deployment, use Docker to containerize the application:
     ```bash
     cd deployment
     docker-compose up --build
     ```

---

## Project Timeline

- **Start Date**: Mid-December
- **Owner**: upadhyayutkars2005
- **Progress**: Ongoing development to integrate more features, expand to additional regions, and enhance the real-time collaboration capabilities.

---

## Contributions

Feel free to contribute by:
- Reporting issues.
- Suggesting features.
- Submitting pull requests.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


