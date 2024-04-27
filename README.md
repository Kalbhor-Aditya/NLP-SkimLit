# NLP-SkimLit

## Project Overview
NLP-SkimLit is a project aimed at using Natural Language Processing (NLP) to make reading medical literature easier. The project involves various experiments with different models to understand and extract insights from medical texts.

## Models Used
I have used and compared the following models:

1. **Baseline Model (MultinomialNB)**: This is the baseline model for our experiments. It uses the Multinomial Naive Bayes algorithm, which is suitable for classification with discrete features.

2. **CONV1D**: Convolutional Neural Networks can be used to identify patterns in such sequences. They work By sliding a filter or kernel across the sequence and performing elemnet wise multiplication and summation.

3. **Pretrained Token Embedding (universal sentence encoder)**: I also used pretrained token embeddings as a part of model. These embeddings are trained on a large corpus of text and can capture semantic meanings of words.

4. **Character Level Tokenizer and Embedding**: In addition to token level processing, I also experimented with character level processing. This allows the model to capture the meaning of words based on their individual characters.

5. **Positional Encoding Models**: Positional encoding is a concept in transformer networks that allows the model to consider the position of words in the text.

## Experiments
I conducted several experiments using Google Colab notebooks. Each model was trained and evaluated on the same dataset for a fair comparison.

## Results
The results of experiments are summarized in the Results section of our notebooks. We compare the performance of each model based on various metrics.




