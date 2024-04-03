# Demo: Low-complexity Real-time Neural Network for Blind Bandwidth Extension of Wideband Speech
This repository contains the demo page for the paper **Low-complexity Real-time Neural Network for Blind Bandwidth Extension of Wideband Speech** by
Esteban Gómez, Mohammad Hassan Vali and Tom Bäckström from the Department of Information and Communications Engineering, Aalto University, Espoo, Finland and
Voicemod S.L., Valencia, Spain. The paper has been peer reviewed and published in the proceedings of the 31st European Signal Processing Conference, EUSIPCO 2023.

# Abstract
Speech is streamed at 16 kHz or lower sample rates in many applications (e.g. VoIP, Bluetooth headsets). Extending its bandwidth can produce significant quality improvements.
We introduce BBWEXNet, a lightweight neural network that performs blind bandwidth extension of speech from 16 kHz (wideband) to 48 kHz (fullband) in real-time in CPU.
Our low latency approach allows running the model with a maximum algorithmic delay of 16 ms, enabling end-to-end communication in streaming services and scenarios where the
GPU is busy or unavailable. We propose a series of optimizations that take advantage of the U-Net architecture and vector quantization methods commonly used in speech coding,
to produce a model whose performance is comparable to previous real-time solutions, but approximately halving the memory footprint and computational cost. Moreover, we show that
the model complexity can be further reduced with a marginal impact on the perceived output quality.

# Download
Click [here](https://research.aalto.fi/en/publications/low-complexity-real-time-neural-network-for-blind-bandwidth-exten) to download the paper.

# Cite
Please use the following BIBTEX code to cite this work. Additional formats can be found in the **Cite this** section of the [download page](https://research.aalto.fi/en/publications/low-complexity-real-time-neural-network-for-blind-bandwidth-exten).

```
@inproceedings{BBWEXNetEUSIPCO23,
  title = "Low-complexity Real-time Neural Network for Blind Bandwidth Extension of Wideband Speech",
  keywords = "bandwidth extension, speech processing, real-time, deep learning",
  author = "{G{\'o}mez Mellado}, Esteban and Mohammadhassan Vali and Tom B{\"a}ckstr{\"o}m",
  year = "2023",
  month = sep,
  day = "4",
  doi = "10.23919/EUSIPCO58844.2023.10290072",
  language = "English",
  series = "European Signal Processing Conference",
  publisher = "European Association For Signal and Imag Processing",
  pages = "31--35",
  booktitle = "31st European Signal Processing Conference, EUSIPCO 2023 - Proceedings",
  note = "European Signal Processing Conference, EUSIPCO ; Conference date: 04-09-2023 Through 08-09-2023",
  url = "https://eusipco2023.org/",
}
```
