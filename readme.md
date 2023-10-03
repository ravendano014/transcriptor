# Audio Transcription Web Application

This web application is designed to transcribe audio files using the AssemblyAI API. It allows users to easily transcribe audio content from a given URL and view the transcribed text on the web page.

## Features

- Transcribe audio from a specified URL.
- Display the transcription result on the webpage.
- User-friendly interface with a single "Start Transcription" button.
- Real-time update of transcription status.

## Getting Started

Follow these steps to use the Audio Transcription Web Application:

1. Clone or download this repository to your local machine.

2. Open the `index.html` file in a web browser.

3. Click the "Start Transcription" button to initiate the transcription process.

4. Wait for the transcription to complete. The transcription result will be displayed on the webpage.

## Requirements

- An internet connection to access external JavaScript libraries and the AssemblyAI API.
- An AssemblyAI API token. Replace `YOUR_API_TOKEN` in the JavaScript code with your actual API token.

## Technologies Used

- HTML: For structuring the web page.
- CSS: For styling the web page.
- JavaScript: For interacting with the AssemblyAI API and updating the webpage.

## How It Works

1. The user clicks the "Start Transcription" button.

2. The JavaScript code sends a POST request to the AssemblyAI API with the URL of the audio file to be transcribed.

3. The code then periodically checks the transcription status using a polling mechanism.

4. Once the transcription is completed, the result is displayed on the webpage in the `transcriptionText` element.

## Troubleshooting

- If the transcription fails, an error message will be displayed.
- Ensure that you have a valid API token and that the audio file URL is accessible.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project uses the AssemblyAI API for audio transcription.

---

Feel free to contribute to this project or provide feedback. If you encounter any issues, please open an issue on GitHub.
