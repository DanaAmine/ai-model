# Part 1 : Genetic Algorithm for Discord Meeting Scheduling

This script implements a genetic algorithm to optimize meeting scheduling for a Discord server. It reads preprocessed data from a CSV file, containing available meeting times, and generates optimal meeting schedules based on specified parameters.

## Requirements

- Python 3.x
- pandas
- numpy

## Installation

1. Clone the repository or download the script file (`genetic_algorithm_discord.py`).
2. Install the required Python packages:
    ```bash
    pip install pandas numpy
    ```

## Usage 

1. Prepare your dataset:
   - Ensure your meeting time data is preprocessed and saved in a CSV file named `discordData.csv`.
   - The CSV file should contain a column named `'time'` with available meeting times.

2. Run the script:
    ```bash
    python genetic_algorithm_discord.py
    ```

3. Adjust parameters (optional):
   - You can modify parameters such as `population_size`, `num_generations`, and `crossover_rate` within the script according to your requirements.

4. Interpret results:
   - The script will output the best solution found after the specified number of generations.

## Parameters

- `population_size`: The number of solutions (meeting schedules) in each generation.
- `num_generations`: The number of generations the algorithm will run.
- `crossover_rate`: The probability of crossover occurring between two solutions during reproduction.

## Customization

- Fitness Function:
  - Modify the `evaluate_fitness` function to define a custom fitness function that evaluates the quality of each solution based on your specific requirements.

- Representation and Crossover:
  - Define your representation of a solution and implement custom crossover methods in the `crossover` function according to your problem domain.

## Contributing

Pull requests and suggestions for improvements are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Part 2 : TikTok Posts Time Prediction 

This project aims to predict the best time to post content on TikTok using statistical methods. By analyzing historical posting data and engagement metrics, the script identifies the optimal time slots for maximizing post visibility and audience interaction.

## Overview

TikTok has become a popular platform for content creators, and timing plays a crucial role in reaching a wider audience. This script helps TikTok creators schedule their posts more effectively by leveraging statistical analysis of past posting trends.

## Data

- **Input Data**: 
  - The script requires a dataset containing historical TikTok posting data, including timestamps and corresponding engagement metrics (e.g., likes, comments, shares).
  - Ensure the dataset is preprocessed and formatted correctly before running the script.

## Statistical Methods

- **Time Series Analysis**:
  - The script performs time series analysis on the historical posting data to identify patterns and trends in user engagement over time.
  - It may include techniques such as trend analysis, seasonality decomposition, and forecasting.

- **Descriptive Statistics**:
  - Utilizes descriptive statistics to summarize key metrics such as average engagement rate, peak posting times, and variability in audience activity.

- **Probability Distributions**:
  - Fits probability distributions (e.g., normal distribution) to the posting data to model the distribution of engagement metrics.
  - This helps in estimating the likelihood of achieving certain engagement levels at different posting times.

## Usage

1. **Data Preparation**:
   - Prepare your dataset containing historical TikTok posting data.
   - Ensure the dataset includes timestamps and relevant engagement metrics.

2. **Run the Script**:
   - Execute the script (`tiktok_posts_time_prediction.py` or similar) in a Python environment.
   - Provide the path to your dataset as input to the script.

3. **Interpret Results**:
   - The script will output predicted optimal time slots for posting content on TikTok based on statistical analysis.
   - Analyze the results and adjust your posting schedule accordingly to maximize audience reach and engagement.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib (for visualization, if applicable)

## Contributing

Contributions and feedback are welcome! If you have suggestions for improvement or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
