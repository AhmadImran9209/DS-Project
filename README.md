Title: Text Editor with Auto-Suggestion and Huffman Coding

Description:
This C++ program is a text editor that includes features such as auto-suggestion, Huffman coding for compression, and basic file manipulation functionalities. The editor allows users to create a new document, edit existing documents, delete words from a file, search for words, find and replace words, and more.

Features:

Auto-suggestion: The program suggests words based on the user's input, providing up to 10 suggestions from a predefined list of words stored in a trie tree.

Huffman Coding: The program utilizes Huffman coding to compress and decompress data. The Huffman tree is constructed based on the frequency of characters in the input text.

File Manipulation:

Users can start editing from the last edited notepad or create a new notepad.
Words can be deleted from an existing file.
Searching for a word in a file and finding/replacing words are supported.
User Interaction:

The program prompts the user with options to start from the last edited notepad, start from a new notepad, delete a word, search for a word, find and replace a word, or exit the program.
Auto-Storage and Decoding:

The program automatically stores the edited text into a file and uses Huffman coding to encode the data. The Huffman tree is also stored for decoding purposes.
Readme File:

The readme file provides instructions on how to use the text editor, explanations of the implemented features, and how to navigate through different options.
Usage:

Compile and run the program.
Follow the on-screen prompts to perform various actions in the text editor.
The program will automatically store the edited text in the 'Notepad.txt' file, and the encoded data will be saved in 'encode.txt'.
The Huffman tree will be stored in 'hufftree.txt' for decoding.
Note: This program is intended for educational purposes, and improvements can be made for a more user-friendly interface and additional features.

Readme:
The 'Notepad.txt' file contains the text data that you can edit using this program. The encoded version of the data is stored in 'encode.txt', and the Huffman tree is saved in 'hufftree.txt'.

To start the program:

Choose option 1 to start from the last edited notepad.
Choose option 2 to start with a new notepad.
Choose option 3 to delete a word from the existing file.
Choose option 4 to search for a word in the file.
Choose option 5 to find and replace a word in the file.
