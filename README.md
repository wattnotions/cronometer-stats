# cronometer-stats
Takes cronometer weight and calorie csv files and provides enhanced plots and stats

## Weight Tracking Plot

### Installation
```bash
pip install -r requirements.txt
```

### Usage
```bash
python3 weight_plot.py
```

### Features
- Interactive plot showing daily weight measurements and weekly averages
- Weeks start on Monday with vertical lines delineating each week
- Calculates average weight for each week
- Add trendlines between any two weeks to analyze weight changes
- Displays weekly weight change, starting weight, and ending weight for trendlines

### Adding Trendlines
After running the script, you can add trendlines interactively:

```python
# Example: Add trendline from week 0 to week 4
add_trendline(0, 4)

# Example: Add trendline from week 2 to week 8
add_trendline(2, 8)
```

The first datapoint is automatically ignored as it's marked as erroneous.
