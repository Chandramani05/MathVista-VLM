# Generate Advanced Multi-modal Mathematical And Synthetic data

This is a novel pipeline for generating synthetic multi-modal data to improve mathematical reasoning capabilities in Vision Language Models (VLMs). This project demonstrates significant improvements in VLM performance on mathematical reasoning tasks, particularly those involving bar charts and line plots.

## Key Features

- **Synthetic data generation pipeline using GPT-4 and code generation**
- **860 training samples and 200 validation samples of bar charts and line plots**
- **Fine-tuning of InternLM-XComposer2-VL-1.8B using LoRA and DoRA**
- **Evaluation on MathVista benchmark**

## Results
  - 6.5% increase in performance on bar chart tasks in MathVista
  - 12.5% increase in performance on line chart tasks in MathVista
  - Improved performance on other categories, including geometry tasks

## Dataset

The dataset includes:

- **460 bar charts**
- **400 line plots**
- **Associated mathematical reasoning questions**

## Example generated bar chart:

<figure>
    <img src= images/bar_chart.png alt="Example generated bar chart">
    <figcaption>Example Bar Chart Generated Using GAMMAS. Associated question: According to the bar chart, what was the percentage increase in hours spent by users on Online Shopping from 2019 to 2020?</figcaption>
</figure>
