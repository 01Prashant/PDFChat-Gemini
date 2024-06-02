# PDFChat-Gemini

This project enables users to ask questions from multiple PDF files and get answers using Gemini, a conversational AI model. The project utilizes Streamlit for the user interface and various libraries for text extraction, vectorization, and question-answering.

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/01Prashant/PDFChat-Gemini
   cd flask-jwt-auth-api

2. **Create and activate a virtual environment:**

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install the dependencies:**

   ```sh
   pip install -r requirements.txt

## Usage

1. **Run the Streamlit app:**

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

2. Access the app in your web browser by navigating to the provided URL.
3. Ask questions from the uploaded PDF files by typing them into the text input field and clicking "Submit & Process".

## How It Works

1. The app allows users to upload multiple PDF files.
2. Upon submission, the text is extracted from the PDF files.
3. The text is split into chunks and vectorized using Google Generative AI Embeddings.
4. Conversational AI model Gemini is employed for question-answering.
5. Users can ask questions related to the content of the PDF files, and the app provides answers based on the provided context.

## Configuration

Ensure you have set up a Google API key and added it to your environment variables (`GOOGLE_API_KEY`).

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit pull requests.
