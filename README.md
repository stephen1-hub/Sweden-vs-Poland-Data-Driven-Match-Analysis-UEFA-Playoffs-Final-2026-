# Sweden-vs-Poland-Data-Driven-Match-Analysis-UEFA-Playoffs-Final-2026-
# Overview

This project analyzes the Sweden vs Poland UEFA Playoffs Final (2026) using shot data to uncover tactical insights, player performance, and shot efficiency.

Rather than relying on generic observations, this analysis connects data → insights → actionable recommendations for coaching and scouting decisions.

# Objective

To evaluate attacking patterns, shot quality, and player contributions using data, and translate these into clear tactical and recruitment insights.

# Data Used
Shot-level data including:
Player name
Shot coordinates (x, y)
Shot outcome (goal, miss, save, block, post)
Team (home/away)
Derived metrics:
Shooting accuracy
Average distance to goal
Shot distribution by type
Body part usage
# Key Findings
Poland
15 total shots
46.7% shooting accuracy
Average shot distance: 21m
Relied on central areas and long-range efforts
Sweden
9 total shots
55.6% shooting accuracy
Average shot distance: 12.8m
Focused on high-quality chances inside the box
# Insight

Sweden’s efficiency came from taking shots closer to goal, while Poland’s higher volume was offset by lower shot quality.

# Player Highlights
Karol Świderski – 3 shots, 1 goal, 100% on target
Anthony Elanga – 1 shot, 1 goal
Viktor Gyökeres – 1 shot, 1 goal (close range)
# Visualizations
Shot Map (with distance-to-goal annotations)
Shot Outcome Distribution
Player Shot Contributions

Example:

Circles = Sweden (home)
Squares = Poland (away)
Colors represent shot outcomes (goal, miss, save, etc.)
# Tactical Implications
Poland needs more shot diversity, especially from the left side or long-range specialists
Sweden should maintain efficiency but add width in build-up play to stretch defenses
# Tech Stack
Python
Pandas
Matplotlib
Mplsoccer
# How to Run
# Clone the repository
git clone https://github.com/your-username/sweden-vs-poland-analysis.git

# Navigate into the project folder
cd sweden-vs-poland-analysis

# Install dependencies
pip install -r requirements.txt

# Run the script
python app.py
# Future Improvements
Add Expected Goals (xG) model
Build interactive dashboard (Streamlit)
Compare multiple matches
Player clustering & shot profiles
# Connect

If you're interested in football analytics, scouting, or data-driven decision making, feel free to connect or collaborate!
