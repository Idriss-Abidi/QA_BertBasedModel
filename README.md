# ENSIAS Chatbot

This simple chatbot uses Streamlit and the Hugging Face Transformers library to answer questions about ENSIAS (National School of Computer Science and Systems Analysis).

Powered by the Hugging Face question-answering pipeline, it delivers precise responses to user queries based on provided context, enhancing user interaction and accessibility.

# What is a Question-Answering Pipeline?

A question-answering pipeline is a model that takes a question and a context as inputs and returns an answer derived from the context. It utilizes pre-trained models, such as those fine-tuned on the SQuAD (Stanford Question Answering Dataset) to understand and extract the most relevant information from the given context to answer the question.

![Interface](./images/HuggingFace_QApipeline.png?raw=true "Title")

<div align="center">
    <img src="./images/app.png" alt="Interface" width="500">
</div>

# Features

The chatbot can answer questions on the following topics:
![Interface](./images/Context.png?raw=true "Title")
### Information about ENSIAS
- What is ENSIAS?
- When was ENSIAS founded?
- Where is ENSIAS located?
- What programs does ENSIAS offer?

<img src="./images/app_1.png" alt="Interface" width="600">
<img src="./images/app_2.png" alt="Interface" width="600">
<img src="./images/app_3.png" alt="Interface" width="600">

### Study Fields of ENSIAS
- How many study fields are available to engineering students at ENSIAS?
- Can you list the study fields offered at ENSIAS?
- What does BI&A stand for?
- What does GD stand for?
- What does GL stand for?
- What does IDSIT stand for?
- What does IDF stand for?
- What does 2IA stand for?
- What does SSI stand for?
- What does 2SCL stand for?
- What does SSE stand for?

<img src="./images/app_4.png" alt="Interface" width="600">

### Admission to ENSIAS
- How competitive is admission to ENSIAS?
- What determines admission to ENSIAS?
  
<img src="./images/app_5.png" alt="Interface" width="600">

### Information about the Director
- Who is the current director of ENSIAS?
- When did Ms. Ilham Berrada become the director of ENSIAS?
- What is the role of Ms. Ilham Berrada at ENSIAS?

<img src="./images/app_6.png" alt="Interface" width="600">


## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/Idriss-Abidi/ENSIAS-ChatBot_QA-huggingface.git
    cd ENSIAS-ChatBot_QA-huggingface
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Make sure you have the `transformers` package installed. If not, install it using:
    ```bash
    pip install transformers
    ```

4. Ensure you have Streamlit installed. If not, install it using:
    ```bash
    pip install streamlit
    ```

## Running the Application

1. Navigate to the directory containing the `main.py` file.
    ```bash
    cd src
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run main.py
    ```

4. Open your web browser and go to the URL provided by Streamlit, typically `http://localhost:8501`.

## File Structure

- `main.py`: The main script to run the Streamlit chatbot application.
- `requirements.txt`: List of Python packages required for this project.
- `Detailed_Approach.py`: Demonstrates how to use the Hugging Face transformers library to create a question-answering model.

## Usage

- Start the Streamlit application by running the command mentioned above.
- The application will display a simple interface where you can ask questions about ENSIAS.
- The chatbot will generate answers based on the provided context.
