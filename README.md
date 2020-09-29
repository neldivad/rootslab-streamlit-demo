# Rootslab at lunch Demo: Real-Time Voice Cloning

This repository demonstrates how a simple voice transfer app can be created using [Streamlit](https://www.streamlit.io/). The code for this demo is based on the repository for [Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning).

This app allows you to:
* Record your voice
* Visualize the embedding of the speaker
* Synthesize speech based on the recorded voice


## Setup

### 1. Install Requirements
**Python 3.6 or 3.7** is needed

* Install [PyTorch](https://pytorch.org/get-started/locally/) (>=1.0.1).
* Install [ffmpeg](https://ffmpeg.org/download.html#get-packages).
* Run `pip install -r requirements_demo.txt` to install the remaining necessary packages.

### 2. Download Pretrained Models
Download the latest [here](https://github.com/CorentinJ/Real-Time-Voice-Cloning/wiki/Pretrained-models).

### 3. Launch streamlit demo

* `streamlit run demo_voice.py`