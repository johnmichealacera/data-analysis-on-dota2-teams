# Dota 2 Teams Data Analysis

A comprehensive data analysis project exploring professional Dota 2 team statistics, performance metrics, and competitive insights.

## 📊 Project Overview

This project analyzes professional Dota 2 team data to uncover patterns in team performance, ratings, and competitive standings. The analysis includes data visualization, statistical insights, and performance comparisons across different teams in the professional Dota 2 scene.

## 🎯 Key Features

- **Team Performance Analysis**: Comprehensive analysis of team ratings, win/loss records, and competitive metrics
- **Data Visualization**: Interactive charts and graphs showing team performance trends
- **Statistical Insights**: Deep dive into team statistics and performance patterns
- **Professional Teams Database**: Curated dataset of professional Dota 2 teams with detailed metrics

## 📁 Project Structure

```
data-analysis-on-dota2-teams/
├── dota_team_analysis.ipynb    # Main Jupyter notebook with analysis
├── teams.json                  # Team data in JSON format
├── README.md                   # Project documentation
└── LICENSE                     # MIT License
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required Python packages (see requirements below)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/data-analysis-on-dota2-teams.git
cd data-analysis-on-dota2-teams
```

2. Install required packages:
```bash
pip install pandas matplotlib jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `dota_team_analysis.ipynb` to explore the analysis

## 📈 Data Analysis

The project includes several key analyses:

### Team Performance Metrics
- **Rating Analysis**: Examination of team ratings and their distribution
- **Win/Loss Records**: Statistical analysis of team performance
- **Performance Filtering**: Teams with ratings above 1450 for focused analysis

### Visualizations
- **Stacked Bar Charts**: Visual representation of team performance metrics
- **Performance Comparisons**: Side-by-side analysis of top-performing teams
- **Statistical Distributions**: Understanding of rating and performance patterns

### Key Insights
- Analysis of top-performing teams like Team Liquid, Gaimin Gladiators, and Shopify Rebellion
- Performance trends and competitive patterns
- Statistical correlations between different performance metrics

## 📊 Sample Data

The dataset includes information about professional Dota 2 teams with the following fields:

- `team_id`: Unique identifier for each team
- `name`: Team name
- `tag`: Team abbreviation
- `rating`: Team rating/ELO score
- `wins`: Number of wins
- `losses`: Number of losses
- `last_match_time`: Timestamp of last match
- `logo_url`: URL to team logo

## 🛠️ Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Interactive development environment
- **JSON**: Data storage format

## 📋 Requirements

```
pandas>=1.3.0
matplotlib>=3.4.0
jupyter>=1.0.0
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**John Micheal Acera**

## 🙏 Acknowledgments

- Dota 2 community for the competitive scene
- OpenDota API for providing team data
- The data science community for inspiration and tools

## 📞 Contact

If you have any questions or suggestions, feel free to reach out!

---

*This project is for educational and analytical purposes. All team data is publicly available information.*