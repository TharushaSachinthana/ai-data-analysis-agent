# 📊 AI Data Analysis Agent

An intelligent AI data analysis agent built using the Agno Agent framework and OpenAI's GPT-4o model. This agent helps users analyze their data through natural language queries, making data analysis accessible to everyone regardless of their SQL expertise.

**Key Improvement**: This project uses Pandas for robust data analysis on Windows systems, with full support for CSV and Excel files.

## Features

- 📤 **File Upload Support**: 
  - Upload CSV and Excel files
  - Automatic data type detection and schema inference
  - Support for multiple file formats

- 💬 **Natural Language Queries**: 
  - Convert natural language questions into SQL queries
  - Get instant answers about your data
  - No SQL knowledge required

- 🔍 **Advanced Analysis** (Powered by Pandas):
  - Perform complex data aggregations and filtering
  - Statistical summaries and insights
  - Multi-step data transformations
  - Cross-platform compatibility

- 🎯 **Interactive UI**:
  - User-friendly Streamlit interface
  - Real-time query processing
  - Clear result presentation

## How to Run

1. **Setup Environment**
   ```bash
   # Clone the repository
   git clone https://github.com/TharushaSachinthana/ai-data-analysis-agent.git
   cd ai-data-analysis-agent

   # Install dependencies
   pip install -r requirements.txt
   ```

2. **Configure API Keys**
   - Get OpenAI API key from [OpenAI Platform](https://platform.openai.com)

3. **Run the Application**
   ```bash
   streamlit run ai_data_analyst.py
   ```

## Usage

1. Launch the application using the command above
2. Provide your OpenAI API key in the sidebar of Streamlit
3. Upload your CSV or Excel file through the Streamlit interface
4. Ask questions about your data in natural language
5. View the results and generated visualizations

