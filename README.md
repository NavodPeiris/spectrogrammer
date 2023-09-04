# Spectrogramer 

spectrogramer is a library that provide ease to developers to extract spectrogram from their wav files.

example:

```
from spectro import get_spectrogram, plot_spectrogram
import numpy as np
import matplotlib.pyplot as plt

spectrogram = get_spectrogram("girl_scream.wav")

plot_spectrogram(spectrogram)

```