# -Generating-Roman-Urdu-Poetry-with-Language-Modelling

License

## Table of Contents
* Introduction
* Techniques
* Getting Started
* Usage
* Examples
* Contributing
* License

## Introduction
This repository contains a Python implementation of a Poetry Generator using Language Models. The generator explores three different techniques for generating poetic verses: Bigrams, Trigrams, and Bidirectional Models. By leveraging the power of natural language processing with bigrams, trigrams, and bidirectional models, the generator can produce captivating verses that mimic human creativity.

## Techniques
### Bigrams
Bigrams are a simple yet effective approach for generating poetry. The algorithm calculates the frequency of each pair of consecutive words in the corpus and uses these probabilities to predict the next word in a sequence. The generation process starts with an initial word, and subsequent words are selected based on bigram probabilities until the desired verse length is achieved.

### Trigrams
Trigrams extend the concept of bigrams by considering triplets of consecutive words. This allows for a more nuanced understanding of the language structure and context. The algorithm calculates the frequency of each trigram and generates poetry that is more coherent and contextually rich. Similar to bigrams, the process begins with an initial pair of words, and subsequent words are generated using trigram probabilities.

### Bidirectional Models
Bidirectional models combine the power of both forward and backward bigrams. By considering both the preceding and succeeding words, bidirectional models capture a broader context. In this approach, the generator selects an initial word and generates the next word using both forward and backward bigram probabilities. This bidirectional generation results in verses that exhibit a unique blend of contexts and associations.

## Getting Started
To get started with the Poetry Generator, follow these steps:
1. Clone the repo
`
git clone https://github.com/your_username/poetry-generator.git
cd poetry-generator
`
## Contributing
Contributions to the Poetry Generator are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request. For major changes, please open an issue to discuss the proposed changes beforehand.

## License
This project is licensed under the MIT License -
