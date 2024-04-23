# Speech Recognition with Flask and SocketIO

This project demonstrates how to perform real-time speech recognition using Flask and SocketIO. It provides endpoints to upload audio files or stream audio data to receive transcriptions in return.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt

## Usage
1. Run the Flask application:
    ```bash
    python app.py
2. Use the provided endpoints to interact with the application:

   - /upload-audio: POST endpoint to upload an audio file and receive a transcription.
   - /: Home route.

## Dependencies

- Flask: A micro web framework for Python.
- Flask-SocketIO: WebSocket support for Flask applications.
- SpeechRecognition: Library for performing speech recognition.
- flask_cors: Cross-Origin Resource Sharing (CORS) support for Flask.
- gevent: A coroutine-based Python networking library that uses greenlet.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
