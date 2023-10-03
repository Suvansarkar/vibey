# Vibey

Vibey is a bash script that turns your voice into music. It allows you to record your voice as you say the name of a song and plays it back for you. With Vibey, you can enjoy a hands-free and interactive way to control your music playback.

## Dependencies

Before using Vibey, make sure you have the following dependencies installed:

- [vosk](https://github.com/alphacep/vosk-api): A speech recognition toolkit
  ```python
  pip3 install vosk
  ```
  Additionally, you need to download a VOSK model from [here](https://alphacephei.com/vosk/models). The small model will suffice for this project as the big ones are overkill. Store the file locally and change the `VOSK_MODEL_PATH` in the vibey file to its path.
- [ffmpeg](https://www.ffmpeg.org/): A powerful multimedia framework (used for recording audio)
- [google_speech](https://pypi.org/project/google-speech/): A Python library for Google Speech Recognition
  ```python
  pip3 install google_speech
  ```
- [yt-dlp](https://github.com/yt-dlp/yt-dlp): A command-line program to download videos from YouTube
  ```python
  pip3 install yt-dlp
  ```

## Usage

1. Clone the Vibey repository to your local machine:

   ```bash
   git clone https://github.com/Suvansarkar/vibey.git
   cd vibey
   ```
2. Install the required dependencies if you haven't already.

3. Run Vibey:
   ```bash
   ./vibey
   ```
4. Speak out the name of the song you desire to be played out loud into the microphone(not too loud).
5. Vibey will process your input and play the requested song.

   Enjoy your music with vibey!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details
