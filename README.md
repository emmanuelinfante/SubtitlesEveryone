<div align="center">
<img src="https://github.com/emmanuelinfante/SubtitlesEveryone/blob/main/SUB.png" /><br>
<h1>SubtitlesEveryone</h1>
<i>Transcribe Like a Pro, Without Paying a Penny!</i><br><br>

[![Open In Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/github/emmanuelinfante/SubtitlesEveryone/blob/main/SubtitlesEveryone.ipynb)
[![Licence](https://img.shields.io/badge/LICENSE-MIT-green.svg?style=for-the-badge)](https://github.com/emmanuelinfante/SubtitlesEveryone?tab=MIT-1-ov-file#readme)

</div>

---

This repository allows you not only to create subtitles in a completely unlimited and free manner, but also allows you to:

- 🌍 Translate your subtitle with more than 20 translators! With the help of **[Translators!](https://pypi.org/project/translators)**

- ![](https://github.com/emmanuelinfante/SubtitlesEveryone/blob/main/mini%20deepl.png) Translate your subtitle with DeepL completely free and unlimited, with the help of **[SrtTranslators!](https://pypi.org/project/srtranslator/)**
- 🎷 Improve the [WhisperX](https://github.com/m-bain/whisperX) transcription with the help of **[Demucs](https://github.com/facebookresearch/demucs)**, extract the vocals, and no longer have any errors with Vad!

### Improvements to WhisperX with the help of Demucs 🎷
We have noticed that WhisperX has very serious errors when VAD is used in oriental languages. This is because VAD cannot differentiate between non-voice sounds and voice, causing it to end up eliminating sections where there is voice. The solution to this is to use Demucs to extract the voice, and with this, the transcription improves significantly, in any language.

### Translators as subtitle translator 
Originally, Translatros was not created to translate subtitles; however, we adapted the code for subtitle translation, which allows you and anyone else to translate subtitles into many languages, with over 20 translators, and completely free of charge 🥳

## News 🚨
- Soon, we will upload a video explaining how to properly use the Google Colab notebook! ✨

---

## **Credits and Special Thanks**
This notebook combines many free libraries from Github and PyPI to achieve its purpose. Below, I will share what they are:

- [**WhisperX** - Artificial Intelligence for Transcription](https://github.com/m-bain/whisperX)
- [**Translators** - Library with API for over 10 languages](https://pypi.org/project/translators/)
- [**Srt** - Necessary for reading .srt files](https://pypi.org/project/srt/)
- [**Demucs** - For voice extraction](https://pypi.org/project/demucs/)
- [**Ctranslate2** - Necessary for WhisperX](https://pypi.org/project/ctranslate2/)
- [**Yt-dlp** - for video downloading](https://pypi.org/project/yt-dlp/)
- [**Ip-Rotator** - Proxy for APIs](https://pypi.org/project/ip-rotator/)
- [**Srtranslator** - Subtitle Translation with Deepl](https://pypi.org/project/srtranslator/)

Important Clarification, this notebook also uses its own code for subtitle creation; Translators **were not created to translate subtitles, I had to write the code myself to make it work that way.** Still, I greatly appreciate the team behind all these projects, they are crucial to making this project possible! With nothing more to say, Enjoy this project!
