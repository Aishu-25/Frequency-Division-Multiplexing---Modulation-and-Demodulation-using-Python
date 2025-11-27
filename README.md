# Frequency-Division-Multiplexing---Modulation-and-Demodulation-using-Python

__Aim__:

To generate an FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab). Observe time & frequency domain signals and measure recovery quality.


__Apparatus Required__:

Google Colab (or any Python environment)

Python libraries: numpy, matplotlib, scipy (scipy.signal)


__Theory__:

FDM places different message signals in separate, non-overlapping frequency bands by modulating each message onto a distinct carrier frequency. The multiplexed signal is the sum of all modulated channels. At the receiver, bandpass filters (or tuned filters) isolate each channel; then each isolated carrier is demodulated (coherently multiplied by a synchronized carrier) and low-pass filtered to recover the original baseband.

__Procedure__:

1 — Imports and parameters

2 — Create message signals and carriers

3 — Modulate each message (standard AM DSB-SC) and form FDM signal

4 — Frequency domain (spectrum) of FDM signal

5 — (Optional) Add AWGN noise to FDM signal

6 — Receiver: isolate each channel with bandpass filter

7 — Demodulate each isolated channel (coherent) and low-pass filter to recover baseband

__Output_:
<img width="759" height="786" alt="image" src="https://github.com/user-attachments/assets/9eda3af7-29da-4fd6-adbb-c44c8b4306a3" />
<img width="753" height="695" alt="image" src="https://github.com/user-attachments/assets/9efd757f-b524-42d0-b46e-3a9dfa6c4bed" />
<img width="758" height="697" alt="image" src="https://github.com/user-attachments/assets/7b26cd00-a62e-442e-b13e-44f1732c3528" />

__Result__:
Thus the frequency division multiplexing technique was successfully implemented using SCILAB.
