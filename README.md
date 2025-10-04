# Donate & Support Innovation
If you would like to support our research and development, you can donate in **XRP (Ripple)**.  
Every contribution helps us continue advancing AI and open research. 🙏  

Network: XRP - Ripple

Currency: XRP

Address: 
```
rnrqyM7kS6wmC5demJm9vrfdN2vLgS8LfY
```

Destination Tag: 
```
1086890406
```

Developer Email : nkrafafakevoicedetection@gmail.com

# Model Architecture
Mask CNN-4

![IMG_5624](https://github.com/user-attachments/assets/687420d1-e60b-4d47-907b-a5a74980caf8)

Mask SE-ResNet-34

![IMG_5622](https://github.com/user-attachments/assets/7ec5fb51-49ae-42e5-b958-4c35656d92bd)

Mask SE-ResNeXt-152

![IMG_5623](https://github.com/user-attachments/assets/1ef7ef46-b432-4296-b169-52f844bfa580)

# FakeVoiceDetection
About Implementation of Anon and Payap's Fake Voice Detection Model of Public Figures
<img width="1275" height="746" alt="MasK_SE-ResNeXt-152" src="https://github.com/user-attachments/assets/102e5522-371f-4d9e-a6ff-4703818320f7" />

Reference

[1] Bangsan, A., & Sirinam, P. (2025). The Application of Generative Artificial Intelligence Technology in Voice Conversion. NKRAFA JOURNAL OF SCIENCE AND TECHNOLOGY, 21(2), 135–157. retrieved from https://ph02.tci-thaijo.org/index.php/nkrafa-sct/article/view/257352
[2] Bangsan, A., & Sirinam, P. (2026). Development of a Fake Voice Detection Model of Public Figures to Mitigate Disinformation in a Cyber Domain. KKU Science Journal, 54(1).

# DEMO

Web Application

```
http://soc3.ddns.net:9999/
```

# NKRAFA Thai Dataset

The authors of the paper used the dataset from the Spoke task of Navaminda Kasatriyadhiraj Royal Air Force Academy (NKRAFA). This is a dataset of non-parallel utterances from TM03 (male) speaker. There are 10 reals and 10 fakes for test in the real situation.

Download the dataset from google drive
```
https://drive.google.com/drive/folders/1NHfj5ogu8m8sDswCC7WTHYG5_EEEELjd
```
# Setup

Operating System.

```
Ubuntu 22.04.4 LTS 64-bit
```

Install Anaconda to create a Python environment for the model.

```
https://accuweb.cloud/resource/articles/install-anaconda-in-ubuntu-22-04-tutorial-for-beginners
```

Install CUDA Toolkit for using NVIDIA GPU’s CUDA capabilities.

```
https://www.cherryservers.com/blog/install-cuda-ubuntu
```

Clone the repository.

```
git clone git@github.com:NKRAFAVoiceAI/FakeVoiceDetection.git
cd FakeVoiceDetection
```

Create the conda environment.
```
conda env create -f environment.yml
conda activate FakeVoiceDetection
```
