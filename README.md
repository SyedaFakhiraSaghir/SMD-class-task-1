# Word Frequency Analyzer

A simple Dart program that identifies the most frequent word in each sentence of a given list.

## Overview

This program analyzes a list of sentences and finds the word that appears most frequently in each sentence. For each sentence, it outputs the most common word along with the sentence number.

## How It Works

1. A list of three sentences is defined:
   - "this is a test this is"
   - "hello hello world"
   - "dart is fun fun fun"

2. For each sentence:
   - Splits the sentence into individual words
   - Counts the frequency of each word
   - Identifies the word with the highest frequency
   - Outputs the result with the sentence number

## Output Format
[word] (appears in sentence number X)

Where:
- `word` is the most frequently occurring word in the sentence
- `X` is the sentence number (1-based index)

## Example Output

For the given sentences, the program will output:
[this] (appears in sentence number 1)
[hello] (appears in sentence number 2)
[fun] (appears in sentence number 3)

## Note
In case of ties (multiple words appearing with the same maximum frequency), the program outputs the first word that reaches the maximum count during iteration.

## Requirements

- Dart SDK

## How to Run

1. Save the code in a file with `.dart` extension (e.g., `word_frequency.dart`)
2. Run using Dart:
   ```bash
   dart word_frequency.dart
