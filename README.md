# NLP_Project on Priming for Tonal Consistency in AI Text Generation


## Description

Explores the limitations of human-authored tone (in context of sentiment) priming language models.

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Experiment Description](#experiment-description)
- [Results](#results)

## Installation

This project was created, run, and tested using Google Collab Pro. Unsure of what would need to be changed to run this on a local machine. 

## Dependencies

Before running the code, ensure you have the following libraries and dependencies installed:

- OpenAI (API key required)
- Sentence-Transformers
- NumPy
- SciPy
- Itertools
- Time
- Tabulate
- Matplotlib
- Pandas (for exporting results to LaTeX)

## Usage

1. Set up your OpenAI API key by adding it to the `openai.api_key` variable in the Python script. You will need to have the paid option for this model (using the second model would not have kept up with cutting-edge research in the area).

2. Run the experiment


## Experiment Description

The experiment aims to assess the tonal consistency in AI-generated responses compared to responses from real students. The code uses OpenAI's GPT-3.5-turbo model to generate responses based on priming examples and a given prompt. The Semantic Similarity metric with BERT embeddings measures the similarity between generated responses.

## Results

The experiment results are presented in various ways:

- Mean Similarity Scores for Real Student and AI Student Responses
- Standard Deviation for Real Student and AI Student Responses
- Median and Range for Real Student and AI Student Responses
- 25th Percentile and 75th Percentile for Real Student and AI Student Responses

Additionally, the statistical significance of the results is tested using the Mann-Whitney U test. The output indicates whether there are statistically significant differences between Real Student and AI Student Scores at each priming level.

For detailed tabular results in LaTeX format, refer to the files `output_part1.tex` and `output_part2.tex`.

To visualize the results, the following plots are generated and saved as images:

- Line Plot: Mean Similarity Scores for Real Student vs AI Student Responses
- Bar Plot: Range of Similarity Scores for Real Student vs AI Student Responses
- Bar Plot: 25th Percentiles of Similarity Scores for Real Student vs AI Student Responses
- Bar Plot: 75th Percentiles of Similarity Scores for Real Student vs AI Student Responses
- Bar Plot: Standard Deviation of Similarity Scores for Real Student vs AI Student Responses


