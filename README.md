# SEO Analysis Web App

This is a Streamlit web application that performs simple SEO analysis on a given URL. It extracts metadata such as title, keywords, and description, and then analyzes keyword density.

## Features

- **Metadata Analysis:**
  - Extracts and displays the title of the web page.
  - Retrieves and shows the keywords and description from the metadata.

- **Keywords Analysis:**
  - Displays the list of keywords extracted from the web page.

- **Description Analysis:**
  - Displays the description of the web page.

- **Keyword Density Analysis:**
  - Calculates the total number of words on the page.
  - Analyzes the keyword density (words per keyword) based on the provided keywords.

- **Most Common Words Analysis (commented out):**
  - Displays a table of the most common words on the web page.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Srish0218/SEO-Analysis-Web-App.git
    ```

2. Navigate to the project directory:

    ```bash
    cd SEO-Analysis-Web-App
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On Unix or MacOS:

        ```bash
        source venv/bin/activate
        ```

5. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to the provided URL (usually `http://localhost:8501`).

3. Enter the desired URL into the input field.

4. Explore the different sections for metadata, keywords, description, and keyword density analysis.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
- [Pandas](https://pandas.pydata.org/)
