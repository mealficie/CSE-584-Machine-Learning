# Unveiling AI-Generated Text

This project presents a comprehensive analysis of AI-generated text, focusing on the detection and classification of outputs from various Large Language Models.

## Project Description

This project was originally prepared using Kaggle's online notebook editor. However, it can be replicated on local machines with the proper setup and library installations.

## Installation

1. Clone this repository:

2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```

3. Download additional NLTK data:
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   ```

4. Download the spaCy English model:
   ```
   python -m spacy download en_core_web_sm
   ```

## Running the Project

1. Open the Jupyter notebook or Python script containing the main project code.

2. Ensure that all file paths in the code are updated to match your local directory structure.

3. Run the cells in the notebook or execute the Python script.

## Note

This project was originally developed in a Kaggle environment. When running on a local machine, make sure to adjust file paths and data loading methods accordingly. The provided code assumes certain directory structures and file locations that may need to be modified based on your local setup.

## Libraries Used

The project uses several Python libraries, including:
- transformers
- pandas
- torch
- scikit-learn
- tqdm
- matplotlib
- seaborn
- nltk
- spacy

Refer to the `requirements.txt` file for the complete list of dependencies.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

MIT License

Copyright (c) [2024] [mealficie]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



