Audio_Video_Transcribe_Translate

Turn any audio or video into text and subtitles and also translate it. Freeand nothing to install. It runs in your browser on Google Colab.

What it does
Transcribes audio and video in 99 languages
Handles mixed languages, like Hindi with some English
Translates the text into other languages
Gives you .txt and .srt subtitle files in the original language and in the translation
Uses the GPU if you have one and the CPU if you don't. It picks by itself

Credits

Faster-Whisper (SYSTRAN), Whisper (OpenAI), NLLB-200 (Meta), and Gradio for the interface.

how it works

It runs Faster-Whisper, a faster rebuild of OpenAI's Whisper. The Faster-Whisper project says it's up to 4x faster for the same accuracy, and it uses less memory.
Translation uses Google Translate. If Google is busy, it switches to Meta's offline NLLB-200 model. That one is free too, but the first download is big.

Watch the video guide
Watch the following video guide

https://youtu.be/ZoOom2Wbxs8

