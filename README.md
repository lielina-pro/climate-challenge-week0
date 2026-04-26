# Climate Challenge Week 0

African Climate Trend Analysis for COP32 preparation.
Conducted by: lielina-pro

## Setup Instructions

### Prerequisites
- Python 3.10+
- Git

### Steps to Reproduce Environment

1. Clone the repository:
   git clone https://github.com/lielina-pro/climate-challenge-week0.git
   cd climate-challenge-week0

2. Create and activate virtual environment:
   python -m venv venv
   venv\Scripts\activate

3. Install dependencies:
   pip install -r requirements.txt

4. Launch Jupyter Notebook:
   jupyter notebook

## Project Structure

- notebooks/  — EDA notebooks per country
- src/         — Source code modules
- scripts/     — Helper scripts
- tests/       — Unit tests
- app/         — Streamlit dashboard
- data/        — Local data folder (NOT committed to GitHub)

## Data Source
Data sourced from NASA POWER database.
Place CSV files inside local data/ folder.
Do NOT commit any CSV files to GitHub.