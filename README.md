
# Chat With Multiple Documents

## Environment Setup (Optional but Highly Recommended)

1. Create a python environment (venv for example):

```bash
python -m venv venv
```

2. Activate the environment venv:

    On Windows:
      ```bash
      venv\Scripts\activate
      ```

    On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

Creating a virtual environment prevents dependency conflicts and ensures a cleaner project management.

## Installation

3. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

## API Key

4. Acquire a Gemini API key and put it in an .env file that you create in the same directory:

```bash
GOOGLE_API_KEY="your_api_key_here"
```

## Usage

5. Run the Streamlit app:

```bash
streamlit run app.py
```