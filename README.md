# 🏎️ Formula 1 Winner Prediction

A machine learning project to predict the winner of the current Formula 1 season using historical race data, driver stats, and constructor performance.

## 📊 Project Goals

- Predict the most likely winner of the 2025 Formula 1 season
- Train ML models using historical F1 data
- Explore key features like driver rating, constructor ranking, race count, weather, etc.
- Optional: Build a dashboard or interactive app for predictions

## 📁 Project Structure

- `data/`: Raw and processed data
- `notebooks/`: EDA and experimentation (Colab-compatible)
- `src/`: Modular ML scripts for data prep, training, evaluation
- `models/`: Saved models (`.pkl`, `.joblib`)
- `outputs/`: CSVs, reports, metrics, graphs
- `app/`: Streamlit interface

## 🚀 Setup

```bash
# Clone the repo
git clone https://github.com/mohamed49/f1-winner-prediction.git
cd f1-winner-prediction

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

# Install requirements
pip install -r requirements.txt
