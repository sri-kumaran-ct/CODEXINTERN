# CSV Data Analyzer

A beautiful web application for analyzing CSV files using Pandas and creating visualizations with Matplotlib. Upload your CSV files, perform statistical analysis, generate charts, and get insights about your data.

## Features

- 📁 **CSV File Upload**: Drag-and-drop or click to upload CSV files
- 📊 **Data Analysis**: Calculate statistics (mean, median, std dev, min, max) for numeric columns
- 📈 **Visualizations**:
  - Bar Charts for categorical data
  - Scatter Plots for numeric relationships
  - Correlation Heatmaps for numeric columns
- 💡 **Data Insights**: Automatic generation of insights about your dataset
- 🎨 **Modern UI**: Beautiful, responsive design with smooth animations

## Installation:

1. Install Python dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Start the Flask server:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://localhost:5000
```

3. Upload a CSV file using the upload area

4. Explore your data:
   - View dataset information
   - Analyze specific columns
   - Generate visualizations
   - Get automated insights

## Sample Data

A sample CSV file (`sample_data.csv`) is included for testing. It contains employee data with columns: Name, Age, Salary, Department, Experience, and Performance.

## Requirements

- Python 3.7+
- Flask
- Pandas
- Matplotlib
- Seaborn
- NumPy

## File Structure

```
analyze/
├── app.py                 # Flask backend application
├── requirements.txt       # Python dependencies
├── sample_data.csv        # Sample data for testing
├── templates/
│   └── index.html        # Main HTML template
├── static/
│   ├── style.css         # CSS styling
│   └── script.js         # JavaScript for interactivity
└── uploads/              # Uploaded CSV files (created automatically)
```

## Features in Detail

### Data Analysis
- Mean, median, standard deviation for numeric columns
- Count, unique values, most frequent for categorical columns

### Visualizations
- **Bar Charts**: Frequency distribution of categorical data
- **Scatter Plots**: Relationship between two numeric variables
- **Heatmaps**: Correlation matrix showing relationships between all numeric columns

### Insights
- Dataset overview (rows, columns, missing values)
- Statistical summaries
- Correlation analysis
- Data quality observations

