# Data

## Dataset: GoEmotions

This project uses the **GoEmotions** dataset by Google Research.

- **Source:** https://github.com/google-research/google-research/tree/master/goemotions
- **HuggingFace:** https://huggingface.co/datasets/google-research-datasets/go_emotions
- **Paper:** https://arxiv.org/abs/2005.00547

## Download Instructions

The raw and processed dataset files are not included in this repository due to file size. To reproduce the data:

1. Run `scripts/01_load_data.py` — this will automatically download the dataset from HuggingFace and save it to `data/raw/go_emotions_raw.csv`
2. Run `scripts/02_preprocess_data.py` — this will clean the data and save it to `data/processed/combined_dataset.csv`

## Folder Structure
# Data

## Dataset: GoEmotions

This project uses the **GoEmotions** dataset by Google Research.

- **Source:** https://github.com/google-research/google-research/tree/master/goemotions
- **HuggingFace:** https://huggingface.co/datasets/google-research-datasets/go_emotions
- **Paper:** https://arxiv.org/abs/2005.00547

## Download Instructions

The raw and processed dataset files are not included in this repository due to file size. To reproduce the data:

1. Run `scripts/01_load_data.py` — this will automatically download the dataset from HuggingFace and save it to `data/raw/go_emotions_raw.csv`
2. Run `scripts/02_preprocess_data.py` — this will clean the data and save it to `data/processed/combined_dataset.csv`

## Folder Structure
## Label System

We collapse GoEmotions' 27 emotion categories into 7 classes using **Parrot's emotion framework** (W. Gerrod Parrott, 2001):

| Parrot Class | GoEmotions Labels |
|---|---|
| Joy | joy, amusement, excitement, optimism, pride, relief, gratitude, approval |
| Love | love, admiration, caring, desire |
| Surprise | surprise, realization, confusion, curiosity |
| Anger | anger, annoyance, disapproval, disgust, embarrassment |
| Sadness | sadness, disappointment, grief, remorse |
| Fear | fear, nervousness |
| Neutral | neutral |

## Class Distribution

| Emotion | Count |
|---|---|
| Joy | 29,222 |
| Surprise | 8,272 |
| Anger | 7,663 |
| Love | 6,552 |
| Neutral | 4,268 |
| Sadness | 1,660 |
| Fear | 371 |
| **Total** | **58,008** |
