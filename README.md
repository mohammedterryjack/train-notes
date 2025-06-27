# train-notes
notes to remember for any ml training. Remember, the insights from each step will help inform which method is best to use in subsequent steps

## Data (EDA)
- what are the sources? / can we get more?
- are they complete/comprehensive? / what is missing?
- how noisy is the data? (e.g. blanks, failed downloads/generations, etc)
- how noisy are the labels? (e.g. errors, mistakes, blanks, etc)
- how much data per label? / balanced / biases?
- do we need to augment data?
- what features are present?
- what does the typical data look like (qualitative analysis)
- what does the edge case data look like / what are the edge cases?


## Features
- what features exist?
- what additional features can be extracted?
- consider: numerical features, categorical features, textual features, image features, temporal features, sound features, positional features, etc
- consider ways of encoding each type (e.g. pretrained encoders, learned encoders, etc)

## Models
- model-free approaches (embeddings and ranking)
- model approaches (sklearn, torch, huggingface, etc)
- llms

## Training  
- hyperparameter tuning / grid search (e.g. random seed mining, epochs, etc)
- loss functions (e.g. Focal, BCE, etc)
- metrics (e.g. IoU)

## Results Analysis
- feature analysis (SHAP - impact of features on the decisions made by the model)
- model variations - which was best?
- hyperparameter variations - which was best?
- weaknesses of best model? why? / future improvements
- manual evaluations (qualitative)
- inspect predictions (typical)
- inspect predictions (edge cases)

## Deployment
- logging
- dashboard / live monitoring
