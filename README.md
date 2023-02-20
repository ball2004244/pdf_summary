## Target
The goal of this project is to summarize a PDF document using several ML algorithms. The program will take in a PDF file as input and produce a small summary, along with 10 relevant keywords and 5 bullet points. The output will be saved in a text file or equivalent format.

## Methodology
The algorithm will be broken down into several steps:

#PDF Word Recognition: All the words from the input PDF file will be extracted using Optical Character Recognition (OCR) technology. This step will be performed using a Google Colab notebook available at: https://colab.research.google.com/drive/1Z4ejA8HA-3OCnkyqxWMKsBZsdEO-gqbf?usp=sharing.

#Keyword Identification: From the extracted words, 20 keywords will be identified using natural language processing (NLP) techniques, and then narrowed down to the 10 most relevant keywords.

#Summary: A small summary will be generated using NLP techniques. The summary will consist of 7 sentences and will capture the most important information from the PDF document.

#Bullet Points: The algorithm will generate 5 bullet points that summarize the most important points from the PDF document.

#Wrap-up: The output from steps 2, 3, and 4 will be saved in a text file or equivalent format for future use.

##Extras
Two additional features will be implemented in the project:

#Data Storing: The output data from steps 2, 3, and 4 will be stored in a file/files for future use.

#Simple UI: A user interface will be created to allow users to upload a PDF file and view the output in a user-friendly format.

## Conclusion
This project aims to automate the process of summarizing a PDF document using an algorithm. The algorithm will extract keywords, generate a summary and bullet points, and store the output for future use. With the added feature of a simple UI, the project will be user-friendly and accessible to all.