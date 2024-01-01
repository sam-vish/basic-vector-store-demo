# Vector Store Repository

This repository contains Python scripts demonstrating a basic Vector Store implementation using the `VectorStore` class.

## Files

- **`vector_store.py`**: Contains the `VectorStore` class that implements basic functionalities for storing and searching vectors.
- **`app.py`**: Demonstrates the usage of the `VectorStore` class to tokenize sentences, create vectors, store them, and search for similar sentences.

## Description

The `VectorStore` class within `vector_store.py` provides methods to add vectors, retrieve vectors, update an index structure for similarity search, and find similar vectors based on cosine similarity.

The `app.py` script showcases a simple use case of the `VectorStore` class. It tokenizes sentences, generates vector representations based on word frequencies, stores these vectors in the `VectorStore`, and performs a similarity search using a query sentence.

## Usage

To run the `app.py` script:

1. Clone this repository.
2. Ensure you have Python installed.
3. Open a terminal and navigate to the repository folder.
4. Run `python app.py`.

## Requirements

- Python 3.x
- NumPy

## Example Output

Running `app.py` with the provided sentences will display the query sentence and the most similar sentences based on word frequency vectors.

## Contributing

Contributions are welcome! Feel free to suggest improvements, report issues, or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
