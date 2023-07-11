# Plagiarism-Checker

This repo consists of a source code of a Python script which detects plagiarism in a textual document using **cosine similarity**.

## How is it Done?

In order to compute the similarity between two text documents, the textual raw data is transformed into vectors => arrays of numbers and from that, we make use of basic knowledge of vectors to compute the similarity between them.

## Dependencies

```bash
pip3 install -r requirements.txt
```

## Running the App

To run this code you need to have your textual documents in your project directory with the **.txt** extension. When you run the script, it will automatically load all the documents with that extension and then compute the similarities between them as shown below;

```bash
$-> cd Plagiarism-Checker
$ Plagiarism-checker-Python-> python app.py
('studentA.txt', 'studentB.txt', 0.16228391831223246)
('studentA.txt', 'studentC.txt', 0.20179089793739657)
('studentB.txt', 'studentC.txt', 0.5713243251172899)
```
