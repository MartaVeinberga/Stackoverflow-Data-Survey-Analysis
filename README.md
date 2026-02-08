# Stack Overflow Developer Survey Analysis: Data Professionals 2020-2025

An in-depth analysis of data professionals' trends, salaries, and preferences using Stack Overflow's annual Developer Survey data from 2020 to 2025.

> **📊 Includes PDF Presentation**: "Is This the Right Time to Study Data Science?" - Comprehensive insights into the current state of the data science field and career opportunities.

## 📊 Overview

This project analyzes over **49,000 responses** from the 2025 Stack Overflow Developer Survey, with a specific focus on **2,900 data professionals** across seven key roles:

- Data Scientist
- AI/ML Engineer
- Data Engineer
- Data or Business Analyst
- Financial Analyst or Engineer
- Database Administrator or Engineer
- Applied Scientist

The analysis is accompanied by a comprehensive PDF presentation that synthesizes key findings to answer: **"Is data science still a promising career path in 2025?"**

## 🎯 Key Findings

### 2025 Insights

- **Geographic Distribution**: Analysis of data professionals across 177 countries
- **AI Impact**: Most data professionals are not concerned about AI threatening their jobs
- **Programming Languages**: Python dominates with the highest usage among data professionals
- **Remote Work**: Comprehensive salary analysis across remote, hybrid, and on-site arrangements
- **Industry Trends**: Top 10 industries employing data professionals with compensation insights

### Historical Trends (2020-2025)

- **Salary Growth**: Median salary trends for data professionals over 6 years
- **Career Progression**: Compensation patterns across different experience levels

## 📑 Presentation: Is This the Right Time to Study Data Science?

The included PDF presentation (`presentation.pdf`) provides comprehensive insights into:

- **Current market demand** for data professionals
- **Salary trends** and earning potential
- **AI impact** on data science careers
- **Skills and technologies** in demand
- **Industry outlook** and future opportunities
- **Career pathways** in data science

This presentation synthesizes the survey findings to help aspiring data scientists make informed decisions about entering the field.

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Plotly Express** - Interactive data visualizations
- **Jupyter Notebook** - Analysis environment

## 📁 Project Structure

```
├── Stack-overflow-datasets/
│   ├── 2025 Stack Overflow Survey Results.csv
│   ├── 2024 Stack Overflow Survey Results.csv
│   └── ... (2020-2023 datasets)
├── analysis.ipynb
├── presentation.pdf          # "Is This the Right Time to Study Data Science?"
├── requirements.txt
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Install required packages using the provided requirements file:

```bash
pip install -r requirements.txt
```

Or install manually:
```bash
pip install pandas plotly jupyter notebook
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/stackoverflow-data-analysis.git
cd stackoverflow-data-analysis
```

2. Download the Stack Overflow Developer Survey datasets from [Stack Overflow's official survey page](https://survey.stackoverflow.co/) and place them in the `Stack-overflow-datasets/` folder.

3. Run the Jupyter notebook or Python script to generate visualizations.

## 📑 Presentation

A comprehensive PDF presentation (`presentation.pdf`) is included, answering the key question:

### **"Is data science still a promising career path in 2025?"**

The presentation covers:
- **Salary Trends**: Continuous growth in data professional compensation
- **AI Impact**: Survey insights on AI's perceived threat to data roles
- **Programming Languages**: Niche languages like TypeScript commanding premium salaries despite lower usage
- **Remote Work Premium**: Clear compensation advantages for remote positions, especially at senior levels
- **Industry Landscape**: Software development leads in employment, while niche sectors like healthcare offer competitive pay

**Key Takeaway**: 2025 remains a strong time to enter the data field, with rising salaries, diverse opportunities, and AI being viewed more as a tool than a threat.

## 📈 Visualizations

The analysis includes interactive Plotly visualizations:

1. **Geographic Distribution** - Pie chart showing top 10 countries
2. **Role Distribution** - Breakdown of data professional roles
3. **AI Threat Perception** - Survey responses on AI's impact on jobs
4. **Programming Languages** - Usage percentages with median salary color coding
5. **Remote Work Heatmap** - Salary analysis by experience and work arrangement
6. **Industry Analysis** - Top industries with employment and compensation data
7. **Salary Trends** - Historical median salary growth from 2020-2025

## 🔍 Analysis Highlights

### Programming Languages
- Languages ranked by usage percentage among data professionals
- Color-coded by median salary to show compensation potential
- Salary range filtered between $10,000 - $500,000 for accuracy

### Remote Work Analysis
Experience levels analyzed:
- 0-2 years
- 3-5 years
- 6-10 years
- 11-15 years
- 15+ years

Work arrangements compared:
- Remote
- Hybrid
- On-site

### Industry Insights
- Top 10 industries employing data professionals
- Minimum 20 respondents per industry for statistical significance
- Median salary comparisons across sectors

## 📊 Data Source

All data is sourced from the official [Stack Overflow Developer Survey](https://survey.stackoverflow.co/), which has been running annually since 2011. The 2025 survey represents the 15th year of this comprehensive study.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or feedback, please open an issue in this repository.

## 🙏 Acknowledgments

- Stack Overflow for providing comprehensive developer survey data
- The data science community for inspiration and best practices
- All survey respondents who made this analysis possible

---

**Note**: The analysis focuses on data professionals and may not represent the entire developer population surveyed by Stack Overflow.