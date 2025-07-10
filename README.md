AI Financial Coach Agent 💸

The AI Financial Coach Agent is a web-based application powered by Google's Agent Development Kit (ADK) and Streamlit, designed to provide personalized financial advice. It analyzes user inputs (income, expenses, debts) to deliver tailored budgeting, savings, and debt reduction strategies through a multi-agent AI system.


**Multi-Agent System:**

1. Budget Analysis Agent: Categorizes expenses and suggests optimizations.
2. Savings Strategy Agent: Designs emergency fund and savings plans.
3. Debt Reduction Agent: Compares avalanche and snowball debt payoff methods.


**Expense Tracking:**

* Supports CSV uploads and manual expense entry.
* Automated categorization and spending pattern analysis.
* Interactive visualizations (pie charts, bar graphs) using Plotly.


**Savings Recommendations:**

- Emergency fund sizing and automation techniques.
- Goal-based savings allocations with progress tracking.


**Debt Management:**

- Optimized payoff plans with interest savings analysis.
- Visual timelines and actionable recommendations.



🚀 Getting Started

1. Prerequisites

- Python 3.8+
- Google Gemini API key from Google AI Studio
- Dependencies listed in requirements.txt

2. Installation

1. Clone the Repository:
`git clone `
`cd AI_Financial_Coach_Agent`


2. Set Up Environment:Create a .env file in the project root:
`GOOGLE_API_KEY=your_api_key_here`


3. Install Dependencies:
`pip install -r requirements.txt`


4. Run the Application:
`streamlit run ai_financial_coach_agent.py`



📄 CSV File Format
The application accepts CSV files with the following columns:

Date: YYYY-MM-DD format
Category: Expense category (e.g., Housing, Food)
Amount: Numeric transaction amount

Example:
Date,Category,Amount
2024-01-01,Housing,1200.00
2024-01-02,Food,150.50
2024-01-03,Transportation,45.00

Download a template CSV from the application's sidebar.
🛠️ Technologies Used

Python: Core programming language
Streamlit: Web interface framework
Google ADK: Multi-agent AI orchestration
Pandas/Plotly: Data processing and visualization
Pydantic: Structured data validation
asyncio: Asynchronous agent execution

🔒 Privacy & Security

All data is processed locally and not stored.
Secure API communication with Google's services.

📚 Documentation & Support

Project Repository
Report Issues
