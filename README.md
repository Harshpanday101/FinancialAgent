# **Agentic AI for Stock Prediction and News Analysis**

This project is an **Agentic AI application** designed to predict stock trends and provide news insights related to stocks. It leverages advanced AI tools like **phi**, **Groq**, and **OpenAI APIs** to combine financial data analysis and contextual decision-making. The project runs on a local server using **phidata**, offering an interactive Playground interface for predictions and searches.

---

## **Features**
- **Stock Prediction**: Analyze stock data and predict trends using AI-powered models.
- **News Insights**: Fetch relevant financial news and contextual information for informed decisions.
- **Interactive Playground**: Access a local web interface to test and interact with the AI models.

---

## **Project Structure**
- **`financial_agent.py`**: 
  - Contains the logic for stock analysis, news retrieval, and predictions.
- **`playground.py`**:
  - Hosts the application on a local server and serves the Playground interface.
- **`.env`**:
  - Stores API keys securely for **PHI**, **Groq**, and **OpenAI** integrations.
- **`requirements.txt`**:
  - Lists all dependencies required to run the project.

---

## **Installation**

### **Prerequisites**
1. Python 3.8 or above.
2. Pip package manager.
3. API keys for:
   - **PHI_API**
   - **GROQ_API**
   - **OPENAI_API_KEY**

### **Setup**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/agentic-ai-stock-news.git
   cd agentic-ai-stock-news
   ```

2. **Set up a virtual environment**:
   - Create a virtual environment:
     ```bash
     python -m venv venv
     ```
   - Activate the virtual environment:
     - On **Windows**:
       ```bash
       venv\Scripts\activate
       ```
     - On **macOS/Linux**:
       ```bash
       source venv/bin/activate
       ```
   - Once activated, you should see `(venv)` at the beginning of your terminal prompt.

3. **Install dependencies**:
   - Use the `requirements.txt` file to install all necessary libraries:
     ```bash
     pip install -r requirements.txt
     ```

4. **Set up the `.env` file**:
   - Create a `.env` file in the project root and add your API keys:
     ```env
     PHI_API=your_phi_api_key
     GROQ_API=your_groq_api_key
     OPENAI_API_KEY=your_openai_api_key
     ```

---

## **Running the Project**

1. **Activate the virtual environment**:
   - Ensure the virtual environment is active before running the project:
     - On **Windows**:
       ```bash
       venv\Scripts\activate
       ```
     - On **macOS/Linux**:
       ```bash
       source venv/bin/activate
       ```

2. **Start the Playground server**:
   - Run the `playground.py` file:
     ```bash
     python playground.py
     ```

3. **Access the Playground**:
   - Open your browser and navigate to the **phidata Playground** on `http://127.0.0.1:7777`.

4. **Use the Model**:
   - Interact with the AI model for stock predictions and news insights directly from the Playground interface.

---

## **Usage Example**
1. **Stock Prediction**:
   - Input a stock symbol (e.g., `AAPL`) in the Playground interface.
   - The AI will fetch live stock data, predict trends, and recommend actions.
     ```plaintext
     Stock: AAPL
     Current Price: $150.50
     Prediction: Buy (Projected increase in the next 24 hours)
     ```

2. **News Insights**:
   - Query for contextual information (e.g., "latest news about Tesla").
   - The AI fetches relevant articles and displays a summary.

---

## **Development Workflow**
- **Testing**:
  - Use the Playground to debug and refine prediction logic.
- **Extending Functionality**:
  - Enhance models in `financial_agent.py` for better accuracy.
  - Add new tools for expanded capabilities (e.g., sentiment analysis).

---

## **Future Enhancements**
- Add cloud deployment options for broader accessibility.
- Integrate advanced portfolio management features.
- Expand API support for international stock markets.

---

## **Contributing**
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Added feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## **Contact**
For any questions or feedback, reach out:
- **Email**: [harshpanday101@gmail.com](harshpanday101@gmail.com)
- **GitHub**: [Harshpanday101](https://github.com/Harshpanday101)

---

