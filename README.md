# Love Island ROI & Popularity Analysis

A polished 7-slide Jupyter notebook presentation analyzing Love Island contestants for future seasons and spin-offs using data science and machine learning.

## Features

- **Slide 1**: Title slide with Love Island branding
- **Slide 2**: Analysis framework (Reach, Engagement, ROI)
- **Slide 3**: Reach growth analysis with Plotly charts
- **Slide 4**: Engagement efficiency with PyTorch regression model
- **Slide 5**: ROI analysis with cost calculations and projections
- **Slide 6**: Persona clustering with PyTorch autoencoder
- **Slide 7**: Final recommendation

## Requirements

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. **Run the notebook**: Open `deck.ipynb` in Jupyter
2. **Execute all cells**: Run all cells to generate the analysis
3. **Convert to slides**: Use RISE to present as slides

### Converting to PDF slides

```bash
jupyter nbconvert deck.ipynb --to slides --TemplateExporter.exclude_input=True --post serve
```

## Key Insights

- **Waylor Tilliams** emerges as the top choice with highest ratings, strongest growth, and best ROI
- **Sustin Ahepard** is the runner-up for global marketability
- Contestants cluster into two groups: Efficient Fan Favorites vs Global High-Cost Stars
- Screen time and reach are the strongest predictors of poll ratings

## Technology Stack

- **Data Analysis**: Pandas, NumPy
- **Visualization**: Plotly
- **Machine Learning**: PyTorch, Scikit-learn
- **Presentation**: Jupyter + RISE (Reveal.js night theme)
# BAC
