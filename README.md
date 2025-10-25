# cronometer-stats
Takes cronometer weight and calorie csv files and provides enhanced plots and stats

## Weight Tracking Plot

### Installation
```bash
pip install -r requirements.txt
```

### Usage
```bash
python3 interactive_weight_plot.py
```

### Features
- **Fully interactive matplotlib-based plot** with mouse controls
- Shows daily weight measurements and weekly averages
- **Click-to-create trendlines**: Left-click on weekly average points to set trend line endpoints
- **Drag to adjust**: Drag trend line endpoints to fine-tune them
- **Right-click to reset**: Clear trend lines and start over
- Weeks start on Monday with vertical lines delineating each week
- Calculates average weight for each week
- Real-time statistics display showing start/end weights, total change, and weekly change
- Visual feedback with color-coded selected points

### Interactive Controls
- **Left-click**: Select weekly average points to create trend lines
- **Right-click**: Reset/clear current trend line
- **Drag**: Adjust trend line endpoints by dragging them to nearby weekly averages
- **Automatic snapping**: Trend lines automatically snap to weekly average points

### How to Use
1. Run `python3 interactive_weight_plot.py`
2. Left-click on a weekly average point to set the start of your trend line
3. Left-click on another weekly average point to set the end
4. Drag the endpoints to adjust if needed
5. Right-click to reset and start over

The first datapoint is automatically ignored as it's marked as erroneous.
