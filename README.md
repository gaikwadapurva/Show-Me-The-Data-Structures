# Show-Me-The-Data-Structures


## About The Project

This project showcases solutions to six tasks using multiple data structures. It uses Python to analyze and answer questions using clean implementations and efficient answers. Lastly, it also indicates run time analysis of the solutions and determines its efficiency and design choices.


### Problem 1: LRU Cache

The goal here is to design a data structure known as a Least Recently Used (LRU) cache. An LRU cache is a type of cache in which we remove the least recently used entry when the cache memory reaches its limit. For the current problem, consider both get and set operations as an use operation.

Our job is to use an appropriate data structure(s) to implement the cache.

In case of a cache hit, our get() operation should return the appropriate value.
In case of a cache miss, our get() should return -1.
While putting an element in the cache, your put() / set() operation must insert the element. If the cache is full, we must write code that removes the least recently used entry first and then insert the element.

All operations must take O(1) time.

For the current problem, we can consider the size of cache = 5.


### Problem 2: File Recursion

For this problem, the goal is to write code for finding all files under a directory (and all directories beneath it) that end with ".c"

Here is an example of a test directory listing, which can be downloaded [here](https://s3.amazonaws.com/udacity-dsand/testdir.zip).


### Problem 3: Huffman Coding

A data compression algorithm reduces the amount of memory (bits) required to represent a message (data). The compressed data, in turn, helps to reduce the transmission time from a sender to receiver. The sender encodes the data, and the receiver decodes the encoded data. As part of this problem, you have to implement the logic for both encoding and decoding.

A data compression algorithm could be either lossy or lossless, meaning that when compressing the data, there is a loss (lossy) or no loss (lossless) of information. The Huffman Coding is a lossless data compression algorithm.

Here is one type of pseudocode for this coding schema:

1. Take a string and determine the relevant frequencies of the characters.
2. Build and sort a list of tuples from lowest to highest frequencies.
3. Build the Huffman Tree by assigning a binary code to each letter, using shorter codes for the more frequent letters (This is the heart of the Huffman algorithm).
4. Trim the Huffman Tree (remove the frequencies from the previously built tree).
5. Encode the text into its compressed form.
6. Decode the text from its compressed form.
7. Create encoding, decoding, and sizing schemas.


### Problem 4: Active Directory

n Windows Active Directory, a group can consist of user(s) and group(s) themselves. We can construct this hierarchy as such where User is represented by str representing their ids.

The solution to this problem specifies a function that provides an efficient look up of whether the user is in a group.


### Problem 5: Blockchain

A Blockchain is a sequential chain of records, similar to a linked list. Each block contains some information and how it is connected related to the other blocks in the chain. Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data. For our blockchain we will be using a SHA-256 hash, the Greenwich Mean Time when the block was created, and text strings as the data.

Finally we'll need to link all of this together in a block chain, which we'll be doing by implementing it in a linked list. All of this will help us build up to a simple but full blockchain implementation!


### Problem 6: Union and Intersection

Our task for this problem is to fill out the union and intersection functions. The union of two sets A and B is the set of elements which are in A, in B, or in both A and B. The intersection of two sets A and B, denoted by A ∩ B, is the set of all objects that are members of both the sets A and B.

We'll take in two linked lists and return a linked list that is composed of either the union or intersection, respectively. Once we have completed the problem, we'll create our own test cases and perform our own run time analysis on the code.