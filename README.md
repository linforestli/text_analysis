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

The Python Notebook is publicly accessible through [Text Analysis Tool - Google Colab](https://colab.research.google.com/drive/1kcKcE2turc6P_Dc4YsNneGe3rgA-q5zY?usp=sharing).

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
Text analysis of data/thelifeofchuck.txt
Word count: 2350
Sentence count: 120
Unique words count: 923
Average sentence length (words per sentence): 19.58
Lexical diversity: 0.39
Readability score: 62.43
Readability level: 10th to 12th grade: Fairly difficult to read.
10 Most common words:
    the
    and
    to
    of
    a
    in
    that
    is
    it
    he
Word frequency:
    the: 150
    and: 120
    ...
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
