# Anime character movie dialog/quotes generation using GPT2
Text generation is basically a task in which a user gives a prompt or sample text as input and the machine learning model will generate more text just like humans do.<br />
In modern world AI has excelled into the field of natural language processing and there are many advancements in research to develope architectures which helps and asisst human in automating different tasks like paraphrasing, summarization and generation of text.<br />
One of the major breakthrough in this aspect is the innovation of transformer architectures. Transformers is basically an advanced deep learning model which adopts the mechanism of self attention and helps in solving many sequence to sequence or language modeling tasks. <br />
In this project i have fine tuned a gpt2 model on the quotes of anime characters in the movie and important keywords in the text, Our model trained itself in a way that it used text and keywords both in cojuction so that while generating new text it keeps the as a context then generate the anime character quotes based on those keyword.


#### -- Project Status: [Active]

## Project Brief
For the developement of the model i have downloaded data from kaggle by using this link [https://www.kaggle.com/datasets/mahendrasinghrajpoot/anime-quotes-dataset]. After downloading the data i have picked the quotes column from the dataframe and then used yake (yet another keyword extractor) library to extract the important keyword from the given quote. After extracting the keyword i have generated a new data frame and saved a csv file named (Quotes_with_keyword.csv).<br />
Once i got the data figured out i have generated a custom dataset using Pytorch Dataset class and then fine tuned the GPT2 model from HuggingFace for the text generation. 

## Files Description
You will find three files in the project.<br />
Cleaned_data.csv: if you want to use already preprocessed file then you can consume this file and can implement your finding and techniques on it to develope the algorithms.<br />
Roman_Urdu_Hate_Speech_Dataset.csv: This file only contains the tweets and their respective labels.<br />
Roman_Urdu_Hate_Speech.ipynb: This is the notebook file which is built using google colab.

### Methods Used
* Data preprocessing
* Keyword Extraction
* GPT2
* Natural Language Processing

### Technologies
* Python
* Pandas for data manipulation
* PyTorch
* HuggingFace

### Special Thanks To
https://towardsdatascience.com/conditional-text-generation-by-fine-tuning-gpt-2-11c1a9fc639d
