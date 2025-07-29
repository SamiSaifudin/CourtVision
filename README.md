# CourtVision: NBA Team Clustering Analysis

## Overview

CourtVision is a data science project that analyzes NBA team play styles using clustering algorithms. The project combines NBA API data with play type statistics to categorize teams based on their offensive strategies and playing patterns.

## Project Structure

```
CourtVision/
├── courtVision.ipynb          # Main analysis notebook
├── cluster_analysis.md        # Detailed clustering results
├── Data/
│   └── NBA Play Type Data - Sheet1.csv  # Play type frequency data
├── output.png                 # Generated output visualization
└── README.md                  # This file
```

## Analysis Components

### Data Sources
- **NBA Stats Website**


### Key Metrics Analyzed
- Team pace and possession data
- Play type frequencies (isolation, transition, pick-and-roll, handoff, post-up)
- Offensive rebound percentage
- Turnover rate
- Three-point shooting rate
- Assist rate

## Clustering Results

The analysis identified **9 distinct team clusters** based on playing style:

### Cluster Categories
1. **Balanced Passing Oriented Teams** (Denver Nuggets, Indiana Pacers, San Antonio Spurs)
2. **Well Rounded** (Cleveland Cavaliers, Detroit Pistons, Golden State Warriors, New Orleans Pelicans, Portland Trail Blazers, Utah Jazz, Washington Wizards)
3. **Heliocentric Star Oriented Teams** (Dallas Mavericks, Milwaukee Bucks, Oklahoma City Thunder)
4. **Slower Paced, Defensive Oriented Teams** (Miami Heat, Minnesota Timberwolves, Orlando Magic, Phoenix Suns)
5. **High-Octane, Fast-Paced Teams** (Atlanta Hawks, Toronto Raptors)
6. **Fast Paced Transition Oriented Teams** (Chicago Bulls, Memphis Grizzlies)
7. **Paint Oriented Teams** Houston Rockets, LA Clippers, Los Angeles Lakers, New York Knicks, Philadelphia 76ers, Sacramento Kings
8. **Three Point Volume Shooters** (Brooklyn Nets, Charlotte Hornets)
9. **The Boston Celtics** (Unique outlier playstyle)

For detailed cluster analysis, see [cluster_analysis.md](cluster_analysis.md).

## Setup and Installation

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required Python packages

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd CourtVision
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib scikit-learn nba_api
```

3. Activate the virtual environment (if using):
```bash
source myenv/bin/activate  # On macOS/Linux
```

### Running the Analysis

1. Open the Jupyter notebook:
```bash
jupyter notebook courtVision.ipynb
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- NBA API for providing comprehensive team statistics
- Scikit-learn for machine learning algorithms
- The NBA community for play type data insights
