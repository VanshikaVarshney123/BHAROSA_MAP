
# Bharosa Map

A heat-risk map for city wards that is honest about what it doesn't know.

Made for Hacktoberfest, PS 4.2: Bharosa Map (Heat-Resilient and Alert India).

## The problem
Heat maps can look exact even when there is very little data behind them. This can send cooling and health help to the wrong places.

## What our map does
For every ward it shows:
- **Risk score** (0 to 100): how dangerous the heat is
- **Confidence**: how much we can trust that score
- **"Insufficient data"**: shown in grey when there is not enough evidence, with no score at all

## Main features
- Colour shows risk. Hatching means the estimate is less reliable.
- A slider sets how much confidence is needed before a score is shown.
- Hospital heat-illness data is used to check our estimates, and wards where it disagrees are flagged.
- Each ward gets a clear action: act now, verify first, or collect data.
- You can upload your own CSV data and download the results.

## How to run
Download the files and open `index.html` in your browser. No installation needed.

## Note on data
The data in this prototype is **simulated** for demonstration. It is not real measurement of any city.

## Built with
HTML, CSS and JavaScript

## Author
[Your name], B.Tech student, MMMUT Gorakhpur
