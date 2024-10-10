# Text Analysis Tool - API Documentation

## Overview

This document provides a list of available functions in the text analysis tool and how they can be used.

## Functions

### 1. `word_count(data: str) -> int`

#### Description:
Returns the total number of words in the provided text.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`int`**: The number of words in the text.

#### Example:
```python
text = "This is a test."
word_count(text)  # Output: 4
```

---

### 2. `sentence_count(data: str) -> int`

#### Description:
Returns the total number of sentences in the provided text.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`int`**: The number of sentences in the text.

#### Example:
```python
text = "This is a test. This is another test."
sentence_count(text)  # Output: 2
```

---

### 3. `unique_words(data: str) -> list`

#### Description:
Returns a list of unique words from the provided text, ignoring punctuation and case sensitivity.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`list`**: A list of unique words.

#### Example:
```python
text = "This is a test. This is another test."
unique_words(text)  # Output: ['this', 'is', 'a', 'test', 'another']
```

---

### 4. `avg_len_sen(data: str) -> float`

#### Description:
Calculates and returns the average sentence length in terms of words.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`float`**: The average number of words per sentence.

#### Example:
```python
text = "This is a test. This is another test."
avg_len_sen(text)  # Output: 4.0
```

---

### 5. `word_freq(data: str) -> dict`

#### Description:
Returns a dictionary where the keys are words and the values are the frequency of occurrence of each word in the text.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`dict`**: A dictionary containing word-frequency pairs.

#### Example:
```python
text = "This is a test. This is another test."
word_freq(text)  
# Output: {'this': 2, 'is': 2, 'a': 1, 'test': 2, 'another': 1}
```

---

### 6. `most_common(data: str) -> list`

#### Description:
Returns a list of the top 10 most common words in the provided text.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`list`**: A list of the 10 most common words.

#### Example:
```python
text = "This is a test. This is another test."
most_common(text)  # Output: ['this', 'is', 'test', 'a', 'another']
```

---

### 7. `lexical_diversity(data: str) -> float`

#### Description:
Calculates and returns the lexical diversity of the text, defined as the ratio of unique words to the total number of words.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`float`**: Lexical diversity value (unique words / total words).

#### Example:
```python
text = "This is a test. This is another test."
lexical_diversity(text)  # Output: 0.62
```

---

### 8. `syllables_count(data: str) -> int`

#### Description:
Returns the total number of syllables in the provided text.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`int`**: The total syllable count.

#### Example:
```python
text = "This is a Python test."
syllables_count(text)  # Output: 6
```

---

### 9. `identify_syllable(word: str) -> int`

#### Description:
Estimates the number of syllables in a given word.

#### Parameters:
- **`word`**: `str`  
  The word to analyze.

#### Returns:
- **`int`**: The number of syllables in the word.

#### Example:
```python
word = "Python"
identify_syllable(word)  # Output: 2
```

---

### 10. `readability_score(data: str) -> float`

#### Description:
Calculates the Flesch-Kincaid readability score of the provided text based on the word count, sentence count, and syllables.

#### Parameters:
- **`data`**: `str`  
  The input text to be analyzed.

#### Returns:
- **`float`**: The Flesch-Kincaid readability score.

#### Example:
```python
text = "All the wonderful things Mr.Brown can do."
readability_score(text)  # Output: 94.51
```

---

### 11. `explain_score(score: float) -> str`

#### Description:
Interprets the Flesch-Kincaid readability score, providing a description of the text’s reading level.

#### Parameters:
- **`score`**: `float`  
  The Flesch-Kincaid readability score to be explained.

#### Returns:
- **`str`**: A string description of the reading level.

#### Example:
```python
score = 94.51
explain_score(score)  # Output: "5th grade: Very easy to read. Easily understood by an average 11-year-old student."
```

---
### 12. `input_file() -> str`

#### Description: 
Prompts the user for the input file to be used in the text analysis. The user can choose from sample data files or provide their own.

#### Parameters:
None.

#### Returns:
- **`str`**: The name of the input file.

---
### 13. `output_file() -> str`

#### Description:
Prompts the user for the output file name to save the results of the text analysis.

#### Parameters:
None.

#### Returns:
- **`str`**: The name of the output file with extension.
---
