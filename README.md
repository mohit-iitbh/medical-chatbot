# medical-chatbot
Chatbot able to interact with the users and respond to their queries related to medical terminologies.

## Data used
pdf format of the book "The Gale Encyclopedia of Medicine second edition volume 1"

## LLM used
**open-source** LLama2 7b quantized model <br/>
HuggingFace model link: https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin

## Interface designing
used **chainlit** package for the UI as it is an **open-source** Python package to build production ready Conversational AI.

## Using the medical-chatbot locally in the CPU machine
1) Install the dependencies by using the requirements.txt file by running the command: **pip install -r requirements.txt**
2) Download the model from the given HuggingFace website link
3) Command for running the chatbot: **chainlit run medbot_app.py -w**
