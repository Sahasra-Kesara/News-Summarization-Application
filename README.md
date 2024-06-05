![Screenshot (270)](https://github.com/Sahasra-Kesara/News-Summarization-Application/assets/121740972/859e3907-cfed-4b9c-8972-60d6a4659fcf)
![Screenshot (271)](https://github.com/Sahasra-Kesara/News-Summarization-Application/assets/121740972/46598874-c1ea-4724-b68d-4ed2a92c5538)
# News Summarization Application

This project demonstrates a complete workflow for summarizing news articles using the Hugging Face transformers library, storing them in a SQLite database using Flask and SQLAlchemy, and displaying the summarized articles within a Jupyter Notebook.

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.6 or higher
- Jupyter Notebook
- pip (Python package installer)

## Installation

1. Clone the repository (if applicable) or download the files.
2. Install the necessary Python packages:

```bash
pip install flask flask_sqlalchemy transformers
```

#Usage
Open Jupyter Notebook
```bash
jupyter notebook
```

 Create a new notebook or open the provided notebook file.

# Copy and paste the complete workflow code into a cell in the Jupyter Notebook

 Run the cell to execute the workflow. The summarized news articles will be printed in the notebook output.

## Project Structure

app.py (optional): If you decide to run the application outside of Jupyter Notebook, you can create an app.py file with the same code.

news.db: SQLite database file where news articles and their summaries are stored.
Customization

Model: The code uses the Azma-AI/bart-large-text-summarizer model. You can change this to any other model available on Hugging Face by modifying the model name in the pipeline initialization.

Database: SQLite database is used for simplicity. You can configure SQLAlchemy to use other databases like PostgreSQL or MySQL if needed.
Contributing

Feel free to submit issues or pull requests if you have any improvements or bug fixes.

## License
This project is licensed under the MIT License.
