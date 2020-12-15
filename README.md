[![Mailing list : test](http://img.shields.io/badge/Email-gray.svg?style=for-the-badge&logo=gmail)](mailto:hello@silero.ai) [![Mailing list : test](http://img.shields.io/badge/Telegram-blue.svg?style=for-the-badge&logo=telegram)](https://t.me/joinchat/Bv9tjhpdXTI22OUgpOIIDg) [![License: CC BY-NC 4.0](https://img.shields.io/badge/License-MIT-lightgrey.svg?style=for-the-badge)](https://github.com/snakers4/silero-vad/blob/master/LICENSE) 
 
[![Open on Torch Hub](https://img.shields.io/badge/Torch-Hub-red?logo=pytorch&style=for-the-badge)](https://pytorch.org/hub/snakers4_silero-vad/) (coming soon)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/snakers4/silero-vad/blob/master/silero-vad.ipynb)

![header](https://user-images.githubusercontent.com/12515440/89997349-b3523080-dc94-11ea-9906-ca2e8bc50535.png)

- [Silero VAD](#silero-vad)
  - [Getting Started](#getting-started)
    - [PyTorch](#pytorch)
    - [ONNX](#onnx)
  - [Metrics](#metrics)
    - [Performance Metrics](#performance-metrics)
    - [Quality Metrics](#quality-metrics)
  - [FAQ](#faq)
    - [How VAD Works](#how-vad-works)
    - [VAD Quality Metrics Methodology](#vad-quality-metrics-methodology)
    - [How Number Detector Works](#how-number-detector-works)
    - [How Language Classifier Works](#how-language-classifier-works)
  - [Contact](#contact)
    - [Get in Touch](#get-in-touch)
    - [Commercial Inquiries](#commercial-inquiries)


# Silero VAD

`Single Image Why our VAD is better than WebRTC`

Silero VAD: pre-trained enterprise-grade Voice Activity Detector (VAD), Number Detector and Language Classifier.
Enterprise-grade Speech Products made refreshingly simple (see our [STT](https://github.com/snakers4/silero-models) models).

Currently, there are hardly any high quality / modern / free / public voice activity detectors except for WebRTC Voice Activity Detector ([link](https://github.com/wiseman/py-webrtcvad)).

Also in enterprise it is crucial to be able to anonymize large-scale spoken corpora (i.e. remove personal data). Typically personal data is considered to be private / sensitive if it contains (i) a name (ii) some private ID. Name recognition is highly subjective and would depend on locale and business case, but Voice Activity and Number detections are quite general tasks.

**Key features:**

- Modern, portable;
- Lowe memory footprint;
- Superior metrics to WebRTC;
- Trained on huge spoken corpora and noise / sound libraries;
- Slower than WebRTC, but fast enough for IOT / edge / mobile applications;

**Typical use cases:**

- Spoken corpora anonymization;
- Voice activity detection for IOT / edge / mobile use cases;
- Data cleaning and preparation, number and voice detection in general; 

## Getting Started

The models are small enough to be included directly into this repository. Newer models will supersede older models directly.

Currently we provide the following functionality:

| PyTorch           | ONNX               | VAD                 | Number Detector | Language Clf | Languages              | Colab |
|-------------------|--------------------|---------------------|-----------------|--------------|------------------------|-------| 
| :heavy_check_mark:| :heavy_check_mark: | :heavy_check_mark:  |                 |              | `ru`, `en`, `de`, `es` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/snakers4/silero-vad/blob/master/silero-vad.ipynb) |

**Version history:**

| Version | Date        | Comment                                           |
|---------|-------------|---------------------------------------------------|
| `v1`    | 2020-12-15  | Initial release                                   |
| `v2`    | coming soon | Add Number Detector or Language Classifier heads  |

### PyTorch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/snakers4/silero-vad/blob/master/silero-vad.ipynb)

[![Open on Torch Hub](https://img.shields.io/badge/Torch-Hub-red?logo=pytorch&style=for-the-badge)](https://pytorch.org/hub/snakers4_silero-vad/) (coming soon)

```python
TBD
```

### ONNX

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/snakers4/silero-vad/blob/master/silero-vad.ipynb)

You can run our model everywhere, where you can import the ONNX model or run ONNX runtime.

```python
TBD
```

## Metrics

### Performance Metrics

Speed metrics here.

### Quality Metrics

Quality metrics here.

## FAQ

### How VAD Works

Bla-bla, 300ms, 15ms latency on 1 thread, see examples (naive, streaming).

### VAD Quality Metrics Methodology

TBD

### How Number Detector Works

TBD

### How Language Classifier Works

TBD

## Contact

### Get in Touch

Try our models, create an [issue](https://github.com/snakers4/silero-vad/issues/new), start a [discussion](https://github.com/snakers4/silero-vad/discussions/new), join our telegram [chat](https://t.me/joinchat/Bv9tjhpdXTI22OUgpOIIDg), [email](mailto:hello@silero.ai) us.

### Commercial Inquiries

Please see our [wiki](https://github.com/snakers4/silero-models/wiki) and [tiers](https://github.com/snakers4/silero-models/wiki/Licensing-and-Tiers) for relevant information and [email](mailto:hello@silero.ai) us directly.
