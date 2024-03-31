# Transpose CSV Values using Pandas

This project offers a Python notebook that simplifies the task of transposing CSV data utilizing the Pandas library. It's designed to assist in data transformation efforts, specifically for reshaping CSV data by converting rows into columns or the other way around. The provided notebook includes functionality to load a CSV file from Google Drive or directly via a URL, transpose the DataFrame, and then export the modified data back to a CSV file on Google Drive.

## Prerequisites

- Python 3.x
- Pandas library
- Access to Google Colab (for importing/exporting CSV files via Google Drive)

## Setup

1. **Clone the Repository**: First, clone this repository to your local environment or directly into Google Colab for an easy start with Google Drive functionalities.
2. **Install Dependencies**: Make sure that Pandas is installed. If it's not already set up in your Python environment, you can easily install it using pip: 
```
pip install pandas
```
3. **Google Drive Setup (Optional)**: If your workflow involves Google Drive for importing or exporting CSV files, you'll need to mount your Google Drive within the notebook.

## Usage

1. **Launch the Notebook**: Navigate to the `Transpose_CSV.ipynb` notebook in your preferred environment, such as Jupyter Notebook or Google Colab. 
```
clone https://github.com/arkabyo/Transpose-CSV-Values-using-Pandas.git
```

2. **Loading the CSV File**: Load your CSV into a Pandas DataFrame by either pointing to the file in Google Drive or by providing a URL to the file directly. Ensure to uncomment the appropriate section in the notebook for your choice.

3. **Data Transposition**: The notebook is set up to automatically transpose the DataFrame upon loading your CSV file. To inspect the first 20 entries of the transposed data, run the `new_df.head(20)` cell.

4. **Export the Transposed CSV**: Export the transposed DataFrame to a new CSV file. When utilizing Google Drive, verify that your target folder exists before attempting the export.

5. **Notebook Customization**: Adapt the notebook as needed to fit your specific data handling requirements.

## Contributing

Your contributions are highly appreciated! If you have ideas for improvement or have identified issues, please feel free to open an issue or submit a pull request.
