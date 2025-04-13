File Converter, Cleaner, Editor, and Visualizer
This File Converter, Cleaner, Editor, and Visualizer is an interactive Streamlit application designed to help users efficiently manage and process CSV and Excel files. The tool offers a range of functionalities for data cleaning, dynamic editing, visualizations, and format conversion. Whether you're working with small datasets or large files, this tool simplifies the process of data manipulation and visualization in a user-friendly interface.

Features
File Upload: Upload CSV or Excel files for processing.

Data Cleaning:

Remove Duplicates: Easily remove duplicate rows from the dataset.

Fill Missing Values: Fill missing numerical values with the mean of their respective columns.

Data Editing:

Interactive Data Editing: Modify the data directly within the app.

Column Selection: Choose which columns to display for further analysis.

Data Visualization:

Chart Options: Visualize your data with various chart types (Bar Chart, Line Chart, and Scatter Plot).

Customizable Axes: Select columns for the X-axis and Y-axis to create tailored visualizations.

File Format Conversion:

Convert the file into either CSV or Excel format and download it directly.

Requirements
The application requires the following libraries:

streamlit==1.42.2

pandas==2.2.3

plotly==6.0.0

openpyxl==3.1.5

altair==5.5.0

How to Use
Upload Files: Click on the file uploader to upload your CSV or Excel files. You can upload multiple files simultaneously.

Edit and Clean Data: After uploading, you can interact with the dataset by:

Removing duplicates

Filling missing values with column means

Selecting specific columns for analysis

Visualize Data: Use the charting options to create various visualizations such as bar charts, line charts, and scatter plots.

Download Processed Files: Convert your file into the desired format (CSV or Excel) and download it by clicking the download button.

How to Run
To run this app locally:

Clone the repository:
git clone https://github.com/TalhaJawaid143/your-repository.git

Install the required dependencies:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

Visit http://localhost:8501 to view the app in your browser.
