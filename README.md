<div align="center">
<img src="https://github.com/emmanuelinfante/SubtitlesEveryone/blob/main/127122328.png" /><br>
<h1>SubtitlesEveryone</h1>
<i>Transcribe Like a Pro, Without Paying a Penny!</i><br><br>

[![Open In Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/github/emmanuelinfante/SubtitlesEveryone/blob/main/SubtitlesForEveryone.ipynb)
[![Licence](https://img.shields.io/badge/LICENSE-MIT-green.svg?style=for-the-badge)](https://github.com/emmanuelinfante/SubtitlesEveryone?tab=MIT-1-ov-file#readme)

</div>

---

This repository allows you not only to create subtitles in a completely unlimited and free manner, but also allows you to:

- 🌍 You can translate your subtitle with more than 20 translators! With the help of **[Translators!](https://pypi.org/project/translators)**

- [![image](https://github.com/emmanuelinfante/SubtitlesEveryone/blob/main/mini%20deepl.png)] Translate your subtitle with DeepL completely free and unlimited, with the help of **[SrtTranslators!](https://pypi.org/project/srtranslator/)**
- Improve the WhisperX transcription with the help of **[Demucs](https://github.com/facebookresearch/demucs)**, extract the vocals, and no longer have any errors with Vad!

### Improvements to WhisperX with the help of Demucs
We have noticed that WhisperX has errors when transcribing oriental languages ​​if the original audio has music in the background or sounds that are not really the voice. This is because VAD cannot differentiate between moments with music and moments with voice, and sometimes it tends to remove segments where there is voice. The solution to this is to use demucs to extract the voice and thus significantly improve the transcription.
