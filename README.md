# 📊 Vietnamese High School Exam Analysis 2024

A comprehensive statistical analysis of Vietnamese high school graduation exam scores for 2024, featuring data visualization, correlation studies, and performance insights across academic tracks.

## 🎯 Overview

This project analyzes the performance of Vietnamese high school students in their graduation exams, providing insights into score distributions, subject correlations, and comparative analysis between science and social science tracks.

## 📁 Project Structure

```
├── Phan_tich_diem_THPT_2024.ipynb          # Vietnamese analysis notebook
├── Phan_tich_diem_THPT_2024_English.ipynb  # English analysis notebook
├── diem_thi_thpt_2024.csv                  # Raw exam score dataset
└── README.md                               # Project documentation
```

## 📚 Dataset Description

The dataset contains exam scores for **9 subjects** across different academic tracks:

### Core Subjects (Required for all students)
- **Math** (`toan`) - Mathematics
- **Literature** (`ngu_van`) - Vietnamese Literature  
- **Foreign Language** (`ngoai_ngu`) - English/Other foreign languages

### Science Track (KHTN)
- **Physics** (`vat_li`)
- **Chemistry** (`hoa_hoc`) 
- **Biology** (`sinh_hoc`)

### Social Science Track (KHXH)
- **History** (`lich_su`)
- **Geography** (`dia_li`)
- **Civic Education** (`gdcd`)

## 🔍 Analysis Features

### Statistical Analysis
- ✅ Descriptive statistics (mean, median, std deviation)
- ✅ Distribution analysis with skewness measurements
- ✅ Coefficient of variation for score dispersion
- ✅ Missing data analysis

### Visualizations
- 📈 Score distribution histograms with KDE curves
- 📊 Box plots for outlier detection
- 🔥 Correlation heatmaps between subjects
- 📉 Comparative analysis charts

### Track Comparison
- 🧪 Science track (KHTN) performance analysis
- 📖 Social science track (KHXH) performance analysis
- ⚖️ Cross-track correlation studies

## 🛠️ Requirements

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or install from requirements file:
```bash
pip install -r requirements.txt
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd high-school-exam-analysis-2024
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open analysis notebook**
   - For Vietnamese: `Phan_tich_diem_THPT_2024.ipynb`
   - For English: `Phan_tich_diem_THPT_2024_English.ipynb`

5. **Run all cells** to generate the complete analysis

## 📊 Key Insights

- **Score Distributions**: Analysis reveals varying performance patterns across subjects
- **Subject Correlations**: Strong correlations found between related subjects within tracks
- **Track Performance**: Comparative analysis between science and social science students
- **Variability**: Coefficient of variation analysis shows which subjects have the most dispersed scores

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

For questions or suggestions, please open an issue in this repository.

---
*Analysis of Vietnamese High School Graduation Exam Scores 2024*

