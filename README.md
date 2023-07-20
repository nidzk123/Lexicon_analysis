# Lexicon Delivery for Kazakh Language - Python Solution

This is a Python script to process a corpus of sentences in the Kazakh language. The script reads tokenized and lemmatized data from a JSON file, performs calculations, and generates output in JSON format. The output contains information about lemmas, their part-of-speech labels, inflection information, total frequency counts, and wordform frequency counts.

## Requirements

- Python 3.x
- Pydantic library (install using `pip install pydantic`)

## Usage

1. Place the `sample_parsed_sentences.json` file containing tokenized and lemmatized data in the same directory as the script.

2. Run the Python script:


python script.py


3. The output will be saved as `output.json` in the same directory.

## Data Processing

The script processes the input JSON data and calculates the required information as follows:

- It reads the tokenized and lemmatized data from the `sample_parsed_sentences.json` file.

- For each lemma, it accumulates information about the part-of-speech, inflection, total frequency count, and wordform frequency count.

- The script uses Pydantic data models to represent token information, lemma information, and the final output.

- Finally, the processed output is saved as `output.json`.


## Notes

- Ensure that the `sample_parsed_sentences.json` file is correctly formatted and contains the required tokenized and lemmatized data in the specified structure.

- The code uses Pydantic to create data models for validation and easy parsing. If required, you can modify the models to accommodate specific use cases.

- Handle potential errors or edge cases, such as missing or invalid data, when deploying the solution in a production environment.

## Contact

If you have any questions or need further assistance, feel free to contact nidhi.kumaritj3@gmail.com.

