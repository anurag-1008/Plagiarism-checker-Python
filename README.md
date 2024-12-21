# Plagiarism-checker-Python
This repo consists of a source code of a Python script which detects plagiarism in a textual document using cosine similarity.

How is it Done?
You might be wondering how plagiarism detection on textual data is done, well it ain't as complicated as you may think.

We all know that computers are good with numbers; so in order to compute the similarity between two text documents, the textual raw data is transformed into vectors => arrays of numbers and from that, we make use of basic knowledge of vectors to compute the similarity between them.

This repo contains a basic example on how to do that.

Getting Started
To get started with the code on this repo, you need to either clone or download this repo into your machine as shown below;

git clone https://github.com/anurag-1008/Plagiarism-checker-Python
Dependencies
Before you begin playing with the source code, you might need to install dependencies just as shown below;

pip3 install -r requirements.txt
Running the App
To run this code you need to have your textual documents in your project directory with the .txt extension. When you run the script, it will automatically load all the documents with that extension and then compute the similarities between them as shown below;

$-> cd Plagiarism-checker-Python
$ Plagiarism-checker-Python-> python3 app.py
('sam.txt', 'atib.txt', 0.5465972177348937)
('gulisha.txt', 'sam.txt', 0.14806887549598566)
('gulisha.txt', 'atib.txt', 0.18643448370323362)
A Python Library?
Would you like to use a Python library instead to help you compare strings and documents without spending time writing the vectorizers by yourself, then take a look at Pysimilar.

Issues
In case you have any difficulties or issues while trying to run the script you can raise an issue.

Pull Requests
If you have something to add, I welcome pull requests on improvement; your helpful contribution will be merged as soon as possible.

Give it a Star
If you find this repo useful, give it a star so that many people can get to know it.

