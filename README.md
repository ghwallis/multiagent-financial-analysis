# Financial Analysis Using CrewAI Multi-Agent Systems

This repository contains a Python script, **financial_analysis.py**, that demonstrates a multi-agent system designed to analyze market data, develop trading strategies, and provide actionable insights for financial trading. The script utilizes machine learning models and real-time data analysis tools to assist in decision-making processes for stock trading.


---
### Why use an Agentice Framework?

One may ask why use an agentic framework in the first place? AI agents excel in financial analysis tasks by offering specialization, where each agent focuses on a specific role like data analysis or risk management, ensuring precision and efficiency. Unlike standalone LLMs, agents can dynamically interact, delegate tasks, and go back and forth with other agents to refine responses and manage hierarchical workflows, streamlining complex multi-step processes. Their modular design allows for seamless integration with external tools and APIs for real-time data collection and analysis, while also enabling scalability and reusability across projects. Additionally, agents provide robust error handling, ensuring failures in one area do not disrupt the entire system. These features make AI agents superior for tasks requiring adaptability, collaboration, and precision.

---

## Features
- **Agents:**
  - Data Analyst
  - Trading Strategy Developer
  - Trade Advisor
  - Risk Advisor
- **Tools:**
  - Web scraping tools for real-time data collection
  - Machine learning models for predictive analysis
- **Tasks:**
  - Data monitoring and analysis
  - Strategy development
  - Trade execution
  - Risk assessment

---

## Setup Instructions

### Prerequisites
- Python 3.8+
- Virtual Environment (optional but recommended)
- API keys for:
  - OpenAI (for model management. feel free to use other LLMs)
  - SerperDev (for search tool integration)
- Required libraries (see `requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/financial_analysis.git
   cd financial_analysis
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your `.env` file with the following environment variables:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   SERPER_API_KEY=your_serper_api_key
   OPENAI_MODEL_NAME=gpt-3.5-turbo
   ```

---

### Running the Script
1. Execute the Python script:
   ```bash
   python financial_analysis.py
   ```

2. Monitor the logs and outputs in the console to see the progress and results of each agent.

---

### Output
The script generates comprehensive insights into trading strategies, market trends, and risk assessments. The output includes:
- Data insights and trend analysis for selected stocks.
- Proposed trading strategies and execution plans.
- Risk evaluations and mitigation suggestions.

You can find a sample result file [here](financial_analysis_result.txt).

---

## File Descriptions
- **financial_analysis.py**: Main script implementing the multi-agent system.
- **financial_analysis_result.txt**: Sample output from a script run analyzing AAPL stock data.
- **requirements.txt**: List of required Python libraries.

---

## Demonstration Video

Click the image below to watch the demonstration video:

[![Watch the video](path_to_thumbnail_image)](https://github.com/user-attachments/assets/f861220b-6ed2-4be4-aff5-f0ee76b081d8)



## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
