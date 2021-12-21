# EYAZIS
This repository contains systems for:
 * [formation of a natural language dictionary](https://github.com/Vikort/eyazis/tree/main/lab1);
 * [syntactic analysis of natural language](https://github.com/Vikort/eyazis/tree/main/lab2);
 * [semantic analysis of natural language](https://github.com/Vikort/eyazis/tree/main/lab3).

## Authors
- [Markovec Viktor](https://github.com/Vikort)
- [Nikita Filippov](https://github.com/TetVoid)

## Formation of a natural language dictionary
[The system](https://github.com/Vikort/eyazis/tree/main/lab1) allows you to create a dictionary from the text of the Russian language, load the dictionary from a file, and save the dictionary to a file.

The dictionary contains a list of words, sorted alphabetically and includes only lexemes with additionally formalized entries about the place and role of this word in the sentence.
Such information includes a description of which member of the sentence a given word can be and in what form.

The form of inforamtion representation:
The `Lexeme` column contains a list of tokens contained in the dictionary.
The `Tags` column contains morphological features of the lexeme in this sentence.
The column `Sentence member` contains information which member of the sentence in the given sentence the token is. 

Description of functionality:
 - To compile a dictionary, you must enter the text in the upper field and then click the `Convert` button.
 - To save the dictionary, press the `Save` button, select the desired file in the window that appears, or set a name for the new file.
 - To open the dictionary, click the `File` menu item, in the window that appears, select the desired file.

## Syntactic analysis of natural language
[The system](https://github.com/Vikort/eyazis/tree/main/lab2) allows you to parse an English sentence, load a sentence from a file, and save the sentence to a file in docx format.
The result of the parsing of the sentence is presented in the form of a tree, the nodes of which are phrases or tokens.

Description of functionality:
 - To carry out syntactic analysis, you must enter the text in the upper field and then click the `Create` button.
 - To save, you must press the `Save` button, in the window that appears, select the desired file or set a name for a new file.
 - To open the dictionary, click the `File` menu item, in the window that appears, select the desired file.

## Semantic analysis of natural language
[The system](https://github.com/Vikort/eyazis/tree/main/lab3) allows you to carry out a semantic analysis of an English sentence, load a sentence from a file, and also save a sentence to a file in docx format.
The result of the semantic analysis of the sentence is presented in the form of a tree, the nodes of which are lexemes and their definition, synonyms, antonyms, hyponyms and hyperonyms.

Description of functionality:
 - To carry out semantic analysis, you must enter the text in the upper field and then click the `Create` button.
 - To save, you must press the `Save` button, in the window that appears, select the desired file or set a name for a new file.
 - To open the dictionary, click the `File` menu item, in the window that appears, select the desired file.
