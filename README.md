# AIVideoShortsGenerator - 100 % Free

This Python script automates the creation of short AI-generated videos suitable for platforms like YouTube Shorts, Instagram Reels, and TikTok. It takes a desired topic as input, generates a concise script using an LLM, finds relevant stock footage, creates a voiceover, edits the video with subtitles, and uploads it to specified social media platforms (currently YouTube and X are implemented for upload).

## Overview 🧐

The primary goal of this project is to streamline the process of creating engaging short videos for social media by:

* Generating compelling and concise video scripts based on a user-provided topic.
* Automatically sourcing relevant stock videos from Pixabay.
* Creating a natural-sounding voiceover for the script using a text-to-speech engine.
* Editing the video by merging the footage and voiceover, and adding dynamic subtitles.
* Providing functionality to automatically upload the generated video to YouTube Shorts and X.

## Technologies Used 💻

* **Python**
* **OpenAI (via OpenRouter):** For generating free video scripts using a powerful language model (Deepseek) 🧠.
* **Pixabay API:** For sourcing royalty-free stock videos 🖼️.
* **edge-tts:** For generating free natural-sounding voiceovers 🗣️.
* **MoviePy:** For free video editing tasks, including merging audio and video, and adding subtitles 🎬.
* **Tweepy:** For uploading videos to X 🐦.
* **Google API Client:** For uploading videos to YouTube 📺.
* **Other Libraries:** pandas, numpy, librosa, soundfile, asyncio, etc. for various utilities.

## Key Features ✨

* **Automated Script Generation:** AI-powered script creation tailored for short, engaging social media content.
* **Automatic Video Sourcing:** Fetches relevant stock footage from Pixabay based on the topic.
* **Text-to-Speech Voiceover:** Creates a natural-sounding voiceover for the generated script.
* **Dynamic Subtitles:** Adds stylized and dynamically positioned subtitles to the video.
* **Video Editing:** Combines the video, voiceover, and subtitles into a final video.
* **Automated Upload:** Implements functionality to directly upload the generated video to YouTube Shorts and X.
* **Customizable Topic:** Easily change the `desired_topic` to create videos on various themes.

## Potential Improvements ✨

* **More Platform Support:** Implement automated upload functionality for Instagram Reels and TikTok.
* **Advanced Video Editing:** Explore more sophisticated video editing techniques, transitions, and effects.
* **Background Music:** Add the option to include royalty-free background music.
* **Visual Enhancements:** Integrate more advanced visual elements and animations.
* **Topic Generation:** Automate the topic selection process.

## Contributing

Contributions to this project are welcome. Feel free to fork the repository and submit pull requests with improvements or bug fixes.
