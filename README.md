
# Mean Innings Progression of Batters in T20 Cricket

This Python project analyzes the mean innings progression of some of the top batters in T20 cricket based on the number of balls they have faced in their innings. The project visualizes the average runs scored per ball by batters at different stages of their innings, offering insights into how these batters' scoring patterns evolve as they face more deliveries.

## Batters Analyzed

The following batters have been included in this analysis:

- **Babar Azam**
- **Virat Kohli**
- **Andre Russell**
- **Travis Head**
- **Heinrich Klaasen**
- **Nicholas Pooran**
- **Suryakumar Yadav**

## Project Overview

The project uses ball-by-ball T20 data to calculate the mean runs scored by each batter after facing a certain number of balls in an innings. The key focus is on understanding how each player’s approach changes over the course of their innings, especially how they balance risk and reward as they progress.

### Key Features
- **Data Processing**: Extract and clean ball-by-ball data of T20 innings.
- **Visualization**: A line plot shows how the average runs per ball changes as the innings progresses for each batter.
- **Comparison**: This allows for direct comparisons between different playing styles, from the consistent accumulation of players like **Virat Kohli** and **Babar Azam** to the explosive hitting of **Andre Russell** and **Suryakumar Yadav**.

## Result Overview

The graph (as shown in the attached image) illustrates the mean runs scored per ball for each batter up to 70 balls. 

- **Suryakumar Yadav** (Blue) shows the highest peaks, reflecting his aggressive, high-risk-high-reward approach, especially in the middle overs.
- **Babar Azam** (Red) and **Virat Kohli** (Green) demonstrate more consistent scoring patterns, steadily accumulating runs.
- **Andre Russell** (Purple) exhibits sporadic spikes, highlighting his explosive capabilities towards the end of his innings.

## How to Run the Project

### Prerequisites

- Python 3.x
- pandas
- matplotlib
- plotly

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/t20-batting-progression.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib plotly
   ```

### Usage

1. Load the ball-by-ball T20 dataset into the `data/` directory.
2. Run the script:
   ```bash
   python batting_progression.py
   ```
3. The output will be a line plot visualizing the mean innings progression of the selected batters.

## Conclusion

This project provides an insightful analysis of how different T20 cricket batters approach their innings. From the more traditional accumulation to aggressive risk-taking, the graph offers a clear visual comparison between these top players, helping cricket analysts, fans, and coaches understand their strategies.

---

This should give you a solid README for your project, detailing its purpose, execution, and results. Let me know if you need any further customization!
