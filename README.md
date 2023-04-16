# web-audio-spectrogram 

![o](https://user-images.githubusercontent.com/47185462/232289622-037f552c-ac51-40e7-9f1d-8395b072a782.gif)

Try : https://e04.github.io/web-audio-spectrogram/


This repository contains a simple implementation of a spectrogram using the WebAudio API.  A [spectrogram](https://en.wikipedia.org/wiki/Spectrogram) is a visual representation of the spectrum of frequencies of a signal as it varies with time.

This implementation uses the WebAudio API to create an audio context and capture audio from the user's microphone in real-time. It then performs a Fourier transform on small windows of the time-domain data to obtain frequency-domain data, which is used to create the spectrogram. The spectrogram is then displayed on a canvas element.

## Usage

To use this implementation, simply visit the [GitHub Pages site](https://e04.github.io/web-audio-spectrogram/) for this repository. Allow access to your microphone when prompted, and you should see the real-time spectrogram being displayed on the canvas.


