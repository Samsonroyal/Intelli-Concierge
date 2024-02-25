# Intelli Concierge

Intelli Concierge is a web application with a voice assistant powered by AI. It leverages models such as Falcon, Claude 2, GPT3.5, and Mistral to perform text-to-speech (TTS) and automatic speech recognition (ASR). The ASR functionality is dependent on the Retell API.

## Features

- Voice assistant powered by AI
- Text-to-speech (TTS) using Falcon and Claude 2 models
- Automatic speech recognition (ASR) using GPT3.5 and Mistral models
- Integration with the Retell API for ASR functionality

## Deployment

The AI models are housed in a Docker container on the Google Cloud Platform. The infrastructure is managed using the Infra Run service.

## Getting Started

To get started with Intelli Concierge, follow these steps:

1. Clone the repository: `git clone https://github.com/Samsonroyal/Intelli-Concierge.git`
2. Install the necessary dependencies: `npm install`
3. Configure the Retell API credentials in the application
4. Build and run the Docker container on the Google Cloud Platform

## Usage

Once the application is deployed and running, you can interact with the voice assistant by speaking commands or asking questions. The assistant will respond accordingly using the TTS functionality.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

