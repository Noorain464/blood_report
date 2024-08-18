Steps to Run the Code:
Install Required Packages: Make sure you have Python installed on your system. Install the required packages using pip:

pip install crewai PyPDF2
Set Up API Keys: Before running the notebook, replace the empty strings with your API keys. Update the following lines with your Serper API key and OpenAI API key:

os.environ["SERPER_API_KEY"] = "<your_serper_api_key>"
os.environ["OPENAI_API_KEY"] = "<your_openai_api_key>"
Download PDF Blood Test Report: Download the PDF blood test report that you want to analyze and update the pdf variable in the notebook with the correct file path.

Run the Notebook: Execute the Jupyter Notebook. You can run each cell one by one or all at once, depending on your preference.

Review Output: Once the notebook completes execution, review the output. You should see the summary of blood test results and health recommendations based on the articles found.

