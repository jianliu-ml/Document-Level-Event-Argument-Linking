# Code for Document-Level Event Argument Linking as Machine Reading Comprehension

## Dependencies 
- pytorch=1.6 
- transformers=3.1.0
- spacy=3.0 # conflicts with transformers

## Datasets
- RAMS (Download at [https://nlp.jhu.edu/rams/], and put it at data)

## Training Instructions
- Run `python preprocess.py` for preprocessing, which will generate a `data.pk` file (We have released the back translation results in the file `back_translation_result.txt` to ease the preprocessing steps).
- Run `train.py` for model training, which will save the model at the `models` directory.
- Run `evaluate.py` for model evaluation.# Document-Level-Event-Argument-Linking
