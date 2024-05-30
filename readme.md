# FreeScribe

This web application allows users to transcribe and translate audio files. Users can upload audio files or record audio manually, and the app will provide a transcription of the audio. Additionally, users can translate the transcribed text into multiple languages.

## Installation

Follow these steps to set up the project locally:

### Clone the Repository

```
git clone https://github.com/Tirth29/FreeScribe.git
cd free-scribe
```
### Install Dependency
```
npm i
```
### Start the Development Server
```
npm run dev
```

## Usage

1. Upload or Record Audio
* Use the upload button to select an audio file from your device.
* Alternatively, use the record button to capture audio manually.
2. Transcription
* Once the audio is uploaded or recorded, the app will automatically start the transcription process.
* The transcribed text will be displayed on the screen.
3. Translation
* After transcription, select a language from the dropdown menu to translate the transcribed text.
* The translated text will be displayed alongside the original transcription.

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **Web Workers**: For running scripts in background threads.
- **@xenova/transformers**: A powerful library for handling transcription and translation tasks.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

-Tirth Solanki