# Text Analysis Tool

## Overview

This is a Python program that performs text analysis on a given file, providing statistics such as word count, sentence count, lexical diversity, readability score, and more. The program also outputs the top 10 most common words in the text and a frequency count for each word.

## Repository Contents
- `data` contains sample input data
- `API_documentation` explains the functions
- `main.py` main program to run
- `text_analysis_tool.ipynb` copy of the original Python notebook
- `report_hamilton.txt` sample output file

## How to Run the Program

The Python Notebook is publicly accessible through [Text Analysis Tool - Google Colab](https://colab.research.google.com/github/linforestli/text_analysis/blob/main/text_analysis_tool.ipynb).

Alternatively, clone or download the [repository](https://github.com/linforestli/text_analysis). Then run the program using Python and follow the prompts.
```bash
python main.py
```

## Example Run
1. **Input Prompt**:
```bash
Enter the name of the input file, or choose from the following sample data:
 2. The Life of Chuck by Stephen King (Excerpt)
 3. Mr. Brown can Moo! can you? by Dr. Seuss
 4. Advantage of the Union in Respect to Economy in Government by Alexander Hamilton
```
Type `1`, `2`, or `3` to select one of the sample files or input your own file name.

2. **Output Prompt**:
```bash
Enter the desired name of the output file with extension:
```
Provide the filename for the output file with extension (typically .txt) and press Enter.

3. **Example Output**:
```bash
Text analysis of data/hamilton.txt
Word count: 967
Sentence count: 29
Unique words count: 387
Average sentence length (words per sentence): 33.34
Lexical diversity: 0.4
Readability score: 33.89
Readability level: College: Difficult to read.
10 Most common words: 
	the
	of
	to
	a
	be
	that
	and
	would
	in
	we
Word frequency: 
	to: 43
	the: 74
	people: 3
 ...
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
