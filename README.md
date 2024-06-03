# blockchain-hub
blockchain hub

This script demonstrates a variety of tasks such as fetching web content, extracting text, translating it, saving to a file, encrypting the file, and serving the result via an HTTP server using 10 different npm packages.

## How It Works

1. **Fetching Web Content**: Uses the `axios` package to download the content of a webpage.
2. **Extracting Text from HTML**: Utilizes the `cheerio` package to parse HTML and extract text.
3. **Translating Text**: Employs the `google-translate-api` package to translate the text to another language (e.g., Spanish).
4. **Saving Translated Text to a File**: Uses the `fs-extra` package to write the translated text to a file.
5. **Encrypting the File**: Uses the `crypto` package to encrypt the file.
6. **Creating an HTTP Server**: Uses the `express`, `body-parser`, `morgan`, and `cors` packages to create and configure an HTTP server.
7. **Environment Configuration**: Uses the `dotenv` package to manage environment variables.

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/repository-name.git
    cd repository-name
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Create a `.env` File**:
    Create a `.env` file in the root directory with the following content:
    ```env
    ENCRYPTION_KEY=mysecretkey
    PORT=3000
    ```

4. **Run the Script**:
    ```bash
    node script.js
    ```
