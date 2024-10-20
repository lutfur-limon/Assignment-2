# NLP and Python Programming Assignment
Overview
This repository contains the solution to the second assignment of the unit, which involves performing natural language processing (NLP) tasks on large text data, programming challenges, and a decryption puzzle. The assignment covers text extraction, word counting, tokenization, named-entity recognition, image manipulation, and error-prone code correction.

The repository is divided into several tasks:

NLP on large text files
Programming and image manipulation challenges
Code decryption and correction
# Task Breakdown
## Task 1: Text Extraction
Extracts the 'text' from multiple CSV files and stores them into a single .txt file.
The script task1_text_extraction.py reads all CSV files, extracts the text columns, and combines them into a single file combined_data.txt.
## Task 2: Library Installation
This task requires the installation of NLP libraries for processing biomedical text data.
The file task2_library_installation.md contains instructions on how to install the necessary Python libraries:
SpaCy
scispaCy with models en_core_sci_sm and en_ner_bc5cdr_md
Transformers (Hugging Face) with BioBERT for biomedical NER
## Task 3: Word Count and Tokenization
Word Count: The script task3_word_count.py counts the occurrences of words in the combined text file (combined_data.txt) and outputs the top 30 most common words. The results are saved in top_30_words.csv.
Tokenization: The script task3_auto_tokenizer.py tokenizes the text using the Hugging Face Transformers AutoTokenizer function and counts the top 30 unique tokens.
## Task 4: Named-Entity Recognition (NER)
This task extracts diseases and drugs from the text using the scispaCy models and BioBERT.
The script task4_ner_extraction.py performs NER with both models, and the file task4_ner_comparison.md presents a comparison between the two, including the total number of entities detected and differences in the results.
## Chapter 1: Image Pixel Manipulation
In this task, the input image (chapter1.png) is manipulated by adding a number to the RGB values of the pixels.
The output image (chapter1out.png) is generated, and the sum of the red pixel values in the new image is calculated.
The script chapter1_pixel_manipulation.py handles this process.
## Chapter 2: Code Decryption and Error Fixing
The encrypted code is decrypted using a custom decryption function, then fixed to remove errors.
The script chapter2_code_decryption.py performs the decryption and error correction.
How to Run the Code
## Prerequisites
Python 3.7 or above
Required Python libraries:
pandas
transformers
spacy
scispacy
