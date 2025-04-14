# Kaggle dataset
## Data Source: AI vs Human
https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images/overview

## Data setup in your directory
Set up a folder called 'data' in your base directory. The contents of 'data' are downloaded from the above and are:
- test_data_v2
- train_data
- test.csv
- train.csv

# Environment
This environment uses the same one as A4, but with the following additions:
- kagglehub: importing data via API
- albumentations: image augmentation. much faster than torchvision

