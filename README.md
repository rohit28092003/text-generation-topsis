# Model Comparison Using TOPSIS

This project evaluates various language models based on multiple performance metrics using the TOPSIS method.

## Overview
The script generates text from multiple models, analyzes their features, and ranks them using the TOPSIS decision-making technique.

## Features Evaluated
1. **Word Count** - Number of words in the generated text.
2. **Readability Score** - Flesch reading ease score.
3. **Lexical Diversity** - Ratio of unique words to total words.
4. **Grammar Errors** - Number of detected grammar issues.
5. **Perplexity** - Model's ability to predict the next word (lower is better).

## Model Rankings
![Image](https://github.com/user-attachments/assets/5e7aed12-2aa2-48a7-90eb-f0bc9a3cc520)


## Visualizations
![Image](https://github.com/user-attachments/assets/2d66277f-2d6b-4739-b313-c5919d6d3325)
![Image](https://github.com/user-attachments/assets/7260c76d-2c6b-4b87-bf96-19dff058bea0)

## Dependencies
- numpy
- matplotlib
- seaborn
- sklearn
- textstat
- language_tool_python
- torch

## Usage
Run the script in a Python environment with the required libraries installed. The output will include model rankings and visualized comparisons.
