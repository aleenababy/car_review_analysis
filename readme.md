# Car-ing is sharing Chatbot Prototype

The Chief Technology Officer (CTO) at "Car-ing is sharing," a car sales and rental company, has enlisted your expertise to prototype a chatbot app that addresses diverse inquiries using Large Language Models (LLMs). The CTO has proposed the following tasks for piloting:
![image](car.jpeg)
## Task 1: Sentiment Analysis on Car Reviews
- Utilize a pre-trained LLM to classify the sentiment of the five car reviews in the `car_reviews.csv` dataset.
- Evaluate the classification accuracy and F1 score of predictions.
- Store the model outputs in `predicted_labels`.
- Extract the labels and map them onto a list of {0,1} integer binary labels called `predictions`.
- Store the calculated metrics in `accuracy_result` and `f1_result`.

## Task 2: English-to-Spanish Translation
- As the company is attracting customers from Spain, extract and pass the first two sentences of the first review in the dataset to an English-to-Spanish translation LLM.
- Calculate the BLEU score to assess translation quality, using the content in `reference_translations.txt` as references.
- Store the translated text generated by the LLM in `translated_review`.
- Store the BLEU score metric result in `bleu_score`.

## Task 3: Extractive Question Answering
- Emphasizing brand aspects, load an extractive Question Answering (QA) LLM such as "deepset/minilm-uncased-squad2".
- Formulate the question "What did he like about the brand?" and obtain an answer.
- Use question and context for the two variables containing the LLM inputs: `question` and `context`.
- Store the actual text answer in `answer`.

## Task 4: Summarization
- Summarize the last review in the dataset into approximately 50-55 tokens long.
- Store it in the variable `summarized_text`.

These tasks aim to demonstrate the capabilities of LLMs in addressing various inquiries and enhancing customer engagement within the car sales and rental industry.