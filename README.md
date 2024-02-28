# Speech and Image to Text Chatbot
Welcome to the Speech and Image to Text Chatbot project! This chatbot is designed to take queries in the form of speech and images, providing textual responses through both text and speech outputs. The project utilizes the "llava-hf/llava-1.5-7b-hf" model for image analysis and the Whisper ASR system for transcribing speech.

Features
### Speech Input:

Users can interact with the chatbot by providing queries through speech input.
Whisper ASR system is employed for accurate and efficient speech-to-text conversion.

### Image Input:

Users can input queries through images.
The "llava-hf/llava-1.5-7b-hf" model is used for comprehensive image analysis to understand and respond to queries.

### Text Output:

The chatbot provides textual responses to user queries.
Responses are generated based on the analysis of both speech and image inputs.

### Speech Output:

In addition to text responses, the chatbot can generate speech outputs for a more interactive experience.

### Dependencies
#### Whisper:

The project relies on the Whisper ASR system for transcribing speech input.
llava-hf/llava-1.5-7b-hf:

This model is used for image analysis and understanding queries presented through images.
Installation

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/your-repo.git
cd your-repo
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Download and set up the Whisper ASR model and the llava-hf/llava-1.5-7b-hf model according to their respective documentation.

Usage
Run the chatbot: (opens in gradio)

bash
Copy code
python chatbot.py

Credits
Whisper ASR System: https://github.com/openai/whisper
llava-hf/llava-1.5-7b-hf Model: https://huggingface.co/llava-hf/llava-1.5-7b-hf

Feel free to contribute, report issues, or suggest improvements
